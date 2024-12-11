
```
/project-root
├── /cmd             # Точка входа в приложение (main.go)
├── /internal        # Внутренние пакеты
│   ├── /models      # Определения структур (например, Task)
│   ├── /repository  # Работа с базой данных
│   ├── /services    # Бизнес-логика и методы Task
│   └── /handlers    # Обработчики HTTP-запросов
├── /pkg             # Переиспользуемые пакеты
├── /config          # Конфигурация приложения
└── /migrations      # SQL-миграции базы данных
└── go.mod
```