# ✨ WooX — Менеджер WooCommerce для macOS
![WooX Logo](WooX.png)  
**WooX** — это стильное и удобное приложение для macOS, которое интегрируется с **WooCommerce**. Оно позволяет получать уведомления и быстро просматривать информацию о магазине прямо из строки меню.  

## WooCommerce → Настройки → Дополнительно → REST API

- `siteURL` - URL вашего магазина
- `consumerKey` - Ключ доступа к WooCommerce API
- `consumerSecret` - Секретный ключ доступа

Данные сохраняются в `UserDefaults`, загружаются при каждом запуске и не передаются на внешние серверы.

<br>

##  Основные возможности
- `Уведомления` - информируют пользователя о новых заказах и изменениях статусов заказов
- `Счетчик заказов` - отображает текущее количество заказов, распределенных по статусам
- `Статистика продаж` - отображает информацию о выручке за текущий день, месяц и предыдущий месяц

<br>

## Требования

| Платформа | Версия |
|-----------|--------|
| macOS | 10.15+  |
| WooCommerce API | REST API |
