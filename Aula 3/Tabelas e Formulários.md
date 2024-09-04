# Tabelas e Formulários em HTML

## 1. Introdução às Tabelas

**Explicação:** Tabelas são usadas para organizar dados em linhas e colunas.

**Principais Tags:**

- **Tag `<table>`:** Define o início de uma tabela.
- **Tag `<tr>`:** Define uma linha da tabela.
- **Tag `<td>`:** Define uma célula de dados.
- **Tag `<th>`:** Define uma célula de cabeçalho.

**Exemplo:**

```html
<table border="1">
    <tr>
        <th>Nome</th>
        <th>Idade</th>
    </tr>
    <tr>
        <td>João</td>
        <td>10</td>
    </tr>
    <tr>
        <td>Maria</td>
        <td>11</td>
    </tr>
</table>
```

**Explicação:** Nesse exemplo, criamos uma tabela simples com duas colunas (Nome e Idade) e duas linhas de dados.

## 2. Estilizando Tabelas

**Explicação:** Podemos usar o atributo `style` para adicionar bordas, cores e espaçamento às tabelas.

**Exemplo:**

```html
<table style="border-collapse: collapse; width: 100%;">
    <tr style="background-color: #f2f2f2;">
        <th style="border: 1px solid #ddd; padding: 8px;">Nome</th>
        <th style="border: 1px solid #ddd; padding: 8px;">Idade</th>
    </tr>
    <tr>
        <td style="border: 1px solid #ddd; padding: 8px;">João</td>
        <td style="border: 1px solid #ddd; padding: 8px;">10</td>
    </tr>
    <tr style="background-color: #f2f2f2;">
        <td style="border: 1px solid #ddd; padding: 8px;">Maria</td>
        <td style="border: 1px solid #ddd; padding: 8px;">11</td>
    </tr>
</table>
```

## 3. Introdução aos Formulários

**Explicação:** Formulários permitem a coleta de informações dos usuários. Eles são usados em cadastros, pesquisas, entre outros.

**Principais Tags:**

- **Tag `<form>`:** Define o formulário.
- **Tag `<input>`:** Define campos de entrada.
- **Tag `<label>`:** Define rótulos para os campos.
- **Tag `<button>`:** Cria um botão, geralmente para enviar o formulário.

**Exemplo:**

```html
<form>
    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="nome"><br><br>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email"><br><br>

    <input type="submit" value="Enviar">
</form>
```

**Explicação:** Neste exemplo, criamos um formulário simples com campos de texto e e-mail, além de um botão para enviar.

## 4. Tipos de Campos de Entrada (`<input>`)

**Explicação:** Existem diferentes tipos de campos que podem ser usados para capturar diferentes tipos de dados.

**Exemplos:**

- **Campo de Texto:** `<input type="text">`
- **Campo de Senha:** `<input type="password">`
- **Campo de Email:** `<input type="email">`
- **Campo de Número:** `<input type="number">`
- **Botão de Rádio:** `<input type="radio">`
- **Checkbox:** `<input type="checkbox">`
- **Campo de Data:** `<input type="date">`

### **Atividade Prática**

1. Criar uma Tabela de Contatos

    - Crie uma tabela que lista o nome, idade, e telefone de três amigos.

    **Exemplo:**

    ```html
    <table style="width:100%; border-collapse: collapse;">
        <tr style="background-color: #ddd;">
            <th style="border: 1px solid black; padding: 8px;">Nome</th>
            <th style="border: 1px solid black; padding: 8px;">Idade</th>
            <th style="border: 1px solid black; padding: 8px;">Telefone</th>
        </tr>
        <tr>
            <td style="border: 1px solid black; padding: 8px;">Lucas</td>
            <td style="border: 1px solid black; padding: 8px;">12</td>
            <td style="border: 1px solid black; padding: 8px;">(51) 1234-5678</td>
        </tr>
        <tr style="background-color: #ddd;">
            <td style="border: 1px solid black; padding: 8px;">Ana</td>
            <td style="border: 1px solid black; padding: 8px;">11</td>
            <td style="border: 1px solid black; padding: 8px;">(51) 9876-5432</td>
        </tr>
        <tr>
            <td style="border: 1px solid black; padding: 8px;">Pedro</td>
            <td style="border: 1px solid black; padding: 8px;">13</td>
            <td style="border: 1px solid black; padding: 8px;">(51) 2468-1357</td>
        </tr>
    </table>
    ```

2. Criar um Formulário de Cadastro

    - Crie um formulário para um cadastro simples com os campos: nome, email, senha e um botão de envio.

    **Exemplo:**

    ```html
    <form style="max-width: 400px; margin: auto;">
        <label for="nome">Nome:</label><br>
        <input type="text" id="nome" name="nome" style="width: 100%;"><br><br>

        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" style="width: 100%;"><br><br>

        <label for="senha">Senha:</label><br>
        <input type="password" id="senha" name="senha" style="width: 100%;"><br><br>

        <button type="submit">Cadastrar</button>
    </form>
    ```

### Exercícios Finais

   1. **Adicione uma nova linha** na tabela de contatos com mais um amigo e seus dados.
   2. **Modifique o formulário de cadastro** para incluir um campo de número de telefone.
   3. **Experimente usar diferentes tipos de campos** no formulário, como radio buttons para escolher o gênero ou checkboxes para selecionar hobbies.
