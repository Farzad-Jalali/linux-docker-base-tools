# linux-docker-base-tools

You got a simple linux based docker (e.g. mongo or postgres) and you want to install stuff on it?


# install CURL

`
- apt-get update
- apt-get install curl
- curl --version
`

A message that is similar to the following is displayed:

`
curl 7.29.0 (x86_64-redhat-linux-gnu) libcurl/7.29.0 NSS/3.15.4 zlib/1.2.7 libidn/1.28 libssh2/1.4.3
Protocols: dict file ftp ftps gopher http https imap imaps ldap ldaps pop3 pop3s rtsp scp sftp smtp smtps telnet tftp
Features: AsynchDNS GSS-Negotiate IDN IPv6 Largefile NTLM NTLM_WB SSL libz
`



# install Node.JS v12.x: ( Using Ubuntu )

`
- curl -sL https://deb.nodesource.com/setup_12.x 
- apt-get install -y nodejs
`

or if you are in bash already just:


`
-curl -sL https://deb.nodesource.com/setup_12.x
-apt-get install -y nodejs

`




# to install git


`
- apt-get update
- apt-get install git
`


