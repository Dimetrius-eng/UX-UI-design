# Лабораторна робота №8
## Дисципліна: Основи UX/UI дизайну
## Тема: "UI-компоненти інтерфейсу: кнопки, форми та їх стани. Побудова інтерактивного UI Kit у Figma"
### Виконав: студент групи РПЗ-33, Руденко Дмитро

### Мета роботи: 
<span>1. Ознайомитися з основними UI-компонентами інтерфейсу;</span>    
<span>2. Навчитися проєктувати кнопки, чекбокси, радіобатони та інпут-поля;</span>    
<span>3. Дослідити стани компонентів (default, hover, active, disabled, focus);</span>    
<span>4. Розробити систему компонентів у складі UI Kit;</span>   
<span>5. Навчитися використовувати варіанти (Variants) у Figma;</span>  
<span>6. Інтегрувати компоненти у власний інтерфейс;</span>  
<span>7. Використати інструменти ШІ для генерації ідей або текстів для UI.</span>  

### Матеріальне забезпечення занять:  
<span>1. Персональний комп'ютер, доступ до мережі Інтернет.</span>  
<span>2. Обліковий запис Google.</span>  
<span>3. Середовища Figma та FigJam.</span>

### Завдання для попередньої підготовки.

<div align="justify">

**<span>1. Зробіть короткий словник (5-7 термінів) базових понять англ. мовою.</span>**

_Словник базових понять англ. мовою_

| № | Слово | Пояснення |
| :--- | :--- | :--- |
| 1 | **Primary Button** | Головна кнопка дії, що має найбільшу візуальну вагу (зазвичай суцільна заливка) |
| 2 | **State** | Стан компонента, який змінюється залежно від взаємодії користувача |
| 3 | **Input Field** | Поле введення тексту (логін, вага, кількість повторень) |
| 4 | **Checkbox** | Елемент вибору, що дозволяє обрати кілька варіантів зі списку |
| 5 | **Radio Button** | Елемент вибору, що дозволяє обрати лише один варіант із групи |
| 6 | **Variant** | Функція у Figma для групування різних версій одного компонента в один блок |
| 7 | **Placeholder** | Тимчасовий текст у полі введення, що підказує користувачеві, які дані вводити |

**<span>2. Дайте відповіді на наступні питання:</span>**

<blockquote>

**2.1. Які існують типи кнопок у UI-дизайні?**

* **Primary:** Головна дія (напр., «Почати тренування»).
* **Secondary:** Допоміжна дія (напр., «Додати вправу»).
* **Ghost / Tertiary:** Текстова кнопка без фону для найменш важливих дій («Скасувати»).
* **FAB (Floating Action Button):** Кнопка, що «плаває» поверх контенту для швидкої дії.
* **Icon Button:** Кнопка, що складається лише з іконки (напр., «Налаштування»).
  
**2.2.** ***Чим відрізняється checkbox від radio button?**

* **Checkbox** використовується для множинного вибору (можна обрати 0, 1 або всі варіанти).
* **Radio button** — для одиничного вибору в групі (можна обрати лише один варіант).
  
**2.3.** ****Чому важливо проєктувати стан "Disabled" для кнопок?**

