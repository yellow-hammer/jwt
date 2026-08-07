# Изменения

Формат основан на [Keep a Changelog](https://keepachangelog.com/ru/1.0.0/),
версионирование - [semver](https://semver.org/lang/ru/).

## 0.1.0 - 2026-08-07

### Добавлено

- Первая версия: JSON Web Token по RFC 7519 для OneScript
- Модуль `JWT`: подпись и проверка HS256/HS384/HS512, разбор, проверка утверждений
- Классы `JwtVerificationResult` и `HmacRfc2104`: результат без исключений, HMAC по RFC 2104
- Проверка асимметрично подписанных токенов через внешний проверяющий
