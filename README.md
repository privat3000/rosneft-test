# rosneft-test
Здравствуйте Александр, работа не закончена по причине невозможности подключения бд к приложению.
Началась работа хорошо: была составлена база данных и выбраны сами данные.(все сделано запросами)(IDE MS SQL Server).
Следующим шагом стало написание запросов по выборке данных (были определенные сложности, но в целом справился с задачей).
Дальше я приступил к изучению QT (IDE сначала Clion, но так как было много ошибок файла cmake, прешел на QT Creator), и вот тут пошли проблемы. После долгого изучения того, как можно подключить готовую бд к коду, наткнулся на форум, где рассказывалось что без специальных дров (ODBC) подключение невозможно. Я скачал 5 разных версий этих драйверов, они указали на отсутвие другого драйвера который надо скачать через PowerShell. После того как все было подготовлено ODBC начал выдавать ошибку невозможности подключиться к серверу. Долго поизучав как правильно надо ставить ODBC, я смог его уговорить подключиться и установиться. 
Подключая бд к QT было встречено много ошибок, но я их тоже обошел. И когда я уже написал код для получения первого select, QT сказал что он снова не может подключиться к серверу с бд. Эту ошибку я победить так и не смог. Все скриншоты прилагаются.
На использование варианта работы с другой IDE для создания приложения мне к сожалению не хватило времени, но я думаю проблема не в IDE, а в работе с бд.
