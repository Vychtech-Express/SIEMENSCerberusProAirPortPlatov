# SIEMESCerberusProAirPortPlatov
Аэропорт Платов (г. Ростов-на-Дону). Охранно-пожарная сигнализация и сопряжение со смежными системами

Топологии шлейфов прочитана тестом SIEMENS FDUL-221, сохранены файлами *.topo и *.fsm, которые импортируются в конфигурацию панелей

#### Версия конфигуратора
![Версия конфигуратора v7](https://user-images.githubusercontent.com/104857185/171525162-72eb48be-15e4-4c6d-ac9c-ce2f8240eb65.png)

#### Конфигурация панелей
![Конфигурация менеджера резервирования](https://user-images.githubusercontent.com/104857185/171525249-2db858d7-f589-4326-ac07-526b7c310047.png)
![1](https://user-images.githubusercontent.com/104857185/171525293-ff6c1944-f453-46c9-8135-0f50cebe9ab8.png)
![3](https://user-images.githubusercontent.com/104857185/171525310-5f4ef3a8-eb84-4ca2-a42b-d7ca6e76a9bf.png)
![Группа управления заслонками](https://user-images.githubusercontent.com/104857185/171526247-ae2a4aa9-9189-4a3d-ba56-85affad445b2.png)

#### Настройки BACNet в конфигурации панелей
![Настройки BACnet-а](https://user-images.githubusercontent.com/104857185/171527158-d695c786-c6e3-4a49-b350-0ff6da8ba989.png)

#### Windows Server для SCADA-системы
![Диспетчер устройств](https://user-images.githubusercontent.com/104857185/171526373-eed9d334-f64c-4b5f-ab3b-f1feb8cd6412.png)

Конфигурация панелей *.fsc конвертируется в файл импорта *.xml, который импортируется в компосере ММ-ки

#### SCADA-система DMS8000
![MM+MK](https://user-images.githubusercontent.com/104857185/171525499-a3278fcf-fb39-4e1b-a6b8-f7b289a14b10.png)
![Подвал в ММ-ке](https://user-images.githubusercontent.com/104857185/171527323-d6fdb3ca-ccec-46cb-a146-a64696c014eb.png)
![Этаж 1 в ММ-ке](https://user-images.githubusercontent.com/104857185/171527894-937f4d0d-e36a-41fb-b457-ce2efbee9d56.png)
![Этаж 2 в ММ-ке](https://user-images.githubusercontent.com/104857185/171527961-769292a5-4804-42f7-9c72-1b333ba7edcd.png)
![Этаж 3 в ММ-ке](https://user-images.githubusercontent.com/104857185/171527991-0c364215-1969-4333-9085-787807a2cfe8.png)

#### Слои и глубины детализации
![Глубины детализации](https://user-images.githubusercontent.com/104857185/171526209-145333c4-177f-4cce-97b2-4e32c4d62958.png)
![Слои](https://user-images.githubusercontent.com/104857185/171527544-2f4c6495-7bc8-4f17-9162-2cc2723395e5.png)

#### OPC-сервер
![OPC драйвер](https://user-images.githubusercontent.com/104857185/171525614-aae18637-d6c3-4b14-a0b5-547428b24893.png)
![OPC драйвер 2](https://user-images.githubusercontent.com/104857185/171525633-8deb3b02-fbab-4eeb-a28d-2b16d6a92496.png)
![Соединение с внешним OPC-сервером](https://user-images.githubusercontent.com/104857185/171527615-e4566a08-312d-4e56-807f-54f19dcc5697.png)

#### Клиент MK
![MK8000 Client](https://user-images.githubusercontent.com/104857185/171525699-70dd4093-ad7b-4778-a54d-3fe7fe815f48.png)
![Аспирация в клиенте OPC-сервера](https://user-images.githubusercontent.com/104857185/171525881-a5a5b59e-f393-4164-ba95-6b0070910e5f.png)
![Тестовый шлейф ITRIUM](https://user-images.githubusercontent.com/104857185/171527661-50b35c61-f339-4ac5-afd2-d3ba75a9daa0.png)

#### Порты OPC-сервера
![Входящие соединения на OPC-сервер](https://user-images.githubusercontent.com/104857185/171526115-e3d40d05-596e-418c-b919-25150b979fcf.png)

#### Перенастройка на внешний MS SQL Server
![Перенастройка на внешний SQL Server](https://user-images.githubusercontent.com/104857185/171527277-9038178c-d2d0-465c-a315-c314b747b55d.png)

#### Проверка лицензии и USB-вого ключа ММ-ки
![Проверка ограничений ключа](https://user-images.githubusercontent.com/104857185/171527458-faa0e3e0-9575-4e05-9c72-a36ed3267bd7.png)

#### Базы данных ММ-ки на внешнем MS SQL Server-е
![Базы данных ММ-ки](https://user-images.githubusercontent.com/104857185/171526034-bb69d479-af0b-4dd4-a317-e9b0cec51f64.png)

#### Учетки на сервере
![Локальные пользователи](https://user-images.githubusercontent.com/104857185/171527013-4f32d017-edd6-4975-b01b-e665e1dd5c26.png)
![Добавил права учетке DMS8000_PROC](https://user-images.githubusercontent.com/104857185/171526553-d64ef7a8-145e-4c1f-9466-e33b3a13e239.png)
![Свойства Admin_MM8000](https://user-images.githubusercontent.com/104857185/171527510-11d34f29-ffd1-46b1-baf6-3c8cc43c644d.png)

#### Учетки в ММ-ке
![Учетки в ММ-ке](https://user-images.githubusercontent.com/104857185/171527792-57009abf-45a4-4eb1-a1c4-ed5c4171ac4f.png)

#### Драйверы СУБД, системные DSN-ы
![Добавление системного источника данных ODBC на Windows 7](https://user-images.githubusercontent.com/104857185/171526766-8f545e4b-c0c1-4e04-873a-2746b150339d.png)
![Добавление системного источника данных ODBC на Windows 2000](https://user-images.githubusercontent.com/104857185/171526805-16ff162e-f644-40cb-b22e-e49e74b0371e.png)

#### Статические маршруты между панелями и ММ-кой
![Добавление статического маршрута](https://user-images.githubusercontent.com/104857185/171526915-90cd45ed-5eba-44d7-8776-f6f80ea67c9d.png)
