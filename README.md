# Лабораторной работе №3 " Анализ защищенности с использованием Kali Linux и Damn Vulnerable Linux (DVL)"

# Задание 1. Начальная настройка

 Устанавливаем Kali и DVL. Определим IP на DVL

  ![Desktop Screenshot 2023 12 31 - 02 46 20 73](https://github.com/hipster-x/Lab-3/assets/145153023/20a80989-e076-4b5f-a2b7-1ef0acfaafb5)

# Задание 2. Сканирование Сети и Уязвимостей

 1. Nmap
 
  ![Desktop Screenshot 2023 12 31 - 02 46 20 73](https://github.com/hipster-x/Lab-3/assets/145153023/f6b493ce-4b79-4a3d-bb09-bbec788ec798)

 2. OpenVas

 ![Desktop Screenshot 2023 12 29 - 12 36 54 65](https://github.com/hipster-x/Lab-3/assets/145153023/b5766689-5d6f-4f0d-9e2f-3547896df275)

 ![image](https://github.com/hipster-x/Lab-3/assets/145153023/f68be28e-4238-43cf-9a61-9cd413875bd4)

 ![image](https://github.com/hipster-x/Lab-3/assets/145153023/d89d152a-2549-43f8-b674-dcb5b11c0480)

 # Задание 3. Пентестинг Веб-Приложений
 1. XSS 

 ![Desktop Screenshot 2023 12 31 - 02 52 05 44](https://github.com/hipster-x/Lab-3/assets/145153023/90248db5-8ae5-46de-9fbe-e9c73edc462a)

 Перехватываем и меняем запрос

  ![Desktop Screenshot 2023 12 31 - 02 54 11 44](https://github.com/hipster-x/Lab-3/assets/145153023/39da88f6-2cb7-40b7-b906-d1ec8032d44a)

 Выполняем 

 ![Desktop Screenshot 2023 12 31 - 03 13 29 97](https://github.com/hipster-x/Lab-3/assets/145153023/69958f2d-0bf8-4f90-ae8c-b42c7d2086bb)

 2. CSRF

 ![Desktop Screenshot 2023 12 31 - 03 14 37 37](https://github.com/hipster-x/Lab-3/assets/145153023/e80d7375-40e5-415d-8293-732957bce460)

 Перехватываем и меняем запрос
 
  ![Desktop Screenshot 2023 12 31 - 03 15 50 42](https://github.com/hipster-x/Lab-3/assets/145153023/89a9ac6c-558a-486a-8d5c-a51c07950f13)

  Выполняем 

 ![Desktop Screenshot 2023 12 31 - 03 16 29 77](https://github.com/hipster-x/Lab-3/assets/145153023/fc01fc50-13ac-4275-8b40-b00e545eddf7)

 3. OWASP ZAP

 ![Desktop Screenshot 2023 12 31 - 03 24 00 38](https://github.com/hipster-x/Lab-3/assets/145153023/2fe369ee-dd7e-4249-983c-4eddaa87d6a0)

  Просканируем, посмотрим на результат SQL injection

   ![Desktop Screenshot 2023 12 31 - 03 55 23 70](https://github.com/hipster-x/Lab-3/assets/145153023/913955da-b830-49f2-8c7d-0e6702350ce7)

 # 4. Анализ Безопасности Системы

  1. Metasploit
 Задаем параметры

  ![image](https://github.com/hipster-x/Lab-3/assets/145153023/50b6df68-93d2-4808-aec7-6166b76bdb64)


 Получаем пароль root пользователя

 ![image](https://github.com/hipster-x/Lab-3/assets/145153023/5b1429b0-281a-47a9-8d54-b8bc2b2510e6)


  2. JohnTheRipper
 
 Ищем пароль с помощью JohnTheRippe

 ![293508285-3c459940-c996-400d-8384-4819fb2c4633 (1)1](https://github.com/hipster-x/Lab-3/assets/145153023/7b45ee45-a505-4710-82ac-08d79ade3cf6)

![293508285-3c459940-c996-400d-8384-4819fb2c46331](https://github.com/hipster-x/Lab-3/assets/145153023/b8764980-87ca-4d17-8863-6d4dc582b9b3)

# Задание 5. Сетевая Защита и Защита От Вторжений

 1. Wireshark

 ![image](https://github.com/hipster-x/Lab-3/assets/145153023/feb29426-8089-4e86-a05e-7f175f15afa1)

 2. Snort

 ![image](https://github.com/hipster-x/Lab-3/assets/145153023/f5634d39-2e9f-4e27-816f-46ebf3608acd)



