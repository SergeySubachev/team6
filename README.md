## Стартовый репозиторий для TheGame

Это APS.NET Core приложение с React кодом на фронтенде.


### Для локального запуска проекта для удобной разработки фронта

1. Перейди в директорию src
2. Выполнить `npm i`
3. Выполнить `dotnet build`
4. После успешного окончания билда, выполнить `dotnet run --environment Development`
5. Редактировать фронт в директории `ClientApp`

Это запустит веб-сервер в режиме разработки с горячей заменой фронтенд-кода, чтобы можно было сразу видеть результат 
после редактирования js-кода.

Можно запускать приложение из IDE, но в этом случае может не работать механизм горячей замены фронтенд-кода. 
