# Checkbox (EN)

Creating a simple checkbox function on JavaScript language.

#### HTML

```
<input type="checkbox" id="one" onchange="funChBox()">
```

#### JavaScript

```
function funChBox() {
    var checkbox
    checkbox = document.getElementById('one')

    if (checkbox.checked) {
        alert('Selected')
    } else {
        alert('Not selected')
    }
}
```

# Checkbox (RU)

Создание простой функции флажка на языке JavaScript.

#### HTML

```
<input type="checkbox" id="one" onchange="funChBox()">
```

#### JavaScript

```
function funChBox() {
    var checkbox
    checkbox = document.getElementById('one')

    if (checkbox.checked) {
        alert('Выбран')
    } else {
        alert('Не выбран')
    }
}
```