Стан **Disabled** візуально повідомляє користувачеві, що дія зараз недоступна (наприклад, поки не заповнені всі обов'язкові поля форми). Це запобігає зайвим помилкам та покращує UX.

***2.4.** ****Що таке стани компонентів і навіщо вони потрібні?**

Це візуальні зміни елемента залежно від взаємодії (**Default, Hover, Active, Focus, Disabled**). Вони створюють візуальний відгук (feedback), даючи зрозуміти користувачеві, що інтерфейс реагує на його дії.

**2.5.** ****Що таке "Focus state" і як він впливає на доступність (Accessibility)?**

**Focus state** — це підсвічування елемента при навігації клавіатурою. Це критично для доступності, оскільки дозволяє користувачам з обмеженими можливостями чітко бачити, який елемент зараз активний.

</blockquote>

## Хід роботи

### Практичне завдання №1. Аналіз UI-компонентів (FigJam) (базовий рівень)

**1. Розглянути додаткові навчальні матеріали та приклади:**   

- [Як працює Variant в Figma  | 4 урок | Курс "UI Kit"](https://youtu.be/XADRP9em7c0?si=JnymrSh1n7qd30BJ)
- [Кнопки UI Kit в Figma  | 10 урок | Курс "UI Kit"](https://youtu.be/zjgiJFZSBwg?si=SzuUD967TMoqIeKy)
- [Types of buttons in UI design: Best practices and examples - LogRocket Blog](https://blog.logrocket.com/ux-design/types-of-buttons-in-ui-design/)
- [Buttons in UI Design: Four Common Styles | by Nick Babich | UX Planet](https://uxplanet.org/buttons-in-ui-design-four-common-styles-f6bd02468388)
- [Чекбокси & Радіобатони в Figma | 11 урок | Курс "UI Kit"](https://youtu.be/bXc2kP0aurE?si=L87-JDRiK9VVZtdc)
- [Radio buttons, checkboxes та інші види селекторів - UXPUB 🇺🇦 Дизайн-спільнота](https://ux.pub/editorial/radio-buttons-checkboxes-ta-inshi-vidi-sieliektoriv-49pl)
- [Radio buttons, checkboxes, toggle switches, and dropdown lists: design tips for using selection](https://uxplanet.org/radio-buttons-checkboxes-toggle-switches-and-dropdown-lists-design-tips-for-using-selection-d120a1e323c5)
- [Checkbox vs radio button: when to use which in UI design - Justinmind](https://www.justinmind.com/ui-design/radio-button-vs-checkbox)
- [Інпути в UI Kit  | 12 урок | Курс "UI Kit"](https://youtu.be/SvKmjTENmeU?si=ClcQWr4cHTfkdVWJ)
- [Expertly Crafted Text Fields for Optimized Forms - Input UI Design](https://www.setproduct.com/blog/input-ui-design)
- [Text fields - Material Design](https://m2.material.io/components/text-fields#outlined-text-field)

**2. Дослідіть і зафіксуйте у FigJam:** 

- Зробіть собі короткий мануал по типам та станам кнопок, елементів вибору та стилів інпутів (елементів вводу), які використовуються в сучасних UI-інтерфейсах;
  
- Знайдіть 2–3 приклади інтерфейсів (Behance / Dribbble), які відповідають напрямку вашого проєкту. Проаналізуйте, які типи кнопок, стилі інпутів, чекбокси та радіобатони там використано. Чи можете ви подібні ідеї використати у своєму проєкті?
  
- Зробіть короткий мануал, які компоненти будуть потрібні для вашого проєкту.

[Посилання на дошку FigJam]()

### Практичне завдання №2. *Розробка кнопок та їх станів (Figma) (середній рівень)

**1. У середовищі Figma на основі вашого проєкту (див. попередні ЛР):**

- створіть мінімум дві кнопки типу Primary Button та Secondary Button (відповідно до обраної вами палітри в ЛР №6);
  
- для кожної кнопки реалізуйте стани - Default, Hover, Active, Disabled тощо.

**2. Використайте Variants для організації кнопок та додайте їх до вашого UI Kit;**

**3. Інтегруйте кнопки (або опишіть, якщо вони вже використані) у 1–2 екрани вашого проєкту (дизайн з попередніх ЛР).**

**4. Перевірте узгодженість кнопок з іншими елементами інтерфейсу.**

### Практичне завдання №3. **Чекбокси, радіобатони, поля вводу та їх валідація (підвищений рівень) 

**1. У середовищі Figma розробіть:**

- Checkbox (checked / unchecked / disabled) та Radio button (selected / unselected / disabled). Додайте для них стани hover / active (за можливості);  
- Створіть input field з label та placeholder. Реалізуйте стани default, focus, error та success. Додайте підказку (helper text) та повідомлення про помилку.
  
**2. Використайте для організації компоненти variants  та додайте їх до вашого UI Kit.**

**3. Інтегруйте компоненти у 1–2 екрани вашого проєкту (дизайн з попередніх ЛР) або розробіть новий екран (наприклад, форма реєстрації, якщо ваші дизайни таких компонентів не передбачали.**

**4. Перевірте узгодженість кнопок з іншими елементами інтерфейсу.**

[Посилання на дошку Figma]()

### Контрольні запитання

**1. Де в інтерфейсі доцільно розміщувати Placeholder, а де Label?**

**Label** розміщується зовні поля (зазвичай зверху) і є постійним орієнтиром. **Placeholder** знаходиться всередині поля і зникає при введенні, тому він має містити лише підказку щодо формату даних.
 
**2.** ***Який розмір "області натискання" (Click target) вважається мінімально допустимим для мобільних пристроїв?**

Мінімально допустимий розмір — **44x44 px** (iOS) або **48x48 dp** (Android).

**3.** ****Яку роль відіграє іконка в полі вводу (наприклад, "око" у полі пароля)?**

Вона покращує юзабіліті, дозволяючи користувачеві перевірити введені дані (пароль) без необхідності його повторного введення, що зменшує кількість помилок при авторизації.

## Conclusions

In this laboratory work I mastered the principles of creating complex interactive UI components and building a consistent UI Kit. I learned how to use **Figma Variants** to organize different component states, which significantly speeds up the design process and ensures visual consistency. I implemented robust button and input systems with proper validation states (**Error/Success**), ensuring high usability for the fitness application. This work established a professional design system compliant with modern accessibility and mobile UI standards.











