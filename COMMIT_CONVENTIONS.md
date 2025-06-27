---

## 📦 Commit Types

| Type      | Description                              |
|-----------|------------------------------------------|
| `feat`    | A new feature                            |
| `fix`     | A bug fix                                |
| `docs`    | Documentation only changes               |
| `style`   | Code formatting (white-space, etc)       |
| `refactor`| Code change that neither fixes a bug nor adds a feature |
| `test`    | Adding or updating tests                 |
| `chore`   | Maintenance tasks (e.g. tooling, deps)   |
| `build`   | Changes that affect the build system     |
| `ci`      | Changes to CI/CD configuration           |
| `revert`  | Reverts a previous commit                |

---

## 💡 Tips

- Use imperative mood in message (`add`, `fix`, not `added`, `fixed`)
- Keep messages short and clear
- Scope is optional, but recommended for large projects

---

## 🛑 Incorrect Messages

❌ `updated stuff`  
❌ `fixing bug`  
❌ `new feature`

---

✅ Use this guide to keep your commits clean and meaningful.

# Гайд по оформлению коммитов (Conventional Commits)

Чёткие и единообразные сообщения коммитов помогают быстро понимать историю проекта.  
Используем следующий формат:

## Возможные `type`

| Тип          | Когда использовать                                           | Пример                              |
| ------------ | ------------------------------------------------------------ | ----------------------------------- |
| **feat**     | Добавили новую функциональность                              | `feat(auth): авторизация по Google` |
| **fix**      | Исправили баг                                                | `fix(ui): починил скролл модалки`   |
| **docs**     | Изменения только в документации                              | `docs(readme): дополнил установку`  |
| **style**    | Форматирование, пробелы, точка с запятой, без изменения кода | `style: prettier форматирование`    |
| **refactor** | Рефакторинг без исправления багов и добавления фич           | `refactor(core): упростил логику`   |
| **test**     | Добавление/обновление тестов                                 | `test(api): тесты логина`           |
| **chore**    | Служебные задачи — обновление зависимостей, инструменты      | `chore(deps): обновил eslint`       |
| **build**    | Изменения в системе сборки                                   | `build: настроил webpack`           |
| **ci**       | Конфигурация CI/CD                                           | `ci: добавил GitHub Actions`        |
| **revert**   | Откат предыдущего коммита                                    | `revert: feat(login) ...`           |

## Правила

1. **Глаголы в повелительном наклонении**: `add`, `fix`, `update`, а не `added`, `fixed`.
2. **Scope (область)** — необязателен, но полезен в крупных проектах (модуль, папка, слой).
3. **Сообщение** — короткое (до 50 символов), без точки в конце.
4. Если нужен длинный текст — после пустой строки пишем подробное описание.

## Примеры правильных сообщений

```bash
feat(core): база проекта на Vanilla JS
fix(build): абсолютный путь к файлам
docs: дополнил инструкцию запуска
style: форматирование eslint.config.mjs
```
