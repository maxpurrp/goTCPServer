#   Golang TCP Сервер с Многопоточностью

## Обзор
Это простая реализация TCP-сервера на языке программирования Golang, который работает с использованием многопоточности (горутин). Сервер предназначен для обработки нескольких клиентских подключений одновременно, что обеспечивает эффективное взаимодействие с несколькими клиентами параллельно.

## Установка
1. Убедитесь, что на вашей системе установлен Go.
2. Для клонирования репозитория на ваш компьютер выполните команду ```https://github.com/maxpurrp/goTCPServer```

## Запуск
Запустите сервер с помощью следующей команды:
```go run .\serv\main.go```
Запустите клиент, который отправит 5 раз запрос к серверу с паузой между запросами 1 секунда :
```go run .\client\main.go```


**Примечание:** Это базовый шаблон, и вам может потребоваться доработать его в соответствии с вашими конкретными требованиями и сценарием использования.
