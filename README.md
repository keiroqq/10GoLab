1)	Хэширование данных:
•	Разработайте утилиту, которая принимает на вход строку и вычисляет её хэш с использованием алгоритма SHA-256.
•	Реализуйте возможность выбора нескольких хэш-функций (например, MD5, SHA-256, SHA-512).
•	Включите в утилиту проверку целостности данных: пользователю предлагается ввести строку и её хэш, после чего утилита должна подтвердить или опровергнуть их соответствие.
2)	Симметричное шифрование:
•	Реализуйте программу, шифрующую переданные данные с помощью алгоритма AES.
•	Пользователь должен указать строку и секретный ключ.
•	Программа должна зашифровать строку и предоставить возможность расшифровать её при вводе того же ключа.
3)	Асимметричное шифрование и цифровая подпись:
•	Создайте пару ключей (открытый и закрытый) и сохраните их в файл.
•	Реализуйте программу, которая подписывает сообщение с помощью закрытого ключа и проверяет подпись с использованием открытого ключа.
•	Продемонстрируйте пример передачи подписанных сообщений между двумя сторонами.
4)	Реализация защищённого канала передачи данных (TLS):
•	Модифицируйте TCP-сервер и клиент из предыдущих лабораторных работ для работы через защищённый канал с использованием TLS.
•	Сервер должен поддерживать установку безопасного соединения, а клиент — проверять сертификат сервера перед отправкой данных.
•	Реализуйте взаимную аутентификацию на уровне сертификатов.
5)	Защита REST API:
•	Добавьте поддержку аутентификации с помощью токенов (например, JWT) для REST API.
•	Реализуйте маршруты, требующие аутентификации, и проверьте их работу с валидными и невалидными токенами.
•	Включите ограничение доступа к ресурсам на основе ролей (admin, user).
6)	Защита от CSRF и управление сессиями:
•	Добавьте защиту от CSRF-атак в ваше REST API.
•	Реализуйте механизм сессий для авторизованных пользователей.
