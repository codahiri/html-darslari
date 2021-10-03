# HTML Forms

## HTML-da form elementlari

HTML-da `<form>` tegi orqali foydalanuvchidan turli xildagi ma'lumotlarni olishimiz mumkin bo'ladi. Formalar har doim form elementlaridan tashkil topgan bo'ladi.

[forms](https://www.notion.so/3f44f7e06e40498fa876d42fa96a0b2f)

```html
<form action="#">
  <label for="name">Ismingizni kiriting</label>
  <input type="text" id="name" placeholder="name" />
  <br />
  <label for="surname">Familiyangizni kiriting</label>
  <input type="text" id="ism" placeholder="surname" />
  <br />
  <button type="submit">Yuborish</button>
</form>

<!-- Radio -->
<form>
    <input type="radio" id="html" name="fav_language" value="HTML" />  
  <label for="html">HTML</label><br />
    <input type="radio" id="css" name="fav_language" value="CSS" />  
  <label for="css">CSS</label><br />
   
  <input type="radio" id="javascript" name="fav_language" value="JavaScript" />
    <label for="javascript">JavaScript</label>
</form>

<!-- Chackbox -->
<form action="/action_page.php">
  <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike" />
  <label for="vehicle1"> I have a bike</label><br />
  <input type="checkbox" id="vehicle2" name="vehicle2" value="Car" />
  <label for="vehicle2"> I have a car</label><br />
  <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat" />
  <label for="vehicle3"> I have a boat</label><br /><br />
  <input type="submit" value="Submit" />
</form>

<!-- Select -->
<form action="/action_page.php">
  <label for="cars">Choose a car:</label>
  <select id="cars" name="cars">
    <option value="volvo">Volvo</option>
    <option value="saab">Saab</option>
    <option value="fiat">Fiat</option>
    <option value="audi">Audi</option>
  </select>
  <input type="submit" />
</form>

<!-- fieldset -->
<form action="/action_page.php">
  <fieldset>
    <legend>Personalia:</legend>
    <label for="fname">First name:</label><br />
    <input type="text" id="fname" name="fname" value="John" /><br />
    <label for="lname">Last name:</label><br />
    <input type="text" id="lname" name="lname" value="Doe" /><br /><br />
    <input type="submit" value="Submit" />
  </fieldset>
</form>

<!-- datalist -->
<form action="/action_page.php">
  <input list="browsers" name="browser" />
  <datalist id="browsers">
    <option value="Internet Explorer"></option>
    <option value="Firefox"></option>
    <option value="Chrome"></option>
    <option value="Opera"></option>
    <option value="Safari"></option>
  </datalist>

  <input type="submit" />
</form>
```
