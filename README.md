# Инструкция по подготовке проекта для react native + тестирование

## Устанавливаем необходимое программное обеспечение:

    - Скачиваем и устанавливаем [git] (https://git-scm.com/downloads) 
    - Скачиваем и устанавливаем текстовый редактор [VisualStudioCode] (https://code.visualstudio.com/) 
    - Скачиваем и устанавливаем [Node.js] (https://nodejs.org/ru)

## Регистрация на необходимых сервисах:

    - Регистрация на [GitHUB] (https://github.com/) 
    - Регистрация на [Expo.DEV] (https://expo.dev/) 

## Пошаговая инструкция настройки проекта: 


### Инструкция работы с порталом Expo.DEV:

    - авторизуемся на сайте [Expo.DEV] (https://expo.dev/) 
    - Переходим на вкладку AllProjects
    - Нажимаем на кнопку `+ Created a Project`
    - Пишем наименование проекта
    - Далее переходим в VisualStudioCode

### Инструкция работы с VisualStudioCode:
    
    - Запускаем VisualStudioCode
    - Создаем папку на локальном диске
    - Указываем путь в VisualStudioCode к созданной папке (File->open folder-> указать путь)
    - Открываем терминал в VisualStudioCode, вкладка (terminal->new terminal), горячие клавиши ctrl+shift+`
    - Прописываем команду `npm install --global eas-cli` (ожидаем установки пакетов)
    - Прописываем команду `npx create-expo-app test` (ожидаем развертывание приложения)
    - Переходим в созданную папку `cd test`
    - Прописываем команду `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser` <br/>
      Данная команда разрешает политики WINDOWS выполнять скрипты без разрешения
    - Прописываем команду `eas init --id *ваш ID проекта*` <br/> 
      вводим логин от Expo.DEV
      вводим пароль от Expo.DEV
    

### Тестирование приложения  

    - для того что бы тестироватать ПО есть несколько способом мы будем использовать web тестирование
    - вводим команду в терминале `npx expo install react-native-web@~0.19.6 react-dom@18.2.0 @expo/webpack-config@^19.0.0`  (Подключение библиотек react-native-web)
    - вводим команду в терминале `npm start` (Запускаем react)
    - 

