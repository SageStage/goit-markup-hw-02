# goit-markup-hw-02
> # Уточнить у ментора:

1. Файл portfolio.html має бути на одному рівні з файлом index.html.
**Но призагрузке на гитхаб выдает ошибку по файлу портфлолио 404. Был опыт создания сайта. В тз было - в корневом каталоге только один файл html, тк сервер на апачи, несколько html  файлов в корневом каталоге не индексируются.**

7. Глобально на заколовки не додаються стилі шрифта, коліра, бо малоймовірно, що вони будуть однакові на всьому сайті. Глобально зазвичай прибираємо тільки відступи, які йдуть по дефолту.
> ***Это имеется ввиду в стилях для тегов, типа <h2> -> h2 {font-size:..., color: ...}?***
8. Щоб не дублювати одні і ті самі стилі, можна зробити спільний клас і додавати його там, де мають бути ті стилі. Як наприклад, з заголовками. Ще  одразу передивись, щоб не дублювались стилі. Наприклад, на заголовки не треба додавати font-width: 700, на абзаци font-width: 400 , вони йдуть по дефолту від браузера.  
> **Т.е. если *абсолютно одинаковый* стиль для заголовка второго уровня прописать <h2 class="style-h2">, и уже в CSS задавать .style-h2{font-size:..., color: ...}?**

Выполнено:
2. Нема заголовка h1 на сторінці Портфоліо.  Кнопки фільтра також мають знаходитись всередині секції, бо вони пов'язані з картками.
3. Із прихованими заголовками це в тебе ьимчасове рішення, сподіваюсь)
4. Якщо фізична адреса у футері - це також посилання, доречно його додати у список з контактами.
5. Основний бекграунд, який переважає на сторінках - білий, його можна задати на боді. На секціях Особливості та Чим ми займаємось нема сірого фону, він там білий
6. .header-nav>li,.header-contact>li { display: inline-block;}  - це зайве, у 3й роботі ми будемо робити списки у лінію завдяки флексам.
