[![Статус тестов](../../actions/workflows/tests.yml/badge.svg)](../../actions/workflows/tests.yml)

# Проект react-mesto-api-full

## Описание

Репозиторий для приложения проекта `Mesto`, включающий фронтенд и бэкенд части приложения.

Функционал: регистрация и авторизация пользователя, редактирование профиля пользователя, добавление и удаление карточек, постановка и снятие лайка карточкам, обработка приходящих на сервер данных, храение данных в базе.

Используемый стек технологий: HTML, CSS, React JS, Rest API, Node JS, Express JS, MongoDB.

Адрес репозитория: https://github.com/morevtrue/react-mesto-api-full-gha

## Ссылки на проект

IP 51.250.81.113

Frontend https://mesto-morevtrue.students.nomoreparties.co

Backend https://api.mestomorev.students.nomoreparties.co

## Развёртывание приложения

Backend: в терминале перейти в директорию `backend`, ввести команду `npm run dev`.

Frontend: в терминале перейти в директорию `frontend`, ввести команду `npm start`.

## Системные требования

GIT v2.33.0
Node JS v16.16.0
ReactJS v5.0.1
MongoDB v4.4.23

## Статус и планы по доработке

Сайт выполняет все необходимые функции, но валидирование данных, которые вводит пользователь, в данный момент реализовано с помощью дефолтной браузерной валидации, что хотелось бы исправить и добавить кастомную валидацию.