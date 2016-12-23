# Регистрация пользователя как сотрудника компании для учета в stackalytics

[Account setup](http://docs.openstack.org/infra/manual/developers.html#account-setup)

Необходимо зарегится на http://openstack.org и http://review.openstack.org. По пути получится аккаунт на launchpad, в дальнейшем для доступа будет использоваться он, т.к. gerrit и всякие другие опенстековские сервисы используют lauchpad oauth.
При этом на openstack.org надо повысить аккаунт до Foundation Member

После всего этого надо согласиться с Individual Contributor License Agreement, находится [здесь](https://review.openstack.org/#/settings/agreements). Надо написать I AGREE. Придется заполнить почтовый адрес и иже с ним.

Не забыть залить ssh public key [сюда, в настройки](https://review.openstack.org/#/settings/ssh-keys)

Установить git-review (Опционально). Если нет админских прав на машине, можно установить в виртуальное окружение

Если в офисе не работает ssh, то можно настроить работу с гитом по https, процедура описана [здесь](http://docs.openstack.org/infra/manual/developers.html#accessing-gerrit-over-https)
Web-пароль [здесь](https://review.openstack.org/#/settings/http-password)

# Основные ссылки

[How to Contribute](https://wiki.openstack.org/wiki/How_To_Contribute)
[Getting The Code](https://wiki.openstack.org/wiki/Getting_The_Code)
[Настройка аккаунта](http://docs.openstack.org/infra/manual/developers.html#account-setup)
