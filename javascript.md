```javascript
javascript:boxes=document.getElementsByClassName("js-reviewed-checkbox"),counter=0;for(let e=0;e<boxes.length;e++){const t=boxes[e];"File viewed, click, value:true"==t.dataset.gaClick&&(t.click(),counter++)}alert("Unfolded "+counter);
```

```javascript
Array.from(document.getElementsByClassName("class-name")).forEach(
    function(element, index, array) {
        console.log(element);
    }
);
```
