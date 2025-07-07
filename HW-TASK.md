# Домашнее задание к занятию 5 «Тестирование roles»

## Подготовка к выполнению

1. Установите molecule и его драйвера: `pip3 install "molecule molecule_docker molecule_podman`.
2. Выполните `docker pull aragast/netology:latest` —  это образ с podman, tox и несколькими пайтонами (3.7 и 3.9) внутри.

## Основная часть

Ваша цель — настроить тестирование ваших ролей. 

Задача — сделать сценарии тестирования для vector. 

Ожидаемый результат — все сценарии успешно проходят тестирование ролей.

После выполнения у вас должно получится два сценария molecule и один tox.ini файл в репозитории. Не забудьте указать в ответе теги решений Tox и Molecule заданий. В качестве решения пришлите ссылку на  ваш репозиторий и скриншоты этапов выполнения задания. 

### Molecule
[Molecule converge](https://github.com/vladrabbit/vector-role/blob/main/.screenshots/mc-1.png)
[Molecule verify](https://github.com/vladrabbit/vector-role/blob/main/.screenshots/mv-1.png) 


### Tox

[Tox docker test start](https://github.com/vladrabbit/vector-role/blob/main/.screenshots/tox-start.png)
[Tox docker end](https://github.com/vladrabbit/vector-role/blob/main/.screenshots/tox-end.png)


