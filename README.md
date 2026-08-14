# Market FFB — SMM Landing (Data-Editorial)

Премиальный одностраничный лендинг SMM-услуг в стиле «data-editorial»: терминальная эстетика, лаймовые акценты, характерная типографика. Готов к деплою на GitHub Pages с доменом `marketffb.ru`.

## 🎨 Дизайн-система

| Элемент | Значение |
|---|---|
| Заголовки | **Unbounded** (характерный геометричный) |
| Текст | **Golos Text** (кириллица) |
| Цифры/данные | **JetBrains Mono** |
| Светлый фон | `#F6F5F1` (тёплая бумага) |
| Тёмный фон | `#0E0F0C` (уголь) |
| Акцент | `#D7FF3E` (лайм) |

## ✨ Возможности

- Терминал-дашборд в hero с live-метриками и count-up
- Marquee-лента ниш, scroll progress bar, scrollspy-навигация
- Cookie-баннер (152-ФЗ) + модалки «Политика» и «Оферта»
- SEO: Schema.org (ProfessionalService, FAQPage, HowTo), OG, геотеги
- Mobile-first адаптация, `prefers-reduced-motion`

## 🚀 Деплой

1. Создайте репозиторий, загрузите 4 файла в корень
2. **Settings → Pages → Deploy from branch → main / root → Save**
3. В **Custom domain** впишите `marketffb.ru`
4. У регистратора домена настройте A-записи:
   ```
   @  A  185.199.108.153
   @  A  185.199.109.153
   @  A  185.199.110.153
   @  A  185.199.111.153
   www  CNAME  YOUR_USERNAME.github.io.
   ```
5. Включите **Enforce HTTPS** после активации

## 🔧 Форма

Замените `YOUR_FORM_ID` на ваш ID с [formspree.io](https://formspree.io/) в строке:
```html
<form ... action="https://formspree.io/f/YOUR_FORM_ID" ...>
```

## 🔍 Верификация

Раскомментируйте в `<head>` и подставьте ID:
```html
<meta name="yandex-verification" content="...">
<meta name="google-site-verification" content="...">
```

## 📞 Контакты

marketFFB@bk.ru · [@Artur_FFB](https://t.me/Artur_FFB) · +7 912 279 23 77
