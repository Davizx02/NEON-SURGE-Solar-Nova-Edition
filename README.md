# NEON SURGE — Solar & Nova Edition

## Desenvolvedor

**Davi Araujo**
**Turma:** 2º Ano TEC — Desenvolvimento de Sistemas
**Instituição:** SENAI
**Ano:** 2026

## Sobre o projeto

Jogo arcade retro-futurista de sobrevivência *top-down* onde o jogador enfrenta ondas infinitas de inimigos neon em um mapa infinito. Conta com sistema de tiro automático, mecânicas solares, supernovas, interface responsiva e efeitos sonoros sintéticos gerados dinamicamente no próprio navegador.

### Objetivo do Projeto

O objetivo foi analisar o código-fonte de um jogo existente, compreender seu funcionamento e realizar modificações utilizando conceitos de desenvolvimento de sistemas.

Após as alterações, o projeto foi publicado no GitHub e disponibilizado por meio do GitHub Pages.

## Tecnologias

* **HTML5:** Estruturação da página e elemento de renderização gráfica (`<canvas>`).
* **CSS3:** Estilização da interface (HUD), efeitos luminosos em neon e responsividade para dispositivos móveis.
* **JavaScript (ES6+):** Construção da lógica do jogo, física, colisão de objetos, controle de entradas e máquina de estados.
* **Canvas API:** Renderização gráfica 2D em tempo real, lógica do mapa e efeitos visuais de partículas.
* **Web Audio API:** Sintetização procedural de áudio (efeitos sonoros gerados por código, dispensando o uso de arquivos `.mp3` ou `.wav`).
* **GitHub:** Controle de versão e hospedagem do código-fonte.
* **GitHub Pages:** Publicação e hospedagem direta do jogo na web.

*Diferencial do projeto:* Funciona diretamente no navegador sem dependências ou bibliotecas externas e executa sons e gráficos avançados de forma leve e totalmente procedural.

## Instalação e Uso

Para jogar, basta clonar este repositório ou fazer o download do arquivo `index.html`, abri-lo em qualquer navegador web moderno e clicar em **Começar**. Também é possível jogar diretamente pelo link do GitHub Pages.

### Como jogar

#### Computador

| Ação | Controle |
| --- | --- |
| Mover | W, A, S, D ou setas |
| Mirar | Mouse (ou automático) |
| Impulso | Espaço |
| Pausar | P |

#### Celular

O jogo possui suporte a toque na tela: toque e arraste o dedo para controlar a movimentação da nave enquanto a mira e o ataque ocorrem automaticamente.

## Modificações realizadas

* **Inimigo do tipo Solar:** Adicionado o inimigo `solar`, uma entidade com padrão de disparo contínuo e raio de colisão expandido.
* **Coletável Onda Nova:** Introduzida a habilidade *Nova*, que gera uma explosão de área capaz de destruir inimigos e limpar projéteis da tela.
* **Efeitos de Disparo Solar:** Implementado visual de partículas alaranjadas e sistema de tiro com tema solar.
* **Sintetizador de Áudio Procedural:** Criados novos timbres e frequências na Web Audio API para os efeitos de ativação da *Nova* e ataques *Solares*.
* **Aprimoramento Visual:** Adicionadas variáveis de cor neon CSS para expandir o contraste e o dinamismo da interface.
