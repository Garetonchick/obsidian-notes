Команды требуют **sudo**.
### База
- docker build -t image-name .
Создать image с именем image-name
- docker run -dp localhost:4444:6666 image-name
Запустить контейнер из слепка image-name как 
демон и установить связь между локальным поротом 4444 и 
внутриконтейнерным 6666.
-i интерактивный режим(открытый stdin)
-t эмулятор tty(консоли)
- docker ps или docker container ls
Почекать текущие запущенные контейнеры
- docker image ls
Почекать имеющиеся image-ы
- docker prune --all --force --volumes 
Почистить все
- docker volume create volume-name
Создать новый volume с именем volume-name
- docker volume ls
Почекать имеющиеся volume-ы