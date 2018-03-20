# Чеклист для проверки при запуске проекта

## Интеграции:

* Регистрация аккаунтов на thirdparty@4xxi.com
* Papertrail / алерты
* Добавить в Google Webmaster Tools
* Скормить sitemap Google/Yandex/Bing

## Код
* Иконки
    * favicon
    * apple-touch-icon
* Теги
    * title + og:title
    * description/keywords
    * og-тэги
    * тэги для мобильных приложений
    * тэги соц.сетей
* Semantic/hackable urls
* Аналитика (Google Analytics / Google Tag Manager)
* sitemap.xml
* token в parameters.yml.dist / env
* Страницы ошибок (кастомизация/редиректы)
* Версионирование ассетов
* Размер изображений и их "нарезка"
* Pagespeed (например, https://www.webpagetest.org/)
* Минификация css/js

## Dev Ops
* https (редиректы с http)
* www (редирект на основной домен)
* Настройка регулярных бэкапов
* Настройка постоянного мониторинга
* Интеграция по ошибкам со Slack/Telegram
* Закрытие/доступ к dev-сайтам извне или без VPN
* Настройка CD

## Прочие проверки
* Отправка email’ов
* Доступы к админке
* Ссылки на соцсети
* Чистая установка
* _Behat тесты + CI_
* _Docker (?)_
