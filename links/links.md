# Links

## HTML-da giper murojaat (link, ssilka)

Giper murojaatlar HTML sahifalaridan boshqa sahifalarga yoki shu sahifadagi bazi bir hodisalarni amalga oshirish uchun ishlatiladi.

```html
<a href="url" target="_blank">Giper murojaat matni</a>
```

`href` asosiy attribut bo'lib gipermurojaat manzilini belgilab beradi.

`target` belgilangan giper murojaatni qay holatda ochilishini belgilab beradi:

- `_blank` ulangan sahifa yoki dokumentni yangi oynada ochadi
- `_self` ulangan sahifani shu oynaning o'zida ochadi (default qiymat)
- `_parent` ulangan sahifa yangi sahifada ochiladi
- `_too` ulangan sahifani oynaning bor o'lchamida ochadi
- `framename` ulangan sahifani nomi berilgan freymnda ochadi
