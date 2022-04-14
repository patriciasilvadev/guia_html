# HTML Semântico

Atualmente o papel da HTML não é apenas estruturar documentos para a web, mas também descrever o significado do conteúdo presente nesses documentos por meio de tags semânticas.


**Exemplo:**
```html
    <header>
       <h1>Cursos de programação</h1>
     </header>
     <aside>
        <nav>
            <ul>
                <li>Java</li>
                <li>PHP</li>
            </ul>
        </nav>
    </aside>
     <main>
         <section>
             <h2>Java</h2>
             <article>
                 <h3>Curso de JavaServer Faces</h3>
                 <p>Neste curso você aprenderá a desenvolver aplicações com JSF.</p>
             </article>
             <article>
                 <h3>Curso de Spring</h3>
                 <p>Neste curso você aprenderá utilizar o framework Spring.</p>
             </article>
         </section>
         <section>
             <h2>PHP</h2>
             <article>
                 <h3>Curso básico de PHP</h3>
                 <p>Conheça a linguagem de programação PHP.</p>
             </article>
             <article>
                 <h3>Curso de PDO</h3>
                 <p>Aprenda a acessar bancos de dados com PHP Data Objects.</p>
             </article>
         </section>
     </main>
     <footer>
         <p>MinhaEmpresa.com.br. Todos os direitos reservados.</p>
     </footer>
 ```
As principais tags semânticas:

* `<header>` tag utilizada para representar o cabeçalho
* `<nav>` tag utilizada quando precisamos representar um agrupamento de links de navegação
* `<aside>` tag utilizada quando precisamos criar um conteúdo de apoio/adicional ao conteúdo principal
* `<main>` essa tag especifica o conteúdo principal
* `<section>` essa tag representa uma seção 
* `<article>` tag utilizada quando precisamos declarar um conteúdo que não precisa de outro para fazer sentido
* `<footer>` essa tag representa um rodapé

[Voltar a Home](../README.md)

