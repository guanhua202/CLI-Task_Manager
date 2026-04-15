# Release Notes (EN 🇺🇸)

### Beta v0.1
#### Program Logic

#### Basic commands:
  - ✅ Display a list of tasks
  - ✅ Add/Edit/Delete an issue
  - ✅ Exit the program sanctioned
#
### Beta v0.2:

#### Completed tasks:
  - ✅ 80% of errors are tracked
  - ✅ Added the ability to delete all tasks at once
  - ✅ Added comments
#
### Beta v0.3:

#### Improvements and additional changes:
  - ✅ Refactoring was carried out
#
### Beta v0.5:
#### Improvements and additional changes:
  - ✅ Changed task storage structure: from a flat list of strings to a list of dictionaries (`id_task`, `task_name`, `checked`)
  - ✅ Added file synchronization (menu item 9): manual saving to `tasks.txt` and loading from it
  - ✅ Introduced explicit task status: "In progress" / "Completed ✅"
  - ✅ Renamed functions for clarity: `list_output` → `display_tasks`, `change_task` → `modify_task`
  - ✅ Improved list output: now in the format "number | name | status" instead of just `--> task`
------------------------------------------------------------

# Примечания к выпуску (RU 🇷🇺)

### Бета v0.1
#### Логика программы

#### Основные команды:
  - ✅ Отображение списка задач
  - ✅ Добавление/редактирование/удаление проблемы
  - ✅ Выход из программы после получения разрешения
#
### Бета v0.2:

#### Выполненные задачи:
  - ✅ Отслеживается 80% ошибок
  - ✅ Добавлена возможность удалять все задания сразу
  - ✅ Добавлены комментарии
#
### Бета v0.3:

#### Улучшения и дополнительные изменения:
  - ✅ Был проведён Рефакторинг
#
### Бета v0.5:
#### Улучшения и дополнительные изменения:
  - ✅ Изменена структура хранения задач: вместо плоского списка строк — список словарей (id_task, task_name, checked)
  - ✅ Добавлена файловая синхронизация (пункт меню 9): ручное сохранение в tasks.txt и загрузка из него
  - ✅ Введён явный статус выполнения задачи: «В процессе» / «Завершена ✅»
  - ✅ Переименованы функции для наглядности: list_output → display_tasks, change_task → modify_task
  - ✅ Улучшен вывод списка: теперь в формате «номер | название | статус» вместо просто --> задача
