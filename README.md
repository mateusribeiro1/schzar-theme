# Tema Schzar para Ghost

O tema Schzar é baseado no Headline, que é um tema oficial [Ghost](https://github.com/TryGhost/Ghost), o foco deste tema é notícia locais. Mas pode ser usado para diversos propósitos.
O Headline adapta-se ao seu conteúdo, apresentando os tópicos mais escritos ou possibilitando o controle sobre quais os tópicos serão exibidos com destaque na página inicial.


# Fork

A necessidade de criar um fork desse tema é devido a tradução para o português e também inclusão de outras funções, como botão de compartilhamento, inclusão de página de erro, entre outras necessidades.

# Demonstração do Tema

O tema ajustado estará implementado no site da [Schzar](https://www.schzar.com.br).

# Instruções de Instalação no Ghost CMS

1. [Baixar o tema](https://github.com/mateusribeiro1/Headline/archive/main.zip)
2. Após o download do arquivo, acesse a área administrativa do Ghost
3. Clique no símbolo da engrenagem e logo em seguida na opção 'Design'
4. Após abrir essa opção, selecione no canto inferior esquerdo a opção 'Change Theme'
5. Selecione a opção Upload Theme no canto superior direito e termine a instalação.
6. Faça os ajustes que forem necessários.

# Para desenvolvedores

O tema está sendo compilado utilizando o Gulp/PostCSS. Para editar o tema, você irá precisar do [Node](https://nodejs.org), [Yarn](https://yarnpkg.com/) e [Gulp](https://gulpjs.com) instalados.

Em Janeiro, a Ghost liberou uma ferramenta para auxiliar no processo de criação de temas. O artigo está [aqui](https://ghost.org/changelog/vscode-extension/). A ferramenta é para o VS Code e chama-se Ghost, para utilizá-la, use esse link: [Ghost para VS Code](https://marketplace.visualstudio.com/items?itemName=TryGhost.ghost&ref=ghost.org)

Após a instalação desses requisitos, acesso a pasta raíz. Esses são os comandos básicos:

```bash
# Instalar
yarn

# Compilar
yarn dev

```

Agora, você pode editar os arquivos em `/assets/css/`, que serão compilados e para a pasta `/assets/built/` automaticamente.

Para criar um aquivo em formato `zip`, utilize esse comando:

```bash
npm run zip
```
O Gulp fará o empacotamento e ajuste do código. O arquivo em formato zip é salvo na pasta `dist/schzar.zip`.
Você poderá baixar e instalar em seu site posteriormente.


## Copyright & License

Ressaltamos que este é um fork do tema fornecido pela [Ghost Foundation](https://ghost.org) e está publicado utilizando a licença [MIT](LICENSE).
Para acessar o tema original, fornecido pela Ghost, esse é o repositório: https://github.com/TryGhost/Headline
