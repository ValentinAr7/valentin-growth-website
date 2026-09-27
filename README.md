# Valentin Arnautski — Marketing & E-commerce Growth Expert

Презентационен сайт с цел продажба на маркетинг/e-commerce консултантски услуги.
Изграден с [Astro](https://astro.build) + [Tailwind CSS v4](https://tailwindcss.com).

## Структура на проекта

```text
/
├── public/                 # статични файлове (favicon, снимки, ...)
├── src/
│   ├── components/         # секции на сайта, всяка в собствен .astro файл
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── Services.astro
│   │   ├── About.astro
│   │   ├── Process.astro
│   │   ├── Results.astro
│   │   ├── Testimonials.astro
│   │   ├── FAQ.astro
│   │   ├── CTA.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro    # базов HTML shell, SEO мета данни, шрифт
│   ├── pages/
│   │   └── index.astro     # композира всички секции в главната страница
│   └── styles/
│       └── global.css      # Tailwind + брандиращи цветове/токъни (@theme)
└── astro.config.mjs
```

Всяка секция от сайта е отделен компонент — лесно е да пренаредиш, скриеш
или пренапишеш само едно парче, без да пипаш останалите.

Местата с `// TODO:` в компонентите маркират плейсхолдър съдържание
(случаи, отзиви, снимка, контакти), което трябва да се замени с реални данни.

## Команди

| Команда           | Действие                                    |
| :----------------- | :------------------------------------------- |
| `npm install`       | Инсталира зависимостите                      |
| `npm run dev`       | Стартира dev сървър на `localhost:4321`      |
| `npm run build`     | Билдва продукционната версия в `./dist/`     |
| `npm run preview`   | Преглед на билднатата версия локално         |

## Следващи стъпки

- [ ] Реално съдържание: биография, услуги, кейс стъдита, отзиви
- [ ] Реални снимки/визуали (или AI-генерирани, стилизирани spécifично за бранда)
- [ ] Свързване на CTA формата с реален канал (Calendly / имейл форма)
- [ ] Домейн + deploy (Vercel / Netlify / Cloudflare Pages)
- [ ] SEO мета данни, Open Graph изображение
- [ ] Аналитика (напр. Plausible / GA4)
