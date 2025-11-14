# Самодуров Сергей Михайлович CICD/gitlab

## Задание 1

Что нужно сделать:

Разверните GitLab локально, используя Vagrantfile и инструкцию, описанные в этом репозитории.
Создайте новый проект и пустой репозиторий в нём.
Зарегистрируйте gitlab-runner для этого проекта и запустите его в режиме Docker. Раннер можно регистрировать и запускать на той же виртуальной машине, на которой запущен GitLab.
В качестве ответа в репозиторий шаблона с решением добавьте скриншоты с настройками раннера в проекте.

### Решение 1

ВМ под управлением ОС Debian развернута вручную на виртуализации VirtualBox без применения vagrant
После установки на ВМ с хост-машины gitlab доступен по домену gitlab.cicd-homework

![1](https://github.com/SerhioSamodurov/git_project_hw/blob/main/img/1.png)

После чего создан проект и репозиторий

![2](https://github.com/SerhioSamodurov/git_project_hw/blob/main/img/2.png)

Зарегистрировал docker-runner в gitlab
Контейнер запущен на той же ВМ что и git lab

![3](https://github.com/SerhioSamodurov/git_project_hw/blob/main/img/3.png)

конфиг

![4](https://github.com/SerhioSamodurov/git_project_hw/blob/main/img/4.png)

В web ранер в статусе онлайн

![5](https://github.com/SerhioSamodurov/git_project_hw/blob/main/img/5.png)


## Задание 2

Что нужно сделать:

Запушьте репозиторий на GitLab, изменив origin. Это изучалось на занятии по Git.
Создайте .gitlab-ci.yml, описав в нём все необходимые, на ваш взгляд, этапы.
В качестве ответа в шаблон с решением добавьте:

файл gitlab-ci.yml для своего проекта или вставьте код в соответствующее поле в шаблоне;
скриншоты с успешно собранными сборками.

### Решение 2
