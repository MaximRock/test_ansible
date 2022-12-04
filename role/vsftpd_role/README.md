Role Name
=========

Установка и настройка VSFTPD

Role Variables
--------------

# path vsftpd.conf
path_vsftpd_conf: "/etc/vsftpd.conf"

# openssl_privatekey
path_ssl_private_key: "/etc/ssl/private"
filename_ssl_key: vsftpd.pem
size: 2048
type: RSA

# openssl_csr
filename_ssl_csr: vsftpd.csr
country_name: RU
organization_name: test
common_name: mysite.com
subject: CN=mysite.com,ST=MOW,L=Moscow
subject_alt_name: "DNS:mysite.com,DNS:www.mysite.com"

# openssl_certificate
filename_certificate: vsftpd_cert.pem

# user vsftpd
user_name: ftpuser
user_password: "user_password"
