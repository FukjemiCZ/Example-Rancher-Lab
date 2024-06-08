# LAB Rancher

## Hosts
Je potřeba zde přidat 
- veřejnou IP serveru, na kterém bude nainstalován Rancher.
- Uvést uživatele, pod kterým se bude Ansible přihlašovat.

## Github Secrets
- VPS_IP - Přidej veřejnou IP adresu serveru, stejnou jako si přidal do Hosts.
- VPS_USER - Uživatel na serveru, pod kterým se přihlásíš k serveru pro instalaci Rancheru a v případě backupů.
- VPS_USER_PASSWORD - heslo ke tvému uživateli. Heslo se použije při přihlášení přes SSH k serveru.

## Install_rancher.yml
Koukni na proměnné, hlavne na
- rancher_domain
- rancher_version
- docker_version
