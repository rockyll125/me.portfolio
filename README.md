# Portfólio Acadêmico - Desenvolvimento de Sistemas

## Nome do Aluno
Pedro Henrique Tomaz

## Descrição do Portfólio
Este projeto consiste em um site de portfólio pessoal e acadêmico desenvolvido durante o curso técnico em Desenvolvimento de Sistemas. O site apresenta a seção de perfil profissional, uma listagem detalhada de projetos desenvolvidos, seção de habilidades técnicas e canais de contato, oferecendo uma interface limpa, responsiva e moderna com tema escuro (preto e roxo).

## Tecnologias Utilizadas
* **HTML5**: Estruturação semântica das páginas.
* **CSS3**: Estilização personalizada, variáveis globais, efeitos de hover e transições suaves.
* **Bootstrap 5 & Bootstrap Icons**: Grid responsivo, componentes de navegação, cards e ícones vetoriais.
* **JavaScript**: Animação de digitação (typing effect) no cabeçalho e Intersection Observer para animação dinâmica das barras de progresso de habilidades.
* **Git & GitHub / GitHub Pages**: Controle de versão e publicação online do site.

## Link do Site Publicado
https://rockyll125.github.io/me.portfolio/

## Explicação do Funcionamento do Projeto
O portfólio é estruturado em uma única página (Single Page Application) com navegação suave (smooth scroll) através de um menu superior fixo que se adapta ao rolar a página. A estrutura divide-se em:
1. **Início (Hero)**: Apresentação principal com efeito de texto animado e atalhos rápidos.
2. **Perfil (Sobre Mim)**: Informações biográficas e acadêmicas do estudante.
3. **Habilidades**: Exibição visual de tecnologias dominadas com indicadores percentuais.
4. **Projetos**: Cards interativos destacando os trabalhos práticos realizados.
5. **Contato**: Cartões interativos com links diretos para e-mail e redes sociais.

## Descrição do Recurso Novo Adicionado
Como recurso avançado além do padrão visto em sala, foi implementada uma **Seção de Habilidades Interativa com Barras de Progresso Animadas** combinada com um **Efeito de Digitação (Typing Effect)** na seção Hero e **detecção de rolagem (Intersection Observer)**. As barras de progresso preenchem-se suavemente de forma animada apenas quando o usuário rola a página até a seção de habilidades.

## Explicação de Como Esse Recurso Foi Implementado
* **Barras de Progresso e Intersection Observer**: Utilizou-se a API `IntersectionObserver` do JavaScript para monitorar quando o elemento `#habilidades` entra na tela do usuário. Assim que visível, um script lê o atributo `data-width` de cada barra e aplica a largura correspondente com uma transição suave em CSS (`transition: width 1.5s cubic-bezier(...)`).
* **Efeito de Digitação**: Uma função em JavaScript manipula a propriedade `textContent` de um elemento de texto de forma cíclica, apagando e escrevendo frases dinamicamente para dar dinamismo à apresentação inicial.
