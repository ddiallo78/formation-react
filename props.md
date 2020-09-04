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

        <HelloWorld label="djib" age="44"/>
        <HelloWorld label="mark" age="44"/>
        </div>,
        document.getElementById("root")
    );
```
**2eme methode pour passer des props avec des class**

```html
 class HelloMessage extends React.Component {
        render() {
            return (
                <div>
                    Salut {this.props.name}
                </div>
            );
        }
    }
ReactDOM.render(
        <div>
            <HelloMessage name="Thierry" />,
            <HelloMessage name="djibs" />,
        </div>,
        document.getElementById("root")
    );
``` 


