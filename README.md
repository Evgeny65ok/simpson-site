# Simpson Site — CI/CD на GitHub Pages
Индивидуальный проект: статический сайт про Симпсонов на HTML + CSS + JS с автоматическим деплоем на GitHub Pages через GitHub Actions.

## 🎯 Цель проекта

Научиться самостоятельно деплоить «живой» сайт на GitHub Pages через CI/CD, видеть историю деплоев в интерфейсе GitHub и открывать сайт по кликабельной ссылке.

## 🌐 Живой сайт

**Открыть:** [https://evgeny65ok.github.io/simpson-site/](https://evgeny65ok.github.io/simpson-site/)

## 📸 Скриншоты

### 1. Открытый сайт на GitHub Pages
<img width="1851" height="1021" alt="Снимок экрана 2026-10-07 125816" src="https://github.com/user-attachments/assets/e6858df8-e0a4-476a-ab2a-ef0fb89e787e" />

### 2. GitHub Actions — успешные деплои
<img width="1798" height="858" alt="Снимок экрана 2026-10-07 130251" src="https://github.com/user-attachments/assets/3e15d49a-9a90-473a-b96f-f3456f952a77" />


### 3. Настройки Pages (Source: GitHub Actions)
<img width="1511" height="971" alt="Снимок экрана 2026-10-07 125729" src="https://github.com/user-attachments/assets/cac34893-b345-4b76-bbb9-b50177467b72" />


### 4. История деплоев (Deployments)
<img width="1794" height="931" alt="Снимок экрана 2026-10-07 130316" src="https://github.com/user-attachments/assets/2c05c89f-427a-447b-ad06-21b874cf1db3" />


### 5. About с ссылками
<img width="388" height="299" alt="image" src="https://github.com/user-attachments/assets/42696fe7-5b98-461c-8524-1b8ebb6df6aa" />

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
