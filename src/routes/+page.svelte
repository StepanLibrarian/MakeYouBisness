<svelte:head>
    <title>Логика</title>
</svelte:head>

<div class="container">
    <div class="header">
        <div class="Icon">
            <h1>Логика</h1>
            <p>Лучшие инструменты</p>
        </div>
        <div class="menu">
            <div class="item">
                <a href="">
                    <h2>О нас</h2>
                    <p>важно</p>
                </a>
            </div>
            <div class="item">
                <a href="">
                    <h2>Блог</h2>
                    <p>блог компании</p>
                </a>
            </div>
            <div class="item">
                <a href="">
                    <h2>Статьи</h2>
                    <p>лучшие статьи</p>
                </a>
            </div>
            <div class="item">
                <a href="">
                    <h2>Программы</h2>
                    <p>для бизнесса</p>
                </a>
            </div>
        </div>
    </div>
    <div class="MainContainer">
        <div class="main">
            <div class="EmpInfoMain">
                <h3>Лучший сотрудник месяца</h3>
                <p />
                <img
                    alt="Сотрудник месяца"
                    src="images/EmployeeOfTheMonth.jpg"
                />
            </div>
            <div class="IdologyInfoMain">
                <div class="TaskIdol">
                    <h3>Наша цель</h3>
                    <p>
                        Главная цель нашей компании - создание полезного
                        продукта для начинающих и опытных бизнесменов! Для
                        достижения этой цели мы нанимаем лучших менеджеров,
                        программистов и тестировщиков, которые готовы
                        добросовестно трудиться над созданием лучшего продукта в
                        своем роде!
                    </p>
                </div>
                <div class="DesireIdol">
                    <h3>Наши желания</h3>
                    <p>
                        Мы хотим стать ведущей компанией в сфере разработки
                        профессиональных инструментов для бизнеса. Мы стремимся
                        создавать продукты, которые будут помогать достигать
                        новых высот в своей деятельности. Мы верим в командную
                        работу, важность каждого члена нашей команды и честность
                        в отношениях с нашими клиентами. У нас нет предела
                        совершенству, и мы всегда ищем новые решения и
                        возможности для улучшения наших продуктов.
                    </p>
                </div>
                <div class="Office">
                    <div class="OfficeImg">
                        <img src="images/Office1.jpg" alt="Офис в Москве" />
                        <img src="images/Office2.jpg" alt="Офис в спб" />
                    </div>
                    <div class="AboutOffice">
                        <p>
                            Наши главные офисы расположенны как в Москве, так и
                            в Санкт-Петербурге. Офисы находятся в просторных и
                            современных зданиях в центре городов. Каждый, кто
                            попадает в наши офисы, сразу чувствует энергию и
                            творческий дух, который оживляет нашу команду. Мы
                            постарались создать комфортное и продуманное
                            пространство, чтобы наши сотрудники могли
                            максимально эффективно работать. У нас есть
                            несколько открытых рабочих площадок, где команды
                            могут свободно общаться и сотрудничать друг с
                            другом. Также у нас есть комнаты для встреч и
                            переговоров, оборудованные новейшими технологиями
                            для проведения онлайн-встреч и конференций.
                        </p>
                    </div>
                    <div class="OurClients">
                        <div class="ClientsText">
                            <p>Наши клиенты</p>
                        </div>
                        <div class="ClientsImg">
                            <img src="images/ClientVk.png" alt="kVk" />
                            <img src="images/ClientYa.jpg" alt="aYa" />
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="aside">
            <div class="ArticleImg">
                <img src="images/icon.jpg" alt="icon" />
            </div>
            <div class="Article">
                <img src="images/moose.jpg" alt="moose" />
                <p>03.06.2023</p>
                <p>
                    Меня зовут Илья , и я хочу рассказать о фреймворке Svelte,
                    который стал для меня настоящей находкой. Для тех, кто не
                    знаком с этим инструментом, Svelte - это open-source
                    JavaScript-фреймворк для создания веб-приложений. Одно из
                    главных преимуществ Svelte - это то, что он позволяет писать
                    код практически так же, как в обычном HTML и CSS. Для
                    сравнения, во многих других фреймворках <i>....</i>
                </p>
            </div>
            <div class="Article">
                <img src="images/Kat.jpg" alt="Kat" />
                <p>02.06.2023</p>
                <p>
                    Привет всем! Меня зовут Василий, и сегодня я хочу рассказать
                    вам о моем любимом JavaScript-фреймворке - React. В
                    настоящее время React является одним из самых популярных
                    фреймворков в веб-разработке. Я хочу поделиться с вами своим
                    опытом и объяснить, почему я считаю, что React - отличный
                    выбор для разработки приложений любого уровня сложности. <i
                        >....</i
                    >
                </p>
            </div>
        </div>
    </div>
    <div class="footer">
        <p>&#x24b8 2023</p>
    </div>
</div>

<style>
    .header {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        background-color: #231a09;
        color: white;
        margin-left: 10px;
    }
    .menu {
        display: flex;
        justify-content: space-around;
    }
    .item {
        border: solid #000000 1px;
        margin-left: 10px;
        color: white;
    }
    a {
        color: white;
        text-decoration: none;
    }
    a:visited {
        color: white;
        text-decoration: none;
    }
    a:active {
        color: grey;
        text-decoration: none;
    }
    .MainContainer {
        display: flex;
    }
</style>
