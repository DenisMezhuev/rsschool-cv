# Ermakov Denis

## Contacts information:
* __Location:__ Mogilev, Belarus
* __Email:__ alexmezhuev@yandex.by
* __Telegram:__ @denis_mezhuev
* __GitHub:__ [DenisMezhuev](https://github.com/DenisMezhuev)

## About myself:
I want to ***learn*** **Front-End Development**

# Skills
* __HTML__
* __CSS__
* __JavaScript__ (*Basic*)
* __Git__ (*Basic*)
* __Markdown__ (*Basic*)


# Code Example

```
    (function(){
    function createTable(){
        let table = document.createElement("table");
        document.body.appendChild(table);
        createTrTd(table)
    }
    createTable()
    function createTrTd(table){
        let arr = [1, 2, 3, 4, 5, 6, 7, 8, 9];
        let res = 0;
        for(let j = 0; j < 3; j++){
            let tr = document.createElement("tr")
           
            for(let i = 0; i < 3; i++){
                let td = document.createElement("td");
                td.innerHTML = arr[res];
                res++;
                tr.appendChild(td);
            }
            table.appendChild(tr);
        }
    }
}())
```
