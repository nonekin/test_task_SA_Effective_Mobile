# Задание 1: Проектирование API

1. 
GET /api/v1/partner-stores

GET /api/v1/partner-stores?city=Казань

city - город пользователя

2. Пример Json-ответа

{
  "success": true,
  "data": {
    "stores": [
      {
        "id": 201,
        "name": "METRO",
        "description": "Гипермаркет",
        "logo": "https://cdn.petrushka.ru/partners/metro/logo.png",
        "categories": ["Продукты", "Товары для дома"],
        "delivery_info": "Ближайшая доставка сегодня 21:00–23:00",
        "link": "https://metro.ru/?utm_source=petrushka_app",
        
      },
      {
        "id": 202,
        "name": "Ашан",
        "description": "Гипермаркет",
        "logo": "https://cdn.petrushka.ru/partners/auchan/logo.png",
        "categories": ["Продукты", "Одежда", "Товары для дома"],
        "delivery_info": "Ближайшая доставка сегодня 18:00–20:00",
        "link": "https://auchan.ru/?partner=petrushka",
      },
      {
        "id": 203,
        "name": "ВкусВилл",
        "description": "Продукты для здорового питания",
        "logo": "https://cdn.petrushka.ru/partners/vkusvill/logo.png",
        "categories": ["Продукты", "Здоровое питание", "Готовая еда"],
        "delivery_info": "Быстрая доставка от 20 до 60 минут",
        "link": "https://vkusvill.ru/?ref=petrushka",
       
      },
      {
        "id": 204,
        "name": "ВИКТОРИЯ",
        "description": "Сеть супермаркетов",
        "logo": "https://cdn.petrushka.ru/partners/victoria/logo.png",
        "categories": ["Продукты", "Готовая еда"],
        "delivery_info": "Ближайшая доставка сегодня 17:00–19:00",
        "link": "https://victoria.ru/?utm_source=petrushka",
      }
    ],
  }
}
