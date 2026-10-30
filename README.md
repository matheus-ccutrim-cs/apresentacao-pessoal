# Apresentação pessoal — Matheus Costa Cutrim

Página de apresentação pessoal desenvolvida para o **Checkpoint 3**, com foco na aplicação de **CSS Grid, transições, transformações e animações CSS**. O projeto apresenta uma breve introdução sobre Matheus Costa Cutrim e seis interesses pessoais em uma interface responsiva com tema escuro.

## Objetivo

Aplicar os conceitos de HTML e CSS estudados em aula para construir uma página organizada, responsiva e com efeitos visuais. A atividade explora a diferença entre transições acionadas pela interação do usuário e uma animação executada automaticamente ao carregar a página.

## O que foi desenvolvido

- Cabeçalho com as iniciais **MC.** e um link para a seção de interesses.
- Seção de apresentação com nome, fotografia, breve descrição e botão de navegação interna.
- Grade com **seis cards**, cada um contendo uma ilustração, um título e um texto sobre o interesse apresentado.
- Layout com fundo escuro, detalhes em verde e organização feita com **CSS Grid, sem Flexbox**.
- Efeitos de interação nos cards e no botão.
- Animação de entrada da fotografia.
- Adaptação do layout para diferentes tamanhos de tela.
- Rodapé com identificação e referência à atividade.

### Interesses apresentados

| Interesse | Tema do card |
| --- | --- |
| Programação | Aprendizado e resolução de problemas por meio da tecnologia. |
| Comida | Descoberta de sabores e momentos compartilhados em uma refeição. |
| Futebol | Emoção das partidas e conexão entre as pessoas. |
| Corrida | Movimento, superação de desafios e renovação das energias. |
| Filmes | Histórias e diferentes perspectivas através do cinema. |
| Música | Companhia para diferentes momentos e estados de espírito. |

## Tecnologias e recursos

| Recurso | Aplicação no projeto |
| --- | --- |
| HTML5 | Estrutura da página, títulos, seções, imagens e links internos. |
| CSS3 | Cores, tipografia, espaçamentos, bordas e efeitos visuais. |
| CSS Grid | Organização do cabeçalho, da apresentação e dos cards. |
| `transition` | Suavização das mudanças de aparência e movimento. |
| `transform` | Deslocamento e aumento dos cards durante o hover. |
| `@keyframes` e `animation` | Animação automática de entrada da foto. |
| Media queries | Adaptação do layout à largura da tela. |
| SVG e JPG | Ilustrações dos interesses e fotografia de perfil. |

O projeto utiliza apenas **HTML e CSS**, sem JavaScript, frameworks ou dependências de instalação. As imagens são armazenadas no próprio repositório.

## Transições e animações

### Cards

Ao passar o mouse sobre um card, `translateY(-7px)` desloca o elemento para cima e `scale(1.02)` aumenta seu tamanho em 2%. A borda também muda de cor. A propriedade `transition` suaviza essas alterações durante **0,3 segundo**.

### Botão de navegação

O botão que leva à seção de interesses muda de cor ao receber o mouse ou foco visível pelo teclado. A transição da cor de fundo dura **0,3 segundo**.

### Fotografia

A animação `aparecer`, definida com `@keyframes`, é executada automaticamente durante **1 segundo**. A foto começa transparente e deslocada 18 pixels para baixo, terminando totalmente visível em sua posição original.

Os efeitos estão explicados com comentários no arquivo `style.css`.

## Responsividade e acessibilidade

- A grade possui **três colunas** em telas maiores, **duas colunas** em larguras de até 850 pixels e **uma coluna** em larguras de até 580 pixels.
- Em telas menores, a apresentação e a fotografia ficam organizadas em uma única coluna.
- As imagens possuem textos alternativos com o atributo `alt`.
- A página utiliza elementos semânticos, como `header`, `main`, `section`, `article`, `figure` e `footer`.
- A preferência `prefers-reduced-motion` desativa a animação e os movimentos para usuários que solicitam redução de movimento no sistema.
- Propriedades complementares e seus links de referência estão comentados no CSS.

## Estrutura do projeto

| Arquivo ou pasta | Responsabilidade |
| --- | --- |
| `index.html` | Conteúdo e estrutura da página. |
| `style.css` | Estilização, Grid, responsividade e animações. |
| `README.md` | Documentação do projeto. |
| `imagens/perfil.jpg` | Fotografia usada na apresentação. |
| `imagens/programacao.svg` | Ilustração do card de programação. |
| `imagens/comida.svg` | Ilustração do card de comida. |
| `imagens/futebol.svg` | Ilustração do card de futebol. |
| `imagens/corrida.svg` | Ilustração do card de corrida. |
| `imagens/filmes.svg` | Ilustração do card de filmes. |
| `imagens/musica.svg` | Ilustração do card de música. |

## Como executar localmente

1. Baixe o repositório e extraia os arquivos ou clone o projeto.
2. Abra o arquivo `index.html` em um navegador.
3. Navegue até a seção de interesses e passe o mouse sobre os cards para observar os efeitos.

Também é possível abrir a pasta no Visual Studio Code e utilizar a extensão Live Server. Essa extensão é opcional; não há necessidade de instalar pacotes ou executar comandos de build.

Mantenha `index.html` e `style.css` na raiz e preserve a pasta `imagens`, pois o HTML utiliza caminhos relativos para localizar esses arquivos.

## Publicação

O projeto foi preparado para hospedagem estática e publicação no **Vercel**, a partir do repositório do GitHub. Não possui etapa de compilação ou variáveis de ambiente.

- **Repositório:** [apresentacao-pessoal](https://github.com/matheus-ccutrim-cs/apresentacao-pessoal)
- **Página no Vercel:** publicação pendente.

## Identificação acadêmica

- **Aluno:** Matheus Costa Cutrim
- **Curso:** Ciência da Computação
- **Instituição:** FIAP
- **Atividade:** Checkpoint 3 — Página de apresentação pessoal com animações CSS

## Referências de consulta

- [MDN — CSS Grid](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_grid_layout)
- [MDN — transition](https://developer.mozilla.org/pt-BR/docs/Web/CSS/transition)
- [MDN — transform](https://developer.mozilla.org/pt-BR/docs/Web/CSS/transform)
- [MDN — @keyframes](https://developer.mozilla.org/pt-BR/docs/Web/CSS/@keyframes)
- [MDN — animation](https://developer.mozilla.org/pt-BR/docs/Web/CSS/animation)

Projeto acadêmico voltado à prática de estruturação de páginas e efeitos visuais com HTML e CSS.
