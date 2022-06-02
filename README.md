# homeassistant-openweathermap

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://github.com/custom-components/hacs)

Вариант штатной интеграции [OpenWeatherMap для Home Assistant](https://www.home-assistant.io/integrations/openweathermap/) для тех пользователей, у кого штатная интеграция не работает из-за таймаута при запросах к OpenWeatherMap API по HTTPS (но при этом работает по HTTP!).

## Установка

Нужно удалить штатную интеграцию OpenWeatherMap из ХА, затем установить эту, одним из способов ниже на выбор. 
Затем нужно перезагрузить ХА и снова установить интеграцию (она увидится под новым именем OpenWeatherMapCustom). Настройки в ней те же, что и в оригинальном варианте - но выставлены по умолчанию русский язык и метод onecall_hourly (потому что мне так удобно :) )

**Способ первый.** Кастомный репозиторий [HACS](https://hacs.xyz/):

> HACS > Интеграции > 3 точки слева вверху > Пользовательские репозитории > Репозиторий: `ANS-spb/homeassistant-openweathermap`, Категория: Интеграции > Добавить > *чуть-чуть подождём* > homeassistant-openweathermap > Установить

**Способ второй.** Вручную закинуть каталог `openweathermap` в Ваш каталог `/config/custom_components`.
