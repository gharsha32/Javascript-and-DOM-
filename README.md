# Javascript-and-DOM-

### To add mouse events.
```javascript
nameOfTheItem.addEventListener('click', () => {
  // the function you want to perform when the button is clicked;
}) /*in place of click, you can also type hover, dblClick./* 
```

### Selecting page elements by id
```javascript
document.getElementById('nameOfTheId');
```

### Slecting elements by tag name
```javascript
document.getElemtsByTagName('nameOfTheTag');
// This will selct all the elements with the specified tag name
```

### To select elements by class name
```javascript
document.getElementsByClassName('nameOfTheClass');
```

### querySelector
```javascript
document.querySlector('nameOfTheElement');
/*you can select a class, a tag or even an id with this selector by placing a 'dot(.)' before the class name or a 'hash(#)' between the name of the id you want to select. This gives you the first element of the page which has the specified class or id or tag name*/
```

### querSelectorAll
```
document.querySlectorAll('nameOfTheElement');
/*you can select a class, a tag or even an id with this selector by placing a 'dot(.)' before the class name or a 'hash(#)' between the name of the id you want to select. This gives you all the elements of the page which has the specified class or id or tag name*/
```

### To modify the content in an element
```javascript
element.textContent="content of your wish"; // You can also see what's inside an element using this property
```

### To the elements in the HTML
```javascript
document.innerHTML='';
/*between the '', you can change any element in html. like: change a paragraph into a list item. you can also change the content of inside an element.*/
```

### To know the attribute of an element
```javascript
element.value; // you can also change the atribute by assigning a new value
```
Example: <input type="text">

```javascript
input. type; //output: text
input.type="checkBox"; //output: check Box
```
