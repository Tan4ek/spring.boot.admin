# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

Стандартная админка слизанная с https://github.com/codecentric/spring-boot-admin
но поправленн context url

### How do I get set up? ###

Можно и нужно задавать пользователя через параметр запуска, аля: --auth.name=vasa_pupkin -- auth.pass=xer_ugodaesh --admin.domain=http://localhost:8080/ (с '/' в конце)

Для развернывания в heroku добавить config vars:
* AUTH_NAME=auth.name
* AUTH_PASS=auth.pass
* ADMIN_DOMAIN=admin.domain
