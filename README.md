# Interface de Matrícula

Este projeto é uma **interface de matrícula online** desenvolvida para auxiliar instituições de ensino no processo de inscrição de novos estudantes. A aplicação apresenta uma interface dinâmica e intuitiva, permitindo que os usuários escolham cursos, vejam ofertas e avancem nas etapas de matrícula.

## Funcionalidades

- **Seleção de Cursos**: Exibição de cursos disponíveis com base na cidade e forma de ingresso.
- **Ofertas Dinâmicas**: Geração de cards com informações detalhadas das ofertas, incluindo valores promocionais, turno, campus e período letivo.
- **Envio de Interesse**: Integração com API para registrar o interesse do usuário em uma oferta específica.
- **Navegação Multietapas**: Estrutura para guiar o usuário por diferentes etapas do processo de matrícula.
- **Informações Adicionais**: Exibição de vídeos e textos descritivos sobre os cursos, quando disponíveis.

## Tecnologias Utilizadas

- **Frontend**: 
  - HTML, CSS, JavaScript
  - Framework CSS (TailwindCSS, baseado nos estilos vistos)
- **Backend**: API de suporte para dados dinâmicos (ofertas, cursos, interesse).
- **Hospedagem**: Vercel, para deploy e disponibilidade do projeto.

## Estrutura do Projeto

### Páginas Principais

1. **Formulários**: Interface para seleção de curso e exibição de ofertas.
2. **Cards Dinâmicos**: Componentes que mostram informações detalhadas de cada curso e oferta.

### Funcionalidades do Código

- **chamarApiCursos()**: Obtém dados da API sobre os cursos e preenche o dropdown de seleção.
- **criarCards(oferta, uidOferta)**: Gera dinamicamente cards HTML para exibir as ofertas.
- **Envio de Dados**: Função para registrar a escolha do usuário via uma API REST.
- **Controle de Estados**: Atualização da interface ao selecionar diferentes cursos.

## Configuração e Uso

### Pré-requisitos

- Navegador moderno compatível com ES6+.
- Configuração da API (links fornecidos no código).

### Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/victor-feitosaa/interface-de-matricula.git
