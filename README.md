ТЕМА: КОМПОНЕНТНЫЙ ПОДХОД
1. Примеры подходов: функциональный и классовый.
2. Пример функционального подхода:

    export function App() {
        return (
            <div>
                <h1>hello world</h1>
            </div>
        );
    }
3. В папке src создать папку Components
4. Для каждого создать всою папку, например: Header, Main, Footer
5. В этих паках создаем комноненты, например: Header.jsx, Main.jsx, Footer.jsx
6. rfc
7. В App.jsx импортировать компоненты
8. export default function App(){
        return(
            <div className="container">
                <Header/>
                <Main/>
                <Footer/>
            </div>
        );
    }
9. Если при экспорте используем default, то другие элементы не будут импортироваться
10. Если импортируем без default то нужно обернуть элемент в {Elem}

ТЕМА: СТИЛИЗАЦИЯ
1. Чтобы поставить библиотеку нужно остановить старый и создать новый терминал.
2. npmjs.com => search => sass => npm i sass(terminal).
3. В package.json проверить добавился ли sass.
4. Компиляция НЕ НУЖНА.
5. В папках комненентов создать, например: header.scss
6. Подключить стили в файлах компонентов, например:  import './header.scss'