# 🎵 Spotify Clone - Team Collaboration Exam Project

## 🚀 Front-end დეველოპმენტის პროგრამის პირველი ნაწილის საგამოცდო ჯგუფური პროექტი
---

## 👥 გუნდი და პასუხისმგებლობები

* **ხათია ბურდული** — `Header` & `Sidebar` (ზედა ნავიგაცია და გვერდითი პანელი).
* **ნოდარ კიკნაძე** — `Main Content Container` & `Cards` (შიდა კონტეინერი, ფილტრები და "Made For You" სექცია).
* **ანა ალთუნაშვილი** — `Footer Player` (ქვედა ფიქსირებული მართვის პანელი).

---

## 🛠 გამოყენებული ტექნოლოგიები (Tech Stack)

* **HTML5** - სტრუქტურისთვის.
* **SASS (SCSS)** - სტილებისთვის (Flexbox, Grid, Responsive Design).
* **NPM** - პაკეტების მართვისთვის.
* **Git/GitHub** - ვერსიების კონტროლისა და კოლაბორაციისთვის.

---

## 🛠 ტექნიკური მოთხოვნები (Engineering Standards)

პროექტის თითოეული ნაწილი უნდა აკმაყოფილებდეს შემდეგ სტანდარტებს:

1.  **სემანტიკური HTML:** გამოიყენეთ მხოლოდ შესაბამისი ტეგები (`<header>`, `<nav>`, `<main>`, `<aside>`, `<footer>`).
2.  **SASS არქიტექტურა:** * მინიმუმ **15 ცვლადი** (ფერები, დაშორებები, რადიუსები).
    * მინიმუმ **2 mixin** (მაგ: flex-center, text-truncate).
    * Nesting-ის მაქსიმალური დონე: **5**.
3.  **Naming Convention:** გამოიყენეთ ინგლისური, აღწერითი სახელები (მაგ: `.player-controls`, `.sidebar-link`).
4.  **Responsive:** არ გამოიყენოთ `fixed width` პიქსელებში იქ, სადაც ელემენტი უნდა იყოს მოქნილი.

---

## 📌 ინდივიდუალური დავალებების ნიუანსები

### 🟦 ხათია (Header & Sidebar)
* **Sidebar:** უნდა იყოს `aside` ტეგში. აუცილებელია `ul > li > a` სტრუქტურა. მინიმუმ 10 ნავიგაციის ელემენტი. ერთი ელემენტი (`My Library`) უნდა იყოს `active`.
* **Header:** უნდა იყოს `main`-ში. გამოიყენე `justify-content: space-between` მარცხენა (Home/Discover/Search) და მარჯვენა (Icons) ნაწილების გასაყოფად.

### 🟧 ნოდარი (Main Content & Cards)
* **Filters:** "All", "Music", "Podcasts", "Audiobooks" უნდა იყოს `pill-style` ფორმის. "All" უნდა იყოს `active`.
* **Cards:** "Made For You" სექციაში მინიმუმ **8 ქარდი**. თითოეულს უნდა ჰქონდეს სურათი, სათაური და ქვესათაური. გამოიყენე `flex-row` ან `grid`.

### 🟪 ანა (Footer Player)
* **პოზიციონირება:** აუცილებლად `position: fixed; bottom: 0; width: 100%;`.
* **სტრუქტურა:** დაყავი 3 მკაფიო ბლოკად (`.player-left`, `.player-center`, `.player-right`).
* **Center Zone:** აუცილებელია Timeline (ზოლი) და დროის მაჩვენებლები (0:00).