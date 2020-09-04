# Les bases  de react

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>salut</title>
    <script crossorigin src="https://unpkg.com/react@16.13.1/umd/react.development.js"></script>
    <script crossorigin src="https://unpkg.com/react-dom@16.13.1/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/axios/dist/axios.min.js"></script>
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>


</head>
<body>
<div id="root"></div>
<script type="text/babel">


//bas de page
ReactDOM.render(
        <div>
        </div>,
        document.getElementById("root")
    );
</script>
</body>
</html>

```

**Une seul balise `<div></div>` par fonction**

```html
 function ComposentSimpleH6(){
        return ( 
            <div>
                <h6>pure compon h6</h6>
            </div>
        );
    } 
```

**Un seul `ReactDom.render` par page.**


Le DOM est l'outil qui permet l'affichage de la page html+js.

