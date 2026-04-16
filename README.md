## x-ui


## SSL сертификат

### установка acme
curl https://get.acme.sh | sh
source ~/.bashrc

### Выпускаем сертификат
~/.acme.sh/acme.sh --issue --standalone -d DOMEN.NAME --force --register-account -m MY@gmail.com
### или
~/.acme.sh/acme.sh --issue --standalone -d DOMEN.NAME
