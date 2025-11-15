# Самодуров Сергей Михайлович CICD/gitlab

## Задание 1

Что нужно сделать:

Разверните GitLab локально, используя Vagrantfile и инструкцию, описанные в этом репозитории.
Создайте новый проект и пустой репозиторий в нём.
Зарегистрируйте gitlab-runner для этого проекта и запустите его в режиме Docker. Раннер можно регистрировать и запускать на той же виртуальной машине, на которой запущен GitLab.
В качестве ответа в репозиторий шаблона с решением добавьте скриншоты с настройками раннера в проекте.

### Решение 1

Развернул ВМ под управлениеи ОС Debian на виртуализации VirtualBox.
Первоначально установил docker, sonar, postgresql  и подняты контейнеры

![1](https://github.com/SerhioSamodurov/git_project_hw/blob/main/img/1.png)

Установил gitlab, который доступен под доменному gitlab.cicd-homework имени с хост-машины (пока создал пустой проект для создания runner в рамках задачи)

![2](https://github.com/SerhioSamodurov/git_project_hw/blob/main/img/2.png)

Зарегистрировал runner

![3](https://github.com/SerhioSamodurov/git_project_hw/blob/main/img/3.png)

Изменил config.

![4](https://github.com/SerhioSamodurov/git_project_hw/blob/main/img/4.png)

Запустил runner

![5](https://github.com/SerhioSamodurov/git_project_hw/blob/main/img/5.png)



## Задание 2

Что нужно сделать:

Запушьте репозиторий на GitLab, изменив origin. Это изучалось на занятии по Git.
Создайте .gitlab-ci.yml, описав в нём все необходимые, на ваш взгляд, этапы.
В качестве ответа в шаблон с решением добавьте:

файл gitlab-ci.yml для своего проекта или вставьте код в соответствующее поле в шаблоне;
скриншоты с успешно собранными сборками.

### Решение 2

Склонировал репозиторий и запушил его в локальный gitlab

![6](https://github.com/SerhioSamodurov/git_project_hw/blob/main/img/6.png)

Создан .gitlab-ci.yml и добавлен в репозиторй

![7](https://github.com/SerhioSamodurov/git_project_hw/blob/main/img/7.png)

После push runner отработал корректно

![8](https://github.com/SerhioSamodurov/git_project_hw/blob/main/img/8.png)

В sonar так же поодтягивается информация

![9](https://github.com/SerhioSamodurov/git_project_hw/blob/main/img/9.png)

