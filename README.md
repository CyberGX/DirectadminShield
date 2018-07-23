# Directadmin Shield
## Directadmin administration & hardening tools.

```shell
[root@centos7 DirectadminShield]# sh daShield -h 
 


  ____      _                ____       
 / ___|   _| |__   ___ _ __ / ___|_  __ 
| |  | | | | '_ \ / _ \ '__| |  _\ \/ / 
| |__| |_| | |_) |  __/ |  | |_| |>  <  
 \____\__, |_.__/ \___|_|   \____/_/\_\
      |___/                             
        Directadmin Shield - v1.0       
       https://github.com/CyberGx/      


Usage: daShield [OPTION]
Example: daShield -s


PHP Tools:
 --php                                Show PHP status
 --php --secure                       Secure PHP configuration
 --php --double-php                   Add second php to directadmin
 --php --set-timezone                 Set PHP timezone


Directadmin Tools:
--directadmin                         Show Directadmin status
--directadmin --change-port           Change directadmin port


Webserver Tools:
 --webserver                          Show Webserver status
 --webserver --install-mod-security   Install mod_security


Miscellaneous:
 -s, --show-status                    Show server status
 -h, --help                           Display this help text and exit
 ```