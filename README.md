# DevSecOps_Homework_11
Были найдены уязвимости в зависимых пакетах:

ansi-regex:4.1.0
ansi-regex:5.0.0
body-parser:1.19.0
braces:3.0.2
cookie:0.4.0
dicer:0.2.5	
express:4.17.1
got:9.6.0
http-cache-semantics:4.1.0
minimatch:3.0.4
minimist:1.2.5
normalize-url:4.5.0
path-to-regexp:0.1.7
qs:6.7.0
semver:5.7.1
semver:6.3.0
send:0.17.1
serve-static:1.14.1

Критичная уязвимость относится к пакету minimist:1.2.5.
Данной уязвимости подвержены пакеты Minimist <=1.2.5 версии.
В пакете данная уязвимость содержится в функции setKey(), строки 69-95.

Для устранения данной критичной уязвимости необходимо в проекте обновить зависимости, использовать более свежую версию данной библиотеки.