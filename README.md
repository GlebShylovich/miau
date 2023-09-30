ТЕМА: КОМПОНЕНТНЫЙ ПОДХОД И СТИЛИЗАЦИЯ
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
8. export defult function App(){
    return(
        <div className="container">
            <Header/>
            <Main/>
            <Footer/>
        </div>
    );
}
9. Если при экспорте используем default, то другие элементы не будут импортироваться
10. Если импортирует без default то нужно обернуть элемент в {Elem}