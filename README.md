
# WeatherApp

**WeatherApp (начало проекта)**  
В рамках изучения работы с API и Postman я создала **заготовку консольного приложения**, которое отправляет запросы к открытому API погоды.  
Проект помог мне освоить:  
- формирование и отправку HTTP-запросов,  
- обработку ответов в формате JSON,  
- настройку параметров запросов.  

На текущем этапе это **начальная структура проекта с примерами запросов**, которая в дальнейшем может быть доработана в полноценный Telegram-бот или веб-приложение.

---

## 🎯 Цель проекта

Этот проект был создан **для изучения работы с API, обработки данных в формате JSON, а также демонстрации практических навыков программирования на Python.**

---

## 📖 Описание

**WeatherApp** — это **консольное приложение**, которое отправляет запросы к открытому API [OpenWeatherMap](https://openweathermap.org/api) для получения данных о текущей погоде.  
Приложение разработано **в учебных целях** — для практики работы с API, обработки JSON-ответов и настройки параметров запросов.

---

## ✅ Функциональные возможности

- Отображение текущей погоды  
- Поиск погоды по названию города  
- Поддержка данных на русском языке  
- Использование API OpenWeatherMap для получения данных  

---

## ⚙️ Технологии

- **Язык программирования**: Python  
- **API**: [OpenWeatherMap](https://openweathermap.org/api)

---

## 📥 Установка

1. Клонируйте репозиторий:

   ```bash
   git clone https://github.com/Melsfi/Pyatkova_WeatherApp.git
   ```

2. Перейдите в директорию проекта:

   ```bash
   cd WeatherApp
   ```

3. Установите зависимости:

   ```bash
   pip install requests
   ```

---

## ⚙️ Настройка

1. Зарегистрируйтесь на [OpenWeatherMap](https://openweathermap.org/) и получите API-ключ.  
2. В файле `weather_app.py` замените строку:

   ```python
   api_key = "ВАШ_API_КЛЮЧ"
   ```

   на ваш реальный API-ключ.

---

## 🚀 Использование

1. Запустите приложение:

   ```bash
   python weather_app.py
   ```

2. Введите название города:

   ```text
   Введите название города: Москва
   ```

3. Получите данные о погоде:

   ```text
   В городе Москва сейчас облачно с прояснениями, температура 0.01°C
   ```

---

## 📝 Примеры вывода

После ввода названия города приложение отображает данные о погоде, такие как температура и описание:

```text
В городе Москва сейчас облачно с прояснениями, температура 0.01°C
```

---

## 🌐 Источники данных

Данные о погоде предоставляются сервисом [OpenWeatherMap](https://openweathermap.org/).

---

## 🔮 Будущие улучшения

- Добавление веб-интерфейса для удобного использования  
- Реализация прогноза погоды на несколько дней  
- Улучшение обработки ошибок при некорректном вводе  

---

## 📄 Лицензия

Этот проект лицензирован под лицензией **MIT**, что позволяет свободно использовать, копировать и изменять код для любых целей.
