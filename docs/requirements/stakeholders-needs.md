# Запити зацікавлених осіб

## Вступ <a id="introduction"></a>

Цей документ містить коротко описані основні визначення, необхідні інструменти для роботи майбутньої системи.


### Мета <a id="target"></a>
Нашою ціллю є створення інструменту для моніторингу та аналізу ЗМІ.
Це потрвбно для полегшення пошуку певних публікацій, статтей тощо.

### Контекст <a id="context"></a>
В цьому документі йдеться про технічне завдання для системи аналізу медіа-контенту.

### Основні визначення та скорочення <a id="notation"></a>
_Інтернет-ЗМІ_ — інформаційний сайт,
який регулярно оновлюється і виконує функцію засобу масової інформації (ЗМІ),
користується певною популярністю і авторитетом (має свою постійну аудиторію). [[1]](https://uk.wikipedia.org/wiki/%D0%86%D0%BD%D1%82%D0%B5%D1%80%D0%BD%D0%B5%D1%82-%D0%97%D0%9C%D0%86)

_Мас-медіа_ — засоби передавання, зберігання та відтворення інформації,
призначені для її донесення крізь просторові, часові чи інші перепони. [[2]](https://uk.wikipedia.org/wiki/%D0%97%D0%B0%D1%81%D0%BE%D0%B1%D0%B8_%D0%BC%D0%B0%D1%81%D0%BE%D0%B2%D0%BE%D1%97_%D1%96%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D1%96%D1%97)

_Соціальні медіа_ — вид мас-медіа, ряд онлайнових технологій на, 
завдяки яким споживачі контенту через свої дописи стають його співавторами
і можуть взаємодіяти, співпрацювати, спілкуватися, ділитися інформацією або брати участь
у будь-якій інший соціальній активності із теоретично усіма іншими користувачами певного сервісу. [[3]](https://uk.wikipedia.org/wiki/%D0%A1%D0%BE%D1%86%D1%96%D0%B0%D0%BB%D1%8C%D0%BD%D1%96_%D0%BC%D0%B5%D0%B4%D1%96%D0%B0)

_Цифрові медіа_ — це будь-які носії, які закодовані в машиночитаючих форматах. Цифрові медіа можуть бути: створені, 
переглянуті, поширені, змінені і збережені на цифрових електронних пристроях. Приклади цифрових медіа включають: веб-сторінки, 
цифрові зображення, цифрове відео, програмне забезпечення, відеогри, і вебсайти, в тому числі соціальні медіа, дані і бази даних, 
цифрові аудіо, як наприклад MP3 і електронні книги. [[4]](https://uk.wikipedia.org/wiki/%D0%A6%D0%B8%D1%84%D1%80%D0%BE%D0%B2%D1%96_%D0%BC%D0%B5%D0%B4%D1%96%D0%B0)

_NLP - natural-language processing_ - загальний напрям інформатики,
штучного інтелекту та математичної лінгвістики. Він вивчає проблеми комп'ютерного аналізу та синтезу природної мови.
Стосовно штучного інтелекту аналіз означає розуміння мови, а синтез — генерацію розумного тексту.
Розв'язок цих проблем буде означати створення зручнішої форми взаємодії комп'ютера та людини. [[5]](https://uk.wikipedia.org/wiki/%D0%9E%D0%B1%D1%80%D0%BE%D0%B1%D0%BA%D0%B0_%D0%BF%D1%80%D0%B8%D1%80%D0%BE%D0%B4%D0%BD%D0%BE%D1%97_%D0%BC%D0%BE%D0%B2%D0%B8)

_Big Data_ - це технологія обробки великих масивів даних. Кінцевою метою цієї обробки є отримання результатів, 
які легко сприймаються людиною та є ефективними в умовах безперервного росту й розподілення інформації 
по численних вузлах обчислювальної мережі.[[6]](https://uk.wikipedia.org/wiki/%D0%92%D0%B5%D0%BB%D0%B8%D0%BA%D1%96_%D0%B4%D0%B0%D0%BD%D1%96)

### Посилання <a id="links"></a>

[[1] Wikipedia - Інтернет-ЗМІ](https://uk.wikipedia.org/wiki/%D0%86%D0%BD%D1%82%D0%B5%D1%80%D0%BD%D0%B5%D1%82-%D0%97%D0%9C%D0%86)

[[2] Wikipedia - Мас-медіа](https://uk.wikipedia.org/wiki/%D0%97%D0%B0%D1%81%D0%BE%D0%B1%D0%B8_%D0%BC%D0%B0%D1%81%D0%BE%D0%B2%D0%BE%D1%97_%D1%96%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D1%96%D1%97)

[[3] Wikipedia - Соціальні медіа](https://uk.wikipedia.org/wiki/%D0%A1%D0%BE%D1%86%D1%96%D0%B0%D0%BB%D1%8C%D0%BD%D1%96_%D0%BC%D0%B5%D0%B4%D1%96%D0%B0)

[[4] Wikipedia - Цифрові медіа](https://uk.wikipedia.org/wiki/%D0%A6%D0%B8%D1%84%D1%80%D0%BE%D0%B2%D1%96_%D0%BC%D0%B5%D0%B4%D1%96%D0%B0)

[[5] Wikipedia - NLP](https://uk.wikipedia.org/wiki/%D0%9E%D0%B1%D1%80%D0%BE%D0%B1%D0%BA%D0%B0_%D0%BF%D1%80%D0%B8%D1%80%D0%BE%D0%B4%D0%BD%D0%BE%D1%97_%D0%BC%D0%BE%D0%B2%D0%B8)

[[6] Wikipedia - Big Data](https://uk.wikipedia.org/wiki/%D0%92%D0%B5%D0%BB%D0%B8%D0%BA%D1%96_%D0%B4%D0%B0%D0%BD%D1%96)

## Короткий зміст 

1. [Вступ](#introduction)
    * [Мета](#target)
    * [Контекст](#context)
    * [Основні визначення та скорочення](#notation)
    * [Посилання](#links)
2. [Характеристика ділових процесів](#characteristic)
3. [Короткий огляд продукту](#survey)
4. [Функціональність](#functionality)
5. [Практичність](#practicality)
6. [Надійність](#reliability)
7. [Продуктивність](#productivity)
8. [Експлутаційна придатність](#serviceability)

## Характеристика ділових процесів <a id="characteristic"></a>

**ID:** Media content analysis system Version: 1.0.0

**НАЗВА:** Отримання певної медіа-інформаціїї

**УЧАСНИКИ:** Клієнт, Сервіс, Модератор

**ПЕРШИЙ СЦЕНАРІЙ:**

***Реєстрація***

**ОСНОВНИЙ СЦЕНАРІЙ:**

1.Клієнт заходить на сервіс 

2.Клієнт натискає кнопку реєстрації

3.Клієнт здійснює запит на перехід на сторінку реєстрації

4.Система перенаправляє клієнта на сторінку реєстрації

5.Клієнт заповнює поля форми реєстрації

6.Клієнт натискає кнопку відправлення форми реєстрації

7.Клієнт здійснює запит на реєстрацію

8.Система шифрує пароль клієнта

9.Система заносить дані в базу даних

10.Система перенаправляє клієнта на сторінку авториації

**ДРУГИЙ СЦЕНАРІЙ:**

***Аутентифікація/авторизація***

**ОСНОВНИЙ СЦЕНАРІЙ:**

1.Клієнт заповнює поля форми авторизації

2.Клієнт натискає кнопку відправлення форми авторизації

3.Клієнт здійснює запит на авторизацію

4.Система звіряє дані з полів авторизації з даними в БД

5.Система створює веб-токен

6.Система відправляє веб-токен клієнту

7.Система перенаправляє клієнта на головну сторінку

**ТРЕТІЙ СЦЕНАРІЙ:**

***Пошук інформації***

**ОСНОВНИЙ СЦЕНАРІЙ:**

1.Клієнт заповнює поле пошуку інформації

2.Клієнт натискає кнопку пошуку інформації

3.Клієнт надсилає запит на пошук інформації 

4.Система надає клієнту форму фільтрації для пошуку інформації

5.Кілєнт заповнює поля форми фільтрації

6.Клієнт натискає кнопку відправлення форми фільтрації

7.Клієнт здійснює запит на відправлення форми фільтрації

8.Система звіряє дані з форми фільтрації з даними в БД

9.Система формує дані для відповіді клієнту

10.Система відправляє сформовані дані клієнту

**ЧЕТВЕРТИЙ СЦЕНАРІЙ:**

**ОСНОВНИЙ СЦЕНАРІЙ:**

***Задання питання в підтримку системи***

1.Клієнт заповнює поля форми зворотнього зв'язку

2.Клієнт натискає кноку відправлення форми зворотнього зв'язку

3.Клієнт відправляє запит відправлення форми зворотнього зв'язку

4.Система заносить дані із запиту в БД

**П'ЯТИЙ СЦЕНАРІЙ:**

**ОСНОВНИЙ СЦЕНАРІЙ:**

***Обробка запитання модератором***

1.Модератор обробляє питання, зареєстроване в бд

2.Модератор формує відповідь клієнту

3.Модератор заповнює форму відповіді клієнту

4.Модератор натискає кноку відправлення форми відповіді клієнту

5.Система обробляє запит

6.Система надсилає відповідь клієнту

## Короткий огляд продукту <a id="survey"></a>

"Media content analysis system" – це сервіс, система аналізу та надання запитуваної користувачем інформації з медіа джерел. Користувач має можливість виставити критерії інформації, що шукається, таким чином сортуючи її. Сортувати інформацію можна за датою та часом, популярністю, джерелом. Також надається можливість зберігання інформації.


## Функціональність <a id="functionality"></a>

**Клієнт має можливість:**
* На користування захищеною системою, без страху за свої персональні дані
* Швидко отримувати необхідну інформацію, яка його цікавить
* Розраховувати на оперативну допомогу від служби підтримки сервісу

*_Права ж користувача надають йому можливість реєстрації, авторизації до облікового запису, можливість пошуку контенту і можливість зв’язку з модератором._*

**Сервіс має можливість:** 
* Бути розрахованим для користування як фізичними, так і юридичними особами 
* Мати user friendly інтерфейс
* Бути захищеним, продуктивним та оптимізованим
* Мати оперативний якісний зворотній зв'язок з клієнтом

**Система має можливість:**
* Збирати, аналізувати, обробляти інформацію 
* Надавати відповіді на запити користувача у зрозумілій і доступній для нього формі
* Для забезпечення зручності роботи з додатком (як користувача, так і модератора) для відведення певних наборів функцій і впорядкування робочого процесу, сценарії використання було реалізовано відведенням відповідних окремих інтерфейсів

**Модератор має можливість:**
* Вчасно обробляти запитання та надсилати відповіді клієнту
* Своєчасно обробляти інформацію про виявлені користувачем баги, та передавати її в технічний відділ

*_Права модератора надають йому можливість спостереження за медіа джерелами і їх контентом, можливість зв’язку з користувачами, якщо в останніх виникають певні питання або проблеми, можливість спостереження за роботою системи, маючи доступ до відповідних відомостей._*

## Практичність <a id="practicality"></a>

Робота сервісу, пошук контенту та надання відповіді по запиту проходить з достатньою швидкістю, система має user friendly інтерфейс, що надає користувачу можливість швидко опанувати функціонал сервісу і зрозуміти його суть.

## Надійність <a id="reliability"></a>

Сервіс повинен захищати зібрані, оброблені дані, доступ до них мають лише адміністратори, для цієї інформації повинна існувати окрема база даних. Система має бути всіма можливими способами убезпечена від можливих технічних проблем, що можуть спричинити унеможливлення користування нею. У разі можливого збою система має зберегти останні використовувані дані.

## Продуктивність <a id="productivity"></a>

Об'єми запитів користувачів, об'єми отраманої на запит та обробленої інформації визначають продуктивність системи.

## Експлуатаційна придатність <a id="serviceability"></a>

Сервіс здатний витримувати великі навантаження та великі об'єми вхідних і вихідних даних.

