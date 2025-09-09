```mermaid
gantt
    title Дорожная карта обмена ставками с колл-центром (Q2-Q3 2025)
    dateFormat  YYYY-MM-DD
    
    section Система управления ставками
    Разработка API :active, api, 2025-04-01, 45d
    Интеграция с бэк-офисом :active, integration, 2025-05-15, 25d
    Экспорт файлов через SFTP :active, sftp, 2025-06-01, 25d
    
    section Системы колл-центра
    Интеграция внутреннего колл-центра :active, internal, 2025-05-20, 30d
    Тестирование SFTP для внешнего колл-центра :active, external, 2025-06-20, 20d
    
    section Инфраструктура
    Настройка SFTP сервера :active, sftp_setup, 2025-05-05, 25d
    Тестирование системы :active, testing, 2025-06-15, 30d
    Развертывание в production :active, deploy, 2025-07-25, 10d
```