# Тест B2G

Test-B2G - это веб-приложение для рисования и управления полигонами. Пользователи могут добавлять точки, рисовать полигоны и проверять, находятся ли точки внутри или снаружи полигона. Приложение разработано на ASP.NET Core 7 и контейнеризовано с использованием Docker.

## Развёртывание приложения через Docker

### Шаг 1: Получите Docker-образ

Используйте команду Docker для загрузки образа приложения из Docker Hub:

```
docker pull timbildingg/test-b2g:v2 
```
### Шаг 2:
Используйте команду Docker для запуска образа приложения на локальном сервере.
```
docker run -d -p 8080:80 timbildingg/test-b2g:v2
```
### Шаг 3:
Откройте браузер и в поисковой строке введите:
```
localhost:8080
```
### Шаг 4: 
Перейдите на вкладку "Полигон" и выполните инструкцию на экране.

## Развёртывание приложения через GitHub:

### Шаг 1:
Устанавливаем [Git](https://git-scm.com/), если ранее он не был установлен.

### Шаг 2:
Открываем командную строку, выбираем папку (команда `cd "путь_к_папке"`) и при помощи команды `git clone https://github.com/timbilding/Test-B2G` копируем репозиторий в выбранную папку.

### Шаг 3: 
Запускаем приложение при помощи Visual Studio.
