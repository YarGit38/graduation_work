# graduation_work - выпускной проект по сетям.

Реализуйте текстовый протокол общения между клиентом и сервером, в рамках которого они будут обмениваться сообщениями.

Сообщение будет представлять из себя 2 строки:
1. Первая строка будет техническим заголовком. В нем будет передаваться размер второй строки.
2. Вторая строка будет содержать команду. Команда будет простым текстом из одного слова.

Пример:

5

hello

Клиент должен сначала 2 раза отправить корректные сообщения с текстом hello в первом сообщении и cool во втором.
На каждое корректное сообщение сервер должен ответить сообщением ok.

В третьем сообщении клиент должен отправить сообщение с указанием некорректной длины для текста haha.
Сервер должен вернуть сообщение об ошибке err.

Используем netty.
