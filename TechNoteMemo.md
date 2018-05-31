#PHPのログ出力メモ
syslogメソッドで出力するログで、syslog上のログレベルはsyslogの設定で管理する。

syslog(LOG_INFO, "[INFO] $pgname 処理開始");
syslog(LOG_DEBUG, "[DEBUG] $pgname デバッグ情報");

でDEBUGレベルまで出力したいなら、
/etc/rsyslog.conf
の
*.info
の値を
*.debug
に書き換える。

*.info
の場合はLOG_INFOは出力されるがLOG_DEBUGは出力されない。