# Перевод книги [The Complete Redux Book](https://leanpub.com/redux-book) от [Ilya Gelman](https://leanpub.com/u/ilyagelman) и [Boris Dinkevich](https://leanpub.com/u/borisdinkevich)

Перевод книги от 31-01-2017. Переведено и опубликовано с разрешения правообладателей.

## <a name="table-of-contents">Оглавление</a>
* [Часть 1. Введение в Redux](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-1.md#%D0%A7%D0%B0%D1%81%D1%82%D1%8C-1-%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B2-redux)
    * [Глава 1. Основные понятия Flux и Redux](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-1.md#%D0%93%D0%BB%D0%B0%D0%B2%D0%B0-1-%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%BD%D1%8B%D0%B5-%D0%BF%D0%BE%D0%BD%D1%8F%D1%82%D0%B8%D1%8F-flux-%D0%B8-redux)
        * [Что такое Flux?](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-1.md#%D0%A7%D1%82%D0%BE-%D1%82%D0%B0%D0%BA%D0%BE%D0%B5-flux)
        * [Redux и Flux](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-1.md#redux-%D0%B8-flux)
        * [Redux Терминология](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-1.md#redux-%D0%A2%D0%B5%D1%80%D0%BC%D0%B8%D0%BD%D0%BE%D0%BB%D0%BE%D0%B3%D0%B8%D1%8F)
        * [Общие понятия](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-1.md#%D0%9E%D0%B1%D1%89%D0%B8%D0%B5-%D0%BF%D0%BE%D0%BD%D1%8F%D1%82%D0%B8%D1%8F)
        * [Redux и React](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-1.md#redux-%D0%B8-react)
        * [Основная реализация Redux](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-1.md#%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%BD%D0%B0%D1%8F-%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F-redux)
        * [Подведем итоги](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-1.md#%D0%9F%D0%BE%D0%B4%D0%B2%D0%B5%D0%B4%D0%B5%D0%BC-%D0%B8%D1%82%D0%BE%D0%B3%D0%B8)
    * [Глава 2. Ваше первое Redux приложение](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-2.md#%D0%93%D0%BB%D0%B0%D0%B2%D0%B0-2-%D0%92%D0%B0%D1%88%D0%B5-%D0%BF%D0%B5%D1%80%D0%B2%D0%BE%D0%B5-redux-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5) 
        * [Стартовый проект](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-2.md#%D0%A1%D1%82%D0%B0%D1%80%D1%82%D0%BE%D0%B2%D1%8B%D0%B9-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82)
        * [Наше первое приложение](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-2.md#%D0%9D%D0%B0%D1%88%D0%B5-%D0%BF%D0%B5%D1%80%D0%B2%D0%BE%D0%B5-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5)
        * [Настройка Store](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-2.md#%D0%9D%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D0%B0-store)
        * [Добавление рецептов](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-2.md#%D0%94%D0%BE%D0%B1%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D1%80%D0%B5%D1%86%D0%B5%D0%BF%D1%82%D0%BE%D0%B2)
        * [Добавление ингредиентов](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-2.md#%D0%94%D0%BE%D0%B1%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B8%D0%BD%D0%B3%D1%80%D0%B5%D0%B4%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2)
        * [Структурирование кода](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-2.md#%D0%A1%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BA%D0%BE%D0%B4%D0%B0)
        * [Подробней о Reducer](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-2.md#%D0%9F%D0%BE%D0%B4%D1%80%D0%BE%D0%B1%D0%BD%D0%B5%D0%B9-%D0%BE-reducer)
        * [Обработка опечаток и дубликатов](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-2.md#%D0%9E%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0-%D0%BE%D0%BF%D0%B5%D1%87%D0%B0%D1%82%D0%BE%D0%BA-%D0%B8-%D0%B4%D1%83%D0%B1%D0%BB%D0%B8%D0%BA%D0%B0%D1%82%D0%BE%D0%B2)
        * [Простой пользовательский интерфейс](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-2.md#%D0%9F%D1%80%D0%BE%D1%81%D1%82%D0%BE%D0%B9-%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8C%D1%81%D0%BA%D0%B8%D0%B9-%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D1%84%D0%B5%D0%B9%D1%81)
        * [Логирование](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-2.md#%D0%9B%D0%BE%D0%B3%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5)
        * [Получение данных с сервера](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-2.md#%D0%9F%D0%BE%D0%BB%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85-%D1%81-%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80%D0%B0)
        * [Подведем итоги](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-1/charapter-2.md#%D0%9F%D0%BE%D0%B4%D0%B2%D0%B5%D0%B4%D0%B5%D0%BC-%D0%B8%D1%82%D0%BE%D0%B3%D0%B8)
* [Часть 2. Использование в реальном мире](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-3.md#%D0%98%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%B2-%D1%80%D0%B5%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D0%BC-%D0%BC%D0%B8%D1%80%D0%B5)       
    * [Глава 3. Управление состоянием](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-3.md#%D0%93%D0%BB%D0%B0%D0%B2%D0%B0-3-%D0%A3%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D1%81%D0%BE%D1%81%D1%82%D0%BE%D1%8F%D0%BD%D0%B8%D0%B5%D0%BC)
        * [Общее представление разделения](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-3.md#%D0%9E%D0%B1%D1%89%D0%B5%D0%B5-%D0%BF%D1%80%D0%B5%D0%B4%D1%81%D1%82%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5-%D1%80%D0%B0%D0%B7%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F)
        * [Состояние как база данных](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-3.md#%D0%A1%D0%BE%D1%81%D1%82%D0%BE%D1%8F%D0%BD%D0%B8%D0%B5-%D0%BA%D0%B0%D0%BA-%D0%B1%D0%B0%D0%B7%D0%B0-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85)
        * [Хранение нормализованного состояния](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-3.md#%D0%A5%D1%80%D0%B0%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BD%D0%BE%D1%80%D0%BC%D0%B0%D0%BB%D0%B8%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D0%BE%D0%B3%D0%BE-%D1%81%D0%BE%D1%81%D1%82%D0%BE%D1%8F%D0%BD%D0%B8%D1%8F)
        * [Сохранение состояния](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-3.md#%D0%A1%D0%BE%D1%85%D1%80%D0%B0%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5-%D1%81%D0%BE%D1%81%D1%82%D0%BE%D1%8F%D0%BD%D0%B8%D1%8F)
        * [Состояние в реальном проекте](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-3.md#%D0%A1%D0%BE%D1%81%D1%82%D0%BE%D1%8F%D0%BD%D0%B8%D0%B5-%D0%B2-%D1%80%D0%B5%D0%B0%D0%BB%D1%8C%D0%BD%D0%BE%D0%BC-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B5)
        * [Подведем итоги](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-3.md#%D0%9F%D0%BE%D0%B4%D0%B2%D0%B5%D0%B4%D0%B5%D0%BC-%D0%B8%D1%82%D0%BE%D0%B3%D0%B8)
    * [Глава 4. Взаимодействие с сервером](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-4.md#%D0%93%D0%BB%D0%B0%D0%B2%D0%B0-4-%D0%92%D0%B7%D0%B0%D0%B8%D0%BC%D0%BE%D0%B4%D0%B5%D0%B9%D1%81%D1%82%D0%B2%D0%B8%D0%B5-%D1%81-%D1%81%D0%B5%D1%80%D0%B2%D0%B5%D1%80%D0%BE%D0%BC)
        * [Использование обещаний (promise) в Action Creators](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-4.md#%D0%98%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BE%D0%B1%D0%B5%D1%89%D0%B0%D0%BD%D0%B8%D0%B9-promise-%D0%B2-action-creators)
        * [API Middleware](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-4.md#api-middleware)
        * [Перемещение кода из Action Creator](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-4.md#%D0%9F%D0%B5%D1%80%D0%B5%D0%BC%D0%B5%D1%89%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BA%D0%BE%D0%B4%D0%B0-%D0%B8%D0%B7-action-creator)
        * [Использование API Middleware](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-4.md#%D0%98%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-api-middleware)
        * [Обработка ошибок](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-4.md#%D0%9E%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B0-%D0%BE%D1%88%D0%B8%D0%B1%D0%BE%D0%BA)
        * [Индикатор загрузки](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-4.md#%D0%98%D0%BD%D0%B4%D0%B8%D0%BA%D0%B0%D1%82%D0%BE%D1%80-%D0%B7%D0%B0%D0%B3%D1%80%D1%83%D0%B7%D0%BA%D0%B8)
        * [Динамические типы объекта action](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-4.md#%D0%94%D0%B8%D0%BD%D0%B0%D0%BC%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5-%D1%82%D0%B8%D0%BF%D1%8B-%D0%BE%D0%B1%D1%8A%D0%B5%D0%BA%D1%82%D0%B0-action)
        * [Аутентификация](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-4.md#%D0%90%D1%83%D1%82%D0%B5%D0%BD%D1%82%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F)
        * [Дополнительные расширения](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-4.md#%D0%94%D0%BE%D0%BF%D0%BE%D0%BB%D0%BD%D0%B8%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5-%D1%80%D0%B0%D1%81%D1%88%D0%B8%D1%80%D0%B5%D0%BD%D0%B8%D1%8F)
        * [Связывания API](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-4.md#%D0%A1%D0%B2%D1%8F%D0%B7%D1%8B%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-api)
        * [Отмена API запросов](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-4.md#%D0%9E%D1%82%D0%BC%D0%B5%D0%BD%D0%B0-api-%D0%B7%D0%B0%D0%BF%D1%80%D0%BE%D1%81%D0%BE%D0%B2)
        * [Подведем итоги](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-4.md#%D0%9F%D0%BE%D0%B4%D0%B2%D0%B5%D0%B4%D0%B5%D0%BC-%D0%B8%D1%82%D0%BE%D0%B3%D0%B8)
    * [Глава 5. WebSockets](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-5.md#%D0%93%D0%BB%D0%B0%D0%B2%D0%B0-5-websockets)
        * [Основная архитектура](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-5.md#%D0%9E%D1%81%D0%BD%D0%BE%D0%B2%D0%BD%D0%B0%D1%8F-%D0%B0%D1%80%D1%85%D0%B8%D1%82%D0%B5%D0%BA%D1%82%D1%83%D1%80%D0%B0)
        * [Redux Link](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-5.md#redux-link)
        * [Реализация кода](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-5.md#%D0%A0%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F-%D0%BA%D0%BE%D0%B4%D0%B0)
        * [Полный код middleware для работы с WebSocket](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-5.md#%D0%9F%D0%BE%D0%BB%D0%BD%D1%8B%D0%B9-%D0%BA%D0%BE%D0%B4-middleware-%D0%B4%D0%BB%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B-%D1%81-websocket)
        * [Аутентификация](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-5.md#%D0%90%D1%83%D1%82%D0%B5%D0%BD%D1%82%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D1%8F)
        * [Пример потока](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-5.md#%D0%9F%D1%80%D0%B8%D0%BC%D0%B5%D1%80-%D0%BF%D0%BE%D1%82%D0%BE%D0%BA%D0%B0)
        * [Примечание](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-5.md#%D0%9F%D1%80%D0%B8%D0%BC%D0%B5%D1%87%D0%B0%D0%BD%D0%B8%D0%B5)
        * [Подведем итоги](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-5.md#%D0%9F%D0%BE%D0%B4%D0%B2%D0%B5%D0%B4%D0%B5%D0%BC-%D0%B8%D1%82%D0%BE%D0%B3%D0%B8)
    * [Глава 6. Тесты](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-6.md#%D0%93%D0%BB%D0%B0%D0%B2%D0%B0-6-%D0%A2%D0%B5%D1%81%D1%82%D1%8B)
        * [Тестовые файлы и каталоги](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-6.md#%D0%A2%D0%B5%D1%81%D1%82%D0%BE%D0%B2%D1%8B%D0%B5-%D1%84%D0%B0%D0%B9%D0%BB%D1%8B-%D0%B8-%D0%BA%D0%B0%D1%82%D0%B0%D0%BB%D0%BE%D0%B3%D0%B8)
        * [Тестирование Action Creators](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-6.md#%D0%A2%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5-action-creators)
        * [Async Action Creators](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-6.md#async-action-creators)
        * [Тесты для Reducer](https://github.com/Zveroboev/The-Complete-Redux-Book/blob/master/source/part-2/charapter-6.md#%D0%A2%D0%B5%D1%81%D1%82%D1%8B-%D0%B4%D0%BB%D1%8F-reducer)
