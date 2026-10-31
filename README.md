# Galabir

![Galabir](images/cover.png)

**Galabir** — читабельний глаголичний шрифт для українського тексту.
**Galabir** is a readable Glagolitic typeface for Ukrainian and other Cyrillic Slavic languages.

[🇺🇦 Українська](#українська) · [🇬🇧 English](#english) · [Specimen](https://kosoglotoff-netizen.github.io/galabir/) · [Behance](https://www.behance.net/gallery/244865775/Galabir)

---

## Українська

### Про шрифт

Сучасні глаголичні шрифти важко читати: здебільшого в них немає виносних елементів
(асцендерів і десцендерів), немає різниці між великими та малими літерами, а багато
знаків надто схожі між собою.

Головна мета Galabir — **читабельність**. Для цього ми застосували принцип латинки,
де великі й малі літери походять з різних стилів письма:

- **великі літери** — з **кутастої (хорватської) глаголиці**;
- **малі літери** — з **круглої (болгарської) глаголиці**;
- **виносні елементи й хвостики** — запозичені з **глаголичного скоропису**.

У результаті текст, набраний Galabir, читається значно легше, ніж в інших глаголичних шрифтах.

Шрифт створено на основі відкритого шрифту [League Spartan](https://github.com/theleagueof/league-spartan)
для української мови. Він також підходить для інших слов'янських мов, що використовують кирилицю:
болгарської, сербської, білоруської, македонської, чорногорської.

![Алфавіт](images/alphabet-1.png)
![Алфавіт](images/alphabet-2.png)

### Як це працює

Набирайте звичайним **кириличним** текстом, і шрифт покаже його **глаголицею**.
Нічого перемикати не треба: «Слава Україні» у Galabir одразу виглядає глаголичним написом.
Латинські літери, цифри й розділові знаки залишаються з League Spartan.

| | |
|---|---|
| Накреслення | Light (300) |
| Версія | 4.0 |
| Формати | TTF (для встановлення), WOFF2 (для вебу) |

### Завантажити та встановити

1. Відкрийте сторінку [**Releases**](https://github.com/kosoglotoff-netizen/galabir/releases/latest) і завантажте `Galabir.zip`.
2. Розпакуйте архів.
3. Встановіть шрифт:
   - **macOS** — двічі клацніть файл `.ttf` → «Встановити шрифт»;
   - **Windows** — правою кнопкою на файлі `.ttf` → «Встановити для всіх користувачів»;
   - **Linux** — скопіюйте файл у `~/.local/share/fonts/` і виконайте `fc-cache -f`.

Після встановлення шрифт з'явиться у Figma, Word, Photoshop та інших програмах.

### Використання на сайті

Додайте в `<head>`:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/kosoglotoff-netizen/galabir@latest/css/galabir.css">
```

і використовуйте в CSS:

```css
.glagolitic {
  font-family: "Galabir", sans-serif;
}
```

Або підключіть файл шрифту напряму:

```css
@font-face {
  font-family: "Galabir";
  src: url("https://cdn.jsdelivr.net/gh/kosoglotoff-netizen/galabir@latest/fonts/Galabir-Light.woff2") format("woff2");
  font-weight: 300;
  font-style: normal;
  font-display: swap;
}
```

> Щоб зафіксувати конкретну версію, замініть `@latest` на номер релізу, наприклад `@v1.0.0`.

### Ліцензія

Galabir поширюється за ліцензією **[SIL Open Font License 1.1](OFL.txt)**: його можна вільно
використовувати, зокрема в комерційних проєктах, змінювати й поширювати. Продавати сам шрифт
окремо не можна. Похідні шрифти теж мають виходити під OFL.

---

## English

### About

Modern Glagolitic fonts are hard to read: most have no ascenders or descenders,
no distinction between uppercase and lowercase, and many letters look too similar in running text.

Galabir's main goal is **readability**. We borrowed the Latin-script approach, where uppercase
and lowercase come from different writing styles:

- **uppercase** is based on **Angular (Croatian) Glagolitic**;
- **lowercase** is based on **Round (Bulgarian) Glagolitic**;
- **ascenders, descenders and tails** come from **Glagolitic cursive**.

The result is a Glagolitic typeface that is much more readable and accessible.

Galabir is built on the open-source [League Spartan](https://github.com/theleagueof/league-spartan)
and designed for Ukrainian. It also suits other Cyrillic Slavic languages: Bulgarian, Serbian,
Belarusian, Macedonian and Montenegrin.

### How it works

Type ordinary **Cyrillic** text and Galabir renders it in **Glagolitic** — no special keyboard needed.
Latin letters, digits and punctuation come from League Spartan.

Style: Light (300) · Version 4.0 · Formats: TTF (desktop), WOFF2 (web)

### Download & install

1. Go to [**Releases**](https://github.com/kosoglotoff-netizen/galabir/releases/latest) and download `Galabir.zip`.
2. Unzip it.
3. Install the `.ttf` file:
   - **macOS** — double-click → *Install Font*;
   - **Windows** — right-click → *Install for all users*;
   - **Linux** — copy to `~/.local/share/fonts/` and run `fc-cache -f`.

### Use on the web

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/kosoglotoff-netizen/galabir@latest/css/galabir.css">
```

```css
.glagolitic {
  font-family: "Galabir", sans-serif;
}
```

Pin a version by replacing `@latest` with a release tag, e.g. `@v1.0.0`.

### License

Galabir is licensed under the **[SIL Open Font License 1.1](OFL.txt)**. You may use it freely,
including commercially, and modify and redistribute it. The font may not be sold on its own,
and derivative fonts must also be released under the OFL.

---

## Автори · Credits

- **Дизайн / Design:** Павло Салига (Pavlo Salyha) і Дарія Нагладзе (Daria Nagladze) — [Behance](https://www.behance.net/gallery/244865775/Galabir)
- **Основа / Based on:** [League Spartan](https://github.com/theleagueof/league-spartan) © The League Spartan Project Authors (OFL 1.1)
