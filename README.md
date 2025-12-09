# Kod Haqqında Sənəd

## HTML Kodu

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Document</title>
</head>
<body>
    <div class="card">
        <img class="chip" src="https://img.icons8.com/plasticine/2x/sim-card-chip.png" alt="chip">
        <p id="card-number">4500 6812 5512 6089</p>
        <p id="card-owner">ALEKSEEV IVAN</p>
        <p id="vt07">Valid thru:</p>
        <p id="valid-thru">07/22</p>
    </div>
</body>
</html>
```

## CSS Kodu

```css
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
.card{
    width: 240px;
    height: 140px;
    background-color: #833ae0;
    padding-left: 3px;
    border-radius: 10px;
}
.chip{
    width: 30px;
    height: 30px;
    margin-top: 15px;
}
#card-number{
    color: white;
    font-size: 18px;
    margin-top: auto;
    font-family: Courier;
    padding-left: 5px;
}
#card-owner{
    color: white;
    font-size: 14px;
    margin-top: 5px;
    font-family: monospace;
    padding-left: 5px;
}
#valid-thru{
    color: white;
    font-size: 12px;
    padding-left: 5px;
    font-family: tahoma;
}
#vt07{
    color: white;
    font-size: 10px;
    margin-top: 20px;
    padding-left: 5px;
    font-family: tahoma;
}
```

## Kod haqqında Qısa İzah

Bu HTML və CSS kodları sadə bir **bank kartı dizaynı** yaradır. HTML strukturunu qurur, CSS isə kartın rənglərini, ölçülərini və yerləşməsini tənzimləyir.

Kartda:

* Çip şəkli
* Kart nömrəsi
* Kart sahibinin adı
* Son istifadə tarixi

kimi məlumatlar göstərilir.

---

## License

```text
MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
