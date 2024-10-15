
# Лайнокод: Перевірка високосного року 🎉

Привіт! Я **Ігор**, студент 3 курсу 👨‍🎓, і я люблю програмувати! 💻 Цей проект є частиною конкурсу "Лайнокод" від @Robot_Dreams_platformbot. Мета — створити однорядковий код на мові Go, який перевіряє, чи є заданий рік високосним. 🌟

## Опис

Програма приймає рік як вхідні дані і визначає, чи є цей рік високосним. Високосний рік — це рік, що ділиться на 4, але не ділиться на 100, за винятком років, які діляться на 400. 📅

## Однорядковий код

```go
package main; import ("fmt"; "strconv"); func main() { var year string; fmt.Print("🤖 Введіть рік: "); fmt.Scanln(&year); y, _ := strconv.Atoi(year); result := map[bool]string{true: "🎉 Високосний!", false: "❌ Не високосний."}[y%4 == 0 && (y%100 != 0 || y%400 == 0)]; fmt.Printf("Рік %d є %s 🤔\n", y, result) }

```

## Використання 🚀

1. Скопіюйте однорядковий код.
2. Перейдіть на сайт [Programiz Online Compiler](https://www.programiz.com/golang/online-compiler/).
3. Вставте код у вікно компілятора.
4. Натисніть "Run" для запуску програми. 🖱️
5. Введіть рік, який ви хочете перевірити, і програма виведе `🎉 Високосний`, якщо рік високосний, або `❌ Не високосний`, якщо ні. 🎊

## Приклад роботи

![image](https://github.com/user-attachments/assets/ac917634-2f1a-4cfb-a3c2-17dad64abf3e)
![image](https://github.com/user-attachments/assets/01bc69c9-8717-4018-8d65-b47e989f5098)

## Контриб'ютори

- **Ігор** (ваше ім'я) 😊
