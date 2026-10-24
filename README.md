# 📷 Magic of Photography

**Magic of Photography** is a landing page for a photography school, built as
a team project at the GoIT school.

🔗 **Live demo:** https://masenko2604.github.io/magic-of-photography/

---

## About the project

A responsive one-page website that presents the school, its courses and
mentors, and invites visitors to sign up for a course.

## Sections

- **Header** — logo, navigation to page sections, Sign up button, burger menu
  for mobile
- **Hero** — main offer with a large photo
- **Advertisement** and **About us**
- **Our courses** — list of courses with links to the sign-up form
- **Our mentors** — team of teachers
- **Sign up form**
- **Reviews** from students
- **Footer** with contacts and social links
- **Go to top** button

## Technologies

|                   |                                                  |
| ----------------- | ------------------------------------------------ |
| Markup and styles | HTML5, CSS3, BEM, modern-normalize, Google Fonts |
| Responsive images | `<picture>`, `srcset`, WebP, retina 1x / 2x      |
| Logic             | JavaScript (ES6+): mobile menu, go-to-top button |
| Animation         | animate.css                                      |
| Build             | Vite, vite-plugin-html-inject (HTML partials)    |
| Deploy            | GitHub Actions, GitHub Pages                     |

Adaptive layout: mobile (from 320px), tablet (768px) and desktop (1280px).

## Project structure

```
src/
├── index.html        # main page
├── partials/         # HTML sections (header, hero, courses, mentors, form…)
├── css/              # styles for each section
├── js/               # mobile menu, go-to-top button
└── img/              # images and SVG sprite
```

## How to run locally

```bash
git clone https://github.com/Masenko2604/magic-of-photography.git
cd magic-of-photography
npm install
npm run dev
```

Production build: `npm run build` (the result goes to the `dist` folder).

## Team

The project was made by a team of developers: each section in its own branch,
merged into `main` through pull requests with code review.

| Developer       | GitHub                                                       | Contribution |
| --------------- | ------------------------------------------------------------ | ------------ |
| Tatiana Masenko | [@Masenko2604](https://github.com/Masenko2604)               | Header       |
|                 | [@MV1talii](https://github.com/MV1talii)                     |              |
|                 | [@IliyaSamoilov](https://github.com/IliyaSamoilov)           |              |
|                 | [@VitaliiGoIT](https://github.com/VitaliiGoIT)               |              |
|                 | [@Akisha0707](https://github.com/Akisha0707)                 |              |
|                 | [@Bohdana1958](https://github.com/Bohdana1958)               |              |
|                 | [@Anastasia-Kostenko](https://github.com/Anastasia-Kostenko) |              |
|                 | [@Ksuishakusk](https://github.com/Ksuishakusk)               |              |
|                 | [@Ruslan-33](https://github.com/Ruslan-33)                   |              |

### My part — header

I developed the **header** of the site (`src/partials/header.html`,
`src/css/header.css`):

- logo from the SVG sprite, navigation links to all page sections and the
  Sign up button
- responsive layout: full navigation on desktop, burger button on mobile and
  tablet
- hover and focus effects for links
- entrance animation with animate.css

---

## Описание (RU)

**Magic of Photography** — лендинг школы фотографии, командный проект школы
GoIT. Адаптивная вёрстка (мобильный, планшет, десктоп), секции: шапка, hero,
о нас, курсы, менторы, форма записи, отзывы, футер; мобильное меню и кнопка
«наверх». Технологии: HTML, CSS, JavaScript, Vite, animate.css, GitHub Pages.

**Моя часть — header:** логотип из SVG-спрайта, навигация по секциям, кнопка
Sign up, адаптивность (бургер-меню на мобильных и планшетах), эффекты
наведения и анимация появления.
