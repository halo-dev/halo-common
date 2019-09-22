Description=Halo Service
Documentation=https://halo.run
After=network-online.target
Wants=network-online.target

[Service]
Type=simple
ExecStart=/usr/bin/java -server -Xms256m -Xmx256m -jar JAR_PATH
ExecStop=/bin/kill -s QUIT $MAINPID
Restart=always
StandOutput=syslog

StandError=inherit

[Install]
WantedBy=multi-user.target
