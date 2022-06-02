# homeassistant-openweathermap

Вариант штатной интеграции OpenWeatherMap для Home Assistant (https://www.home-assistant.io/integrations/openweathermap/) для тех пользователей, у кого штатная интеграция не работает из-за таймаута при запросах к OpenWeatherMap API по HTTPS (но при этом работает по HTTP!).

Нужно удалить штатную интеграцию OpenWeatherMap из ХА, затем закинуть каталог *openweathermap* в Ваш каталог *custom_components*, перезагрузить ХА и снова установить интеграцию (она увидится под новым именем OpenWeatherMapCustom). Настройки в ней те же, что и в оригинальном варианте - но выставлены по умолчанию русский язык и метод onecall_hourly (потому что мне так удобно :) )
