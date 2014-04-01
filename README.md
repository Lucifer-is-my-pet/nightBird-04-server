Клиент-серверная реализация игрового мира
===================
Реализовать взаимодействие мира и игрового бота по сети. При этом мир выступает в роли
сервера, а игровой бот в роли клиента. С сервером взаимодействует только
один клиент.

В качестве сервера используйте вашу реализацию интерфейса ```Wood``` из предыдущих заданий.
Для реализации клиента можно использовать актуатор. Он должен устанавливать
соединение с сервером, создавать экземпляр класса Мышь (реализация интерфейса ```Mouse```), после чего
на каждый ```Direction``` от игрового бота делать запрос на сервер для получения ```Action```.
