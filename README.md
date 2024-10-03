# 🌐 Обзор сервисов Azure

### В этом репозитории я представляю плюсы и минусы сервисов Azure, которые использую в финальном экзамене по Azure

---

## 🗄️ 1. Azure SQL

### ✅ Плюсы:
- **Масштабируемость**: Автоматически подстраивается под нагрузку, что позволяет оптимизировать работу и затраты.
- **Управляемость**: Полностью управляемая база данных, освобождающая от рутины по обслуживанию, резервным копиям и обновлениям.
- **Высокая доступность**: Встроенные механизмы резервирования данных и восстановление при сбоях.
- **Интеграция**: Хорошо взаимодействует с другими сервисами Azure, такими как Power BI и Azure Data Factory.

### ❌ Минусы:
- **Стоимость**: Может быть дорогим при высоких нагрузках и больших объемах данных, особенно для малых проектов.
- **Ограниченная настройка**: Меньше возможностей тонкой настройки серверной части по сравнению с классическими базами данных.
- **Ограничения размера**: Есть пределы на количество баз данных и их максимальный объем, что может ограничивать в крупных решениях.

---

## 🗂️ 2. Azure Blob Storage

### ✅ Плюсы:
- **Гибкость и масштабируемость**: Подходит для хранения больших объемов данных разного типа (файлы, видео, логи и т.д.).
- **Экономичность**: Разные уровни доступа (горячий, холодный, архивный) помогают снизить затраты в зависимости от частоты обращения к данным.
- **Интеграция с CDN**: Ускоряет доставку контента и уменьшает задержки при загрузке.
- **Безопасность**: Шифрование данных и продвинутые инструменты управления доступом.

### ❌ Минусы:
- **Ограниченная функциональность обработки**: Сам по себе не предоставляет возможностей для обработки данных, требуются дополнительные сервисы.
- **Сложности в управлении доступом**: Настройка прав доступа может быть трудоемкой в больших проектах.
- **Задержки при доступе к холодным данным**: Доступ к данным в холодных и архивных уровнях может занимать больше времени.

---

## ⚡ 3. Azure Cache for Redis

### ✅ Плюсы:
- **Быстрота**: Данные хранятся в оперативной памяти, что обеспечивает мгновенный доступ к ним.
- **Поддержка сложных структур данных**: Можно работать не только с простыми ключ-значениями, но и с множествами, хэшами, списками и другими структурами.
- **Масштабируемость**: Автоматическое масштабирование под нагрузку, что полезно для приложений с нестабильным трафиком.
- **Отказоустойчивость и репликация**: Позволяет сохранять данные и продолжать работу даже при сбоях.

### ❌ Минусы:
- **Высокая стоимость памяти**: Хранение данных в оперативной памяти может быть дорого при больших объемах данных.
- **Ограниченный объем кэша**: Данные могут теряться при нехватке памяти.
- **Сложности с администрированием**: Требуется опыт для настройки производительности и устойчивости.
- **Отсутствие постоянного хранения**: Данные могут потеряться при перезапуске, если не настроено их сохранение.

---
