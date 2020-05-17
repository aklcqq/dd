# dd
dd script from MoeClub.org

bash <(wget --no-check-certificate -qO- 'https://raw.githubusercontent.com/aklcqq/dd/master/InstallNET.sh') -d 10 -v 64 -a --ip-addr <ip> --ip-gate <gateway> --ip-mask <netmask> --mirror 'http://<mirror>'
