# Resumo AP1 - Desenvolvimento Web

## 1. Versionamento

- **Vantagens da utilização:** Permite o controle de versão, exibindo quem e quando fez as alterações no projeto. Além disso, permite a colaboração entre várias pessoas que trabalham no mesmo projeto, permitindo a edição de diferentes partes do código ao mesmo tempo.

## 2. Git e Github

- **Diferença:** O git é o sistema responsável pelo versionamento do projeto, já o github é onde o projeto fica armazenado. O git é utlizado para controlar as alterações do código, e o github é onde você armazena e compartilha o projeto.

## 3. Principais linguagens utilizadas na web

- **HTML**, CSS e JavaScript
    - **HTML** → Linguagem de marcação que estrutura as páginas.
    - **CSS** → Linguagem de estilização que dá a identidade visual dos elementos.
    - **JavaScript** → Linguagem de programação que permite dinamizar e interagir com os elementos.

## 4. Diferença entre tag, elemento e atributo

- **Tag** → Palavra-chave utilizada para marcar diferentes partes do conteúdo da página.
    - <html> <head> <body> <p> <img> <a>
- **Elemento** → É criado a partir de uma tag de abertura e fechamento, juntamente com o conteúdo entre elas.
    - <p> batata baroa </p>
- **Atributo** → É uma propriedade adicionada a uma tag para fornecer mais informações. Pode especificar cor, tamanho, link ou uma descrição alternativa para uma imagem.
    - href, src, id, class

## 5. Exemplo de HTML

<html lang=”pt-br”>

<head>

<meta charset = “UTF-8”> 

<title>Minha página</title>

</head>

<body>

<p>Estou por aqui!</p>  

</body>

</html>

## 6 e 7 Protocolos

- Pilha de protocolos → No contexto da internet, uma pilha de protocolos é um conjunto de protocolos que são usados para viabilizar a comunicação entre computadores e uma rede.
- Camadas de transporte → TCP e UDP
- **TCP**: Fornece confiabilidade, controle de fluxo e confirmação de recebimento de pacotes.
- **UDP:** Protocolo simples e rápido, não garante confiabilidade.

## 8. Arquiteturas

- **Cliente-servidor →** Nessa arquitetura, o servidor gerencia o acesso aos recursos e dados da rede, os clientes se conectam para obter acesso. O servidor armazena os dados, e executa as aplicações, enquanto o cliente recebe (e-mail, banco de dados)
- **************P2P →************** Nessa arquitetura, os clientes se conectam diretamente uns aos outros, sem necessidade de um servidor central. Cada computador atua nessa rede compartilhando recursos e dados (torrent)

## 9. Processos

- É um programa rodando em um nó da rede.

## 10. SSL ou TLS

- Security Socket Layer ou Transport Layer Security
- É uma camada de segurança responsável por proteger e criptografar as informações dos usuários de uma aplicação.
- Protocolos
    - HTTPS → Segurança da internet
    - TLS → E-mails

## 11. Hierarquia HTML

- Não há limite para filhos do nó root, mas é importante considerar que ter muitos elementos pode tornar o código difícil de ler e gerenciar.

## 12. Elementos HTML

- H1-H6 → Header 1 ao 6, utilizados para definir título.
- P → Elemento utilizado para definir um parágrafo.
- A → Elemento utilizado para linkar partes da página ou páginas externas.
- IMG → Elemento utilizado para adicionar imagens ao documento.
- List → Elemento utilizado para criar listas dentro do documento.

## 13. Form

- Elemento utilizado para capturar informações do usuário.
- Form → email, senha, dados, etc

## 14. A

- a → Elemento utilizado para navegar entre diferentes documentos HTML.

## 15. Formulários

- Form → define um formulário HTML
- Input → Cria uma caixa de texto, um campo de seleção ou um botão de múltipla escolha.
- Label → Define um rótulo para um elemento do formulário.
- Select → Cria uma lista de opções.
- Button → Cria um botão no formulário.

## 16. Atributos HTML

- Class → Define um atributo a mais de um elemento, criando uma classe.
- ID → Define um atributo único, que só pode ser usado por um elemento.
- Name → Define um nome para um elemento HTML. Usado geralmente em formulários.
- Hidden → Permite ocultar um elemento HTML, fazendo com que seja renderizado na página, mas de forma invisível ao usuário.
- Style → Atributo usado para definir estilos CSS para um elemento HTML.
- Title → Utilizado para fornecer informações adicionais sobre um elemento HTML, quando o usuário passa o cursor sobre ele.

## 17. Degradação graciosa

- É uma técnica de design para garantir que um site rode em qualquer dispositivo. Em dispositivos mais antigos ou que não suportam certas funcionalidades, o site deve se adaptar para manter o cliente. Fazendo com que seja acessível a todos.

## 18. Conceitos de CSS

- Regra → Composta por seletores e suas respectivas declarações.
- Seletor → Selecionar um ou mais elementos HTML para aplicar estilos.
- Declaração → Propriedade aplicada a um seletor, como cor de texto ou tamanho da fonte.

## 19. Seletores

- Seletor de classe → Utilizado para selecionar um ou mais elementos HTML.
    - <p class=”paragrafos”> batata </p>
- Seletor de ID → Utilizado para selecionar um elemento HTML.
    - <p id=”paragrafo1”> aipim </p>

## 20. CSS Box Model

- Margin → Utilizado para atribuir uma margem entre elementos.
- Padding → Utilizado para atribuir uma margem entre o elemento e sua borda.
- Border → Utilizado para atribuir uma borda a um elemento.

## 21. CSS Position

- Static → O elemento é exibido na ordem que aparece no HTML.
- Relative → O elemento é deslocado em relação a sua posição normal, podendo atribuir as propriedades top, bottom, left e right.
- Absolute → O elemento é posicionado em relação ao elemento pai mais próximo que tenha uma posição definida.
- Fixed → O elemento é posicionado em relação a janela do navegador. Ele permanece no mesmo lugar quando a página é rolada.

## 22. Blocos em JS

- Para definir blocos, se utiliza chaves.

## 23. Diferença de variáveis em JS

- Let → Declarada dentro de um escopo.
- Var → Desuso. Variável global.
- Const → Declarada para valores que não serão alterados futuramente.

## 24.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=
    , initial-scale=1.0">
    <title>Meu saco</title>
</head>
<body>
    <div class="meu_elemento">
        <span>oi</span>
        <span>tchau</span>
    </div>
    <script src="script.js"></script>
</body>
</html>
```

```jsx
function modificarSpan () {
    const spans = document.querySelectorAll(".meu_elemento");
    for (let i = 0; i < spans.length; i++){
        spans[i].style.backgroundColor = "red";
    }
}

window.onload = () => {
    modificarSpan()
    }
```

## 25.

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Exemplo de somatório</title>
  </head>
  <body>
    <label for="campo-numerico">Digite um número:</label>
    <input type="number" id="campo-numerico" name="campo-numerico">

    <br><br>

    <span id="meu_span">0</span>

    <script>
      const campoNumerico = document.getElementById('campo-numerico');
      const meuSpan = document.getElementById('meu_span');
      campoNumerico.addEventListener('change', function() {
        const valorAtual = Number(meuSpan.textContent);
        const novoValor = Number(campoNumerico.value);
        const soma = valorAtual + novoValor;
        meuSpan.textContent = soma;
      });
    </script>
  </body>
</html>
```