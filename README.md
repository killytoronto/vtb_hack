# SkillChain

SkillChain - это инновационная платформа для создания и управления цифровыми профилями сотрудников, основанная на технологиях Verifiable Credentials и NFT.

## Как запустить приложение

1. **Подготовка среды**:
   - Убедитесь, что у вас установлен современный веб-браузер (рекомендуется Chrome 90+, Firefox 88+, или Safari 14+).
   - Для полной функциональности установите расширение MetaMask (https://metamask.io/).

2. **Получение файлов**:
   - Скачайте файл `index.html` из репозитория проекта.
   - Если в репозитории есть дополнительные файлы (CSS, JS), убедитесь, что они находятся в правильных директориях относительно `index.html`.

3. **Запуск приложения**:
   - Дважды кликните на файл `index.html` в вашем файловом менеджере.
   - Альтернативно, откройте ваш браузер и перетащите файл `index.html` в окно браузера.

4. **Проверка запуска**:
   - Вы должны увидеть интерфейс SkillChain с заголовком и различными секциями (Профиль, Сертификаты, Навыки и т.д.).
   - Если вы видите ошибки в консоли браузера (F12 -> Console), проверьте правильность путей к файлам и наличие интернет-соединения.

## Подробное руководство по использованию

### 1. Профиль сотрудника
- Найдите раздел "Профиль сотрудника".
- Заполните поля "Имя" и "Должность".
- Нажмите "Сохранить" для создания профиля.
- После создания профиля вы сможете его редактировать, нажав "Редактировать".

### 2. Сертификаты и Награды
- Перейдите к разделу "Сертификаты и Награды".
- Введите название сертификата и его описание.
- Нажмите "Добавить сертификат".
- Добавленные сертификаты отобразятся ниже с опциями поделиться, посмотреть детали и верифицировать.

### 3. Навыки и Достижения
- В разделе "Навыки и Достижения" введите название навыка.
- Выберите уровень владения навыком (Начальный, Средний, Продвинутый).
- Нажмите "Добавить навык".
- Навыки будут отображаться с индикатором прогресса.

### 4. Рекомендации
- Найдите раздел "Рекомендации".
- Введите имя рекомендателя и текст рекомендации.
- Нажмите "Добавить рекомендацию".
- Рекомендации будут отображаться в виде карточек.

### 5. Социальные Группы
- В разделе "Социальные Группы" вы можете создавать группы и присоединяться к ним.
- Для создания группы введите название и описание, затем нажмите "Создать группу".
- Для присоединения к существующей группе нажмите "Присоединиться" рядом с нужной группой.

### 6. Карьерный Путь
- Раздел "Карьерный Путь" визуализирует ваш прогресс на основе добавленных навыков, сертификатов и участия в группах.
- Диаграмма обновляется автоматически при добавлении новых данных.

### 7. Верификация и NFT
- Нажмите кнопку "Верифицировать сертификаты" для создания NFT из ваших сертификатов.
- Используйте кнопку "Подключить MetaMask" для интеграции с вашим криптокошельком.

### 8. Стейкинг NFT
- После верификации сертификатов, вы можете использовать функцию стейкинга NFT.
- В разделе "Стейкинг NFT" вы увидите доступные NFT и уже застейканные NFT.
- Используйте кнопки "Stake" и "Unstake" для управления вашими NFT.

### 9. Интеграция с внешними сервисами
- В разделе "Интеграция с внешними сервисами" вы можете подключить такие платформы как Coursera, LinkedIn Learning и Udacity.
- Нажмите "Интегрировать" рядом с нужным сервисом для импорта сертификатов.

### 10. Soulbound NFT
- В разделе "Soulbound NFT" вы можете создать неотчуждаемый сертификат сотрудника SkillChain.
- Нажмите "Создать Soulbound NFT" для генерации этого уникального токена.

### 11. Визуализация Навыков
- Раздел "Визуализация Навыков" представляет ваши навыки в виде радарной диаграммы.
- Диаграмма автоматически обновляется при добавлении или изменении навыков.

### 12. Система Достижений
- По мере использования платформы вы будете получать различные достижения.
- О новых достижениях вас будут уведомлять всплывающие сообщения.

### 13. Система Баллов
- За различные действия на платформе вы будете получать баллы.
- Текущее количество баллов отображается в правом верхнем углу экрана.

## Дополнительные функции

- **Темная тема**: Переключайтесь между светлой и темной темой с помощью кнопки в верхнем правом углу.
- **Анимации**: Обратите внимание на плавные анимации при добавлении новых элементов и переходах между разделами.
- **Адаптивный дизайн**: Приложение оптимизировано для работы на устройствах с разными размерами экрана.

## Примечание о сохранении данных

Это демонстрационное приложение использует localStorage браузера для хранения данных. Это означает, что:
- Данные сохраняются только в текущем браузере на текущем устройстве.
- При очистке данных браузера вся информация будет утеряна.
- В full production-приложении неободима дорогая серверная часть для надежного хранения данных и обеспечения безопасности.

## Требования к системе

- Современный веб-браузер с поддержкой JavaScript, localStorage и WebGL (для визуализаций).
- Активное интернет-соединение для загрузки внешних ресурсов (шрифты, библиотеки).
- Расширение MetaMask для полной функциональности, связанной с блокчейном.

Приятного использования SkillChain! Если у вас возникнут вопросы или проблемы, пожалуйста, обратитесь к нам в тг.
