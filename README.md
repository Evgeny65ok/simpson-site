# Simpson Site — CI/CD на GitHub Pages

Индивидуальный проект: статический сайт про Симпсонов на HTML + CSS + JS с автоматическим деплоем на GitHub Pages через GitHub Actions.

## 🎯 Цель проекта

Научиться самостоятельно деплоить «живой» сайт на GitHub Pages через CI/CD, видеть историю деплоев в интерфейсе GitHub и открывать сайт по кликабельной ссылке.

## 🌐 Живой сайт

**Открыть:** [https://evgeny65ok.github.io/simpson-site/](https://evgeny65ok.github.io/simpson-site/)

## 📸 Скриншоты

### 1. Открытый сайт на GitHub Pages
![Site](site.png)

### 2. GitHub Actions — успешные деплои
![Actions](actions.png)

### 3. Настройки Pages (Source: GitHub Actions)
![Pages Settings](pages-settings.png)

### 4. История деплоев (Deployments)
![Deployments](deployments.png)

### 5. About с ссылками
![About](about.png)

## 📄 Страницы сайта

- 🏠 `index.html` — главная
- 🍩 `gomer.html` — Гомер Симпсон
- 👩 `Mardge.html` — Мардж Симпсон
- 🛹 `Bart.html` — Барт Симпсон
- 📚 `Liza.html` — Лиза Симпсон

## 🛠 Технологии

- **HTML5** — разметка страниц
- **CSS3** — стилизация, анимации, градиенты
- **JavaScript** — интерактив
- **GitHub Actions** — CI/CD
- **GitHub Pages** — хостинг

## 📁 Структура проекта

```mermaid
graph TD
    A[simpson-site] --> B[.github/workflows/ci-cd.yml]
    A --> C[index.html]
    A --> D[gomer.html]
    A --> E[Mardge.html]
    A --> F[Bart.html]
    A --> G[Liza.html]
    A --> H[style.css]
    A --> I[Bart/ - картинки]
    A --> J[gomer/ - картинки]
    A --> K[mardge/ - картинки]
    A --> L[lizaIMG/ - картинки]
    A --> M[icon/ - иконки]
    A --> N[img/ - gif-анимации]
    A --> O[README.md]
```

## 🔁 CI/CD

**Файл конфигурации:** `.github/workflows/ci-cd.yml`

### 🚀 Как обновить сайт

Внесите необходимые изменения в файлы проекта (HTML/CSS/JS), а затем выполните в терминале следующие команды:

```bash
git add .
git commit -m "Update"
git push origin main
```

> ⏱ Через **30 секунд** изменения автоматически появятся на «живом» сайте!

## 📊 История обновлений

| # | Коммит | Изменение |
| :--- | :--- | :--- |
| **1** | `Initial commit` | Первая версия сайта |
| **2** | `Update 1` | Изменён заголовок |
| **3** | `Update 2` | Изменён фон |
| **4** | `Update 3` | Изменён текст |

## 🔗 Полезные ссылки

- 🌐 [Живой сайт](https://evgeny65ok.github.io/simpson-site/)
- ⚙️ [GitHub Actions](https://github.com)
- 🚀 [Deployments](https://github.com)
- 📦 [Environments](https://github.com/github-pages)

## 👤 Автор

- **Evgeny65ok** — [GitHub Профиль](https://github.com)
