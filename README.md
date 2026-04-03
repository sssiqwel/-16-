# КТ16 — Blazor: события и формы

Учебный проект на **Blazor Web App** (.NET 8, интерактивный режим **Server**): обработка кликов и ввода (`@onclick`, `@oninput`, `@onchange`), форма с выводом данных, форма обратной связи с валидацией в реальном времени и простой капчей.

**Репозиторий на GitHub:** [github.com/sssiqwel/-16-](https://github.com/sssiqwel/-16-)

Клонирование:

```bash
git clone https://github.com/sssiqwel/-16-.git
cd -16-
```

## Запуск

```bash
dotnet run --project КТ16.csproj
```

Откройте в браузере адрес из консоли (обычно `https://localhost:...`).

## Структура кода

| Компонент | Файл |
|-----------|------|
| Форма ввода (имя, возраст, пол, сброс) | [`Components/FormComponent.razor`](Components/FormComponent.razor) |
| Форма обратной связи (валидация, отправка, очистка, капча) | [`Components/FeedbackForm.razor`](Components/FeedbackForm.razor) |
| Главная страница | [`Components/Pages/Home.razor`](Components/Pages/Home.razor) |

## Скриншоты

Файлы в папке [`screenshots/`](screenshots/).

### Пример из шаблона: Counter (`@onclick`)

Страница `/counter` — демонстрация обработки события нажатия кнопки.

![Counter — пример из презентации / шаблона Blazor](screenshots/photo_2026-04-03_05-03-55.jpg)

### Пример из шаблона: Weather (отображение данных)

Страница `/weather` — таблица с данными.

![Weather — демонстрация вывода данных](screenshots/photo_2026-04-03_05-03-58.jpg)

### Часть 1: форма ввода и текущие значения

Главная страница: `FormComponent` — имя, возраст, пол, кнопка «Сбросить», блок «Текущие значения».

![Часть 1 — форма ввода](screenshots/photo_2026-04-03_05-03-41.jpg)

### Часть 2: форма обратной связи после отправки

Успешная отправка, сообщение «Форма отправлена!», блок «Последняя отправка».

![Часть 2 — форма обратной связи](screenshots/photo_2026-04-03_05-03-51.jpg)
