postmap /opt/zimbra/conf/custom_header_checks

postconf -e "header_checks = regexp:/opt/zimbra/conf/custom_header_checks"

zimbra zmmtactl restart
