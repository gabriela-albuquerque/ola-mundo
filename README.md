# Olá Mundo - Aplicação SPA em React com Roteamento

Este projeto foi desenvolvido durante um curso de React com o objetivo de aprofundar os conhecimentos em **Single Page Applications (SPA)** e **React Router**. A aplicação consiste em uma página inicial, uma página "Sobre Mim", páginas individuais para posts e uma página de erro personalizada.
O banner de apresentação pessoal e a página Sobre Mim ainda tem as informações do instrutor e, assim que produzir meus assets e texto, vou personalizar 😅 .

## Funcionalidades da Aplicação

### Página Inicial

- Um banner de apresentação pessoal.
- Navegação por meio de um menu fixo.
- Uma lista dinâmica de posts gerada a partir de um arquivo JSON.
- Rodapé presente em todas as páginas.

### Página "Sobre Mim"

- Descreve o histórico de desenvolvimento profissional.

### Páginas de Posts

- Cada post é renderizado dinamicamente com base em um arquivo JSON.
- Exibição de conteúdo com markdown utilizando a biblioteca **ReactMarkdown**.
- Lista de posts recomendados na página de cada post.

### Página 404

- Página personalizada para URLs incorretas ou erros no carregamento.
- Exibe uma mensagem amigável e oferece um botão para retornar à página anterior.

## O que Aprendi com Este Projeto

1. **Configuração e Utilização do React Router**

   - Criação de rotas com `BrowserRouter`, `Routes` e `Route`.
   - Configuração de rotas aninhadas com o componente `<Outlet>`.
   - Rotas dinâmicas utilizando parâmetros com `useParams`.

2. **Componentização**

   - Estruturação da aplicação com componentes reutilizáveis, como `Menu`, `Rodape`, `Banner` e `PostModelo`.

3. **Renderização Condicional**

   - Exibição de uma página personalizada caso um post não seja encontrado.

4. **Manipulação de Arquivos JSON**

   - Uso de um arquivo JSON para listar posts dinamicamente e filtrar posts recomendados.

5. **Estilização Modular**

   - Aplicação de estilos utilizando CSS Modules.

6. **Bibliotecas de Terceiros**

   - Integração com **ReactMarkdown** para renderizar conteúdo em markdown.

7. **UX Amigável**
   - Implementação de uma página 404 visualmente atraente e funcional.

## Tecnologias Utilizadas

- **React** para a construção da interface.
- **React Router** para o roteamento SPA.
- **CSS Modules** para estilização isolada.
- **ReactMarkdown** para renderização de markdown.
- **JSON** como fonte de dados.

## Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```

## Conclusão

Com este projeto, explorei os fundamentos do roteamento em React e desenvolvi uma aplicação funcional e escalável. Foi uma oportunidade de aplicar boas práticas de componentização e estruturação de projetos modernos em React.
