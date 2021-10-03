# Basic

**HTML** (**H**yper**T**ext **M**arkup **L**anguage - Gipermatinli belgilash titli) ko'pchilik web sahifalarning asosiy tashkil etuvchisi bo'lib, u brauzer bilan interpritatsiyaga kirishadi va ining natijasida ekranga matinlar, rasmlar, videolar va boshqa ma'lumotlarni chiqaradi.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <h1>Bu sarlavha</h1>
    <p>Bu paragraf</p>
  </body>
</html>
```

- `<!DOCTYPE html>` **HTML5** ekanligini bildirib turuvchi va e'lon qiluvchi.
- `<html lang="en">` HTML sahifaning asosiy ildiz elementi.
- `<head>` o'zida sahifaning meta ma'lumotlarini saqlaydi.
- `<title>` o'zida sahifaning sarlavhasini saqlaydi.
- `<body>` o'zida sahifaning ko'rinadigan qismini saqlaydi.
- `<h1>` Bu element bosh sarlavhani e'lon qiluvchi teg.
- `<p>` punktni e'lon qiluvchi teg

### Teglar va ularni ishlatilishi

Teg bu - foydalanuvchi tomonidan brauzerga web sahifa ma'lumotlarini qanday ko'rsatish haqidagi beriladigan buyruqdir.

`<teg nomi>`Bu matin`</teg nomi>`

`<a>`Bu giper murojaat`</a>`

`<h1>`Bu sarlavha`</h1>`

`<b>`Bu qalin yozuvli matin`</b>`

Har bir tegning o'ziga hos attributlari mavjud. Bu attributlar teg ichidagi ma'lumotlar rangi, holati va boshqa parametirlariga ta'sir qiladi.

`<img src="img.png" alt="New image" />`
