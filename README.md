# Yandex-test-case for Linux-embedded developers C/C++
Есть устройство с Linux в качестве ОС. Данное устройство имеет Ethernet и несколько интерфейсов CAN. Необходимо разработать скрипт или программу, позволяющую использовать данное устройство как конвертер UDP-to-CAN, где каждому CAN-устройству соответствует определенный приемный UDP-порт, данные с которого передаются в соответствующий CAN, и наоборот, данные, пришедшие из CAN, передаются на другой, заранее определенный UDP-порт по заранее определенному IP-адресу. В качестве API работы с CAN рекомендуется использовать SocketCAN.
