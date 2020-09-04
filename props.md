# prpos

Une **fonction a des parametres** et les **composant ont des props.**

```html
function HelloWorld({label, age}){
        return (
            <div>
                <h6>salut a tous je m'appelle {label} et j'ai {age} ans </h6>
            </div>
        );
    }
    ReactDOM.render(
        <div>

        <HelloWorld label="djibssss" age="44"/>
        <HelloWorld label="fufu" age="44"/>
        </div>,
        document.getElementById("root")
    );
```
