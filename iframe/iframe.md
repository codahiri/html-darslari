# iframe

## HTML-da freymlar

Freymlarni `<iframe>` tegi orqali yaratiladi. `<iframe>` -ning bir nechta attributlari mavjud:

- `height` ifreym balandligini belgilaydi
- `width` ifreym kengligini belgilaydi
- `src` ifraymda yuklanishi kerak bo'lgan sahifa manzilini belgilab beradi
- `title` video sarlavhasini belgilaydi
- `frameborder` video chegarasini belgilaydi
- `sandbox` ifreymga ba'zi cheklovlarni qo'yadi
  - `allow-forms`
  - `allow-pointer-lock`
  - `allow-popups`
  - `allow-same-origin`
  - `allow-scripts`
  - `allow-top-navigation`

```html
<iframe
  width="560"
  height="315"
  src="https://www.youtube.com/embed/YPsR8uEHbSo"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen
>
</iframe>
```

[https://www.youtube.com/embed/YPsR8uEHbSo](https://www.youtube.com/embed/YPsR8uEHbSo)

**[Video](https://youtu.be/biI9OFH6Nmg)**

<iframe width="560" height="315" src="https://www.youtube.com/embed/biI9OFH6Nmg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
