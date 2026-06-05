# Как залить проект на GitHub

## Вариант через сайт GitHub

1. Зайди на GitHub.
2. Нажми `+` в правом верхнем углу.
3. Выбери `New repository`.
4. Название:

```text
sound-engineer-ai-chatgpt-project
```

5. Description:

```text
Ready-to-use ChatGPT Project Pack for plugin screenshot analysis, DAW help, vocal chains, mixing and mastering feedback.
```

6. Visibility: `Public`.
7. License: MIT.
8. Создай репозиторий.
9. Загрузи все файлы из этой папки.

## Вариант через Terminal

Открой Terminal в папке проекта:

```bash
cd sound-engineer-ai-chatgpt-project
git init
git add .
git commit -m "Initial Sound Engineer AI ChatGPT Project Pack"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/sound-engineer-ai-chatgpt-project.git
git push -u origin main
```

## Что должно быть в корне репозитория

```text
README.md
LICENSE
.gitignore
CONTRIBUTING.md
CHANGELOG.md
chatgpt_sources/
docs/
examples/
github_assets/
```

## Что написать в About на GitHub

Description:

```text
Ready-to-use ChatGPT Project Pack for music producers, artists and mixing engineers.
```

Website:

```text
оставь пустым, если сайта нет
```

Topics:

```text
chatgpt
chatgpt-project
sound-engineering
mixing
mastering
audio-production
music-production
logic-pro
ableton-live
fl-studio
plugins
vocal-chain
```

## Что написать в релизе v0.1.0

Title:

```text
v0.1.0 — Initial ChatGPT Project Pack
```

Description:

```text
First public version of Sound Engineer AI ChatGPT Project Pack.

Includes:
- Project instructions
- User plugin profile template
- Official manual source index
- Screenshot analysis rules
- Audio analysis rules
- Vocal chain rules
- Mastering chain rules
- DAW workflow rules
- Plugin starting settings
- Response templates
```

## Важно

Не загружай в репозиторий:

- свои приватные WAV-файлы
- чужие треки
- платные семплы
- API-ключи
- чужие PDF-мануалы
- личные данные пользователей
