## rsschool-cv
# Vladislava Zaitseva
## Contacts
* **Phone:** +375(44)5385804
* **Email:** vladislava.zaitseva004@gmail.com
* **Telegram:** [@vlada_328](https://t.me/vlada_328)
* **GitHab:** [Vladislava004](https://github.com/Vladislava004)
## About Me
I am a 2nd-year student at BSUIR (Belarusian State University of Informatics and Radioelectronics). I am goal-oriented, communicative, and responsible. I want to learn something new and develop in various areas of programming - I don't want to stand still. My goal is to become a highly qualified specialist.
## Education
**BSUIR** (Belarusian State University of Informatics and Radioelectronics)\
Faculty of Information Technologies and Management\
Specialty: Automated Information Processing Systems\
2022 - 2026
## Skills
* C++
* C#(Basic)
* HTML, CSS
* MySql
* Git
## Code Example
**Programming language:** C#

```
int number;
int lower, higher;
int triesCount = 5;
int userInput;
Random rand = new Random();
number = rand.Next(0, 101);
lower = rand.Next(number - 10, number);
higher = rand.Next(number + 1, number + 10);
Console.WriteLine($"Мы загадали число от 0 до 100, оно больше чем {lower}, но меньше чем {higher}.");
Console.WriteLine($"Что это за число? У Вас {triesCount} попыток осталось!");

while (triesCount-- > 0)
{
    Console.Write("Ваш ответ: ");
    string userInputString = Console.ReadLine();
    if (int.TryParse(userInputString, out userInput))
    {
        if (userInput == number)
        {
            Console.WriteLine("Вы правы это было число " + number + ".");
            break;
        }
        else
        {
            Console.WriteLine("Неверно! Попробуйте еще раз!");
        }
    }
    else
    {
        Console.WriteLine("Пожалуйста, введите число.");
        triesCount++;
    }
}

if (triesCount < 0)
{
    Console.WriteLine("Увы, вы проиграли, но повезет в другой раз! это было число " + number + ".");
}
```
## Languages
* **Russian** - native speaker
* **English** - B1