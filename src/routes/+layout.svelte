<header>
    <div id="topLayout">
        <h1 id="title">NotesApp</h1>
    </div>
</header>
<body>
    <main>
        <slot></slot>
    </main> 
</body>
<footer>
    <p id="copyright">© 2023 NotesApp</p>
</footer>


<style>
    #title{
        text-align: center;
        margin-left: 20px;
        margin-right: 20px;
        width: 150px;

        border: solid 2px black;
    }
    #copyright{
        text-align: center;
        margin-top: 50px;
    }
    #topLayout{
        border-bottom: solid 2px black;
    }
</style>