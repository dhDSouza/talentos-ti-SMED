# HTML5 Semântico

## 1. Introdução ao HTML5 Semântico

**Explicação:** O `HTML5` trouxe uma série de novas tags semânticas que melhoram a estrutura do documento, tornando o código mais fácil de entender tanto para desenvolvedores quanto para mecanismos de busca. Elas ajudam a descrever melhor o conteúdo da página, indicando o papel que cada seção desempenha.

**Principais Tags Semânticas:**

- **Tag `<header>`:** Representa o cabeçalho de uma página ou de uma seção.
- **Tag `<nav>`:** Define um conjunto de links de navegação.
- **Tag `<main>`:** Indica o conteúdo principal da página.
- **Tag `<section>`:** Agrupa conteúdos relacionados, geralmente com um cabeçalho.
- **Tag `<article>`:** Representa um conteúdo independente, como um artigo ou post.
- **Tag `<aside>`:** Contém informações relacionadas, como uma barra lateral.
- **Tag `<footer>`:** Define o rodapé da página ou de uma seção.

**Exemplo:**

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de HTML5 Semântico</title>
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Site</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section id="home">
            <h2>Início</h2>
            <p>Esta é a seção principal da nossa página.</p>
        </section>

        <section id="sobre">
            <h2>Sobre Nós</h2>
            <p>Informações sobre o nosso site.</p>
        </section>

        <article>
            <h3>Último Artigo</h3>
            <p>Aqui está o conteúdo de um artigo importante.</p>
        </article>
    </main>

    <aside>
        <h3>Links Úteis</h3>
        <ul>
            <li><a href="https://www.exemplo.com">Exemplo 1</a></li>
            <li><a href="https://www.exemplo2.com">Exemplo 2</a></li>
        </ul>
    </aside>

    <footer>
        <p>&copy; 2024 Meu Site. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
```

**Explicação:** Nesse exemplo, usamos várias tags semânticas do HTML5 para estruturar o conteúdo da página de forma mais clara e organizada.

---

## 2. Benefícios das Tags Semânticas

**Explicação:** O uso de tags semânticas em HTML5 melhora a acessibilidade, a otimização para mecanismos de busca (SEO) e facilita a manutenção do código.

### Principais Benefícios

1. **Acessibilidade:** Facilita a navegação em leitores de tela.
2. **SEO:** Os motores de busca entendem melhor o conteúdo, melhorando o ranqueamento.
3. **Legibilidade:** O código fica mais organizado e fácil de entender.

---

## 3. Estrutura Básica de um Documento Semântico

**Explicação:** A estrutura de uma página HTML5 semântica segue uma organização intuitiva com tags específicas para cada tipo de conteúdo.

**Exemplo Estrutural:**

- **Header**: Cabeçalho da página ou seção.
- **Nav**: Links de navegação.
- **Main**: Conteúdo principal.
- **Section**: Partes principais dentro do conteúdo.
- **Article**: Conteúdos independentes, como posts ou artigos.
- **Aside**: Informações adicionais ou complementares, como links úteis.
- **Footer**: Rodapé com informações sobre a página.

---

## 4. Boas Práticas com HTML5 Semântico

### 4.1 Separando Conteúdo com Seções

**Explicação:** Utilize a tag `<section>` para dividir o conteúdo de acordo com os temas. Por exemplo, se sua página tem uma parte sobre serviços e outra sobre equipe, cada uma pode ser uma `<section>`.

**Exemplo:**

```html
<main>
    <section>
        <h2>Nossos Serviços</h2>
        <p>Oferecemos uma gama de serviços personalizados.</p>
    </section>

    <section>
        <h2>Nossa Equipe</h2>
        <p>Conheça os profissionais que fazem a diferença.</p>
    </section>
</main>
```

### 4.2 Artigos Independentes

**Explicação:** Use a tag `<article>` quando o conteúdo puder ser reutilizado de forma independente, como um post de blog ou um artigo de notícias.

**Exemplo:**

```html
<article>
    <h3>Artigo Recente</h3>
    <p>Este é um artigo independente que pode ser compartilhado em outros sites.</p>
</article>
```

### 4.3 Navegação Intuitiva com `<nav>`

**Explicação:** A tag `<nav>` deve ser usada para agrupar links de navegação.

**Exemplo:**

```html
<nav>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#services">Serviços</a></li>
        <li><a href="#contact">Contato</a></li>
    </ul>
</nav>
```

---

### **Atividade Prática**

1. **Crie a Estrutura Semântica de uma Página de Portfólio**

    - Utilize as tags `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>` e `<footer>` para criar uma página simples de portfólio.

    **Exemplo:**

    ```html
    <header>
        <h1>Meu Portfólio</h1>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre Mim</a></li>
                <li><a href="#projetos">Projetos</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="sobre">
            <h2>Sobre Mim</h2>
            <p>Sou desenvolvedor web com experiência em diversas tecnologias.</p>
        </section>

        <section id="projetos">
            <h2>Meus Projetos</h2>
            <article>
                <h3>Projeto 1</h3>
                <p>Descrição do Projeto 1.</p>
            </article>
            <article>
                <h3>Projeto 2</h3>
                <p>Descrição do Projeto 2.</p>
            </article>
        </section>
    </main>

    <aside>
        <h3>Links Externos</h3>
        <ul>
            <li><a href="https://github.com">GitHub</a></li>
            <li><a href="https://linkedin.com">LinkedIn</a></li>
        </ul>
    </aside>

    <footer>
        <p>&copy; 2024 Meu Portfólio. Todos os direitos reservados.</p>
    </footer>
    ```

2. **Adicione um Artigo Recente**

   - Dentro da seção de projetos, adicione mais um `<article>` para descrever um novo projeto ou trabalho recente.

3. **Melhore o Layout com CSS**

   - Aplique estilos básicos para melhorar a aparência da página.

---

### Exercícios Finais

1. **Altere a Navegação:** Inclua mais links de navegação no `<nav>`, como para redes sociais.
2. **Divida Conteúdos:** Crie mais seções e artigos para enriquecer o conteúdo principal da página.
3. **Estilize o Footer:** Melhore o rodapé com informações de contato e ícones de redes sociais.
