# Grid de Filmes de Animação

Este é um aplicativo desenvolvido com SwiftUI que exibe um grid de filmes de animação em um layout dinâmico. O projeto utiliza uma estrutura de grid horizontal, onde os filmes são exibidos com uma imagem e um título. A aplicação também implementa uma barra de navegação e um carrossel para mostrar filmes específicos de lançamentos.

## Funcionalidades

- Exibição de filmes em uma grade (grid) com imagens e títulos.
- Carrossel de lançamentos de filmes.
- Layout flexível e responsivo com uso de `LazyHGrid` para performance otimizada.
- Barra de navegação simples no topo.
- Interatividade com scroll e navegação entre diferentes seções de filmes.

## Tecnologias Utilizadas

- **SwiftUI**: Framework de UI da Apple utilizado para construção da interface.
- **Xcode**: IDE utilizada para desenvolvimento do projeto.
- **Swift**: Linguagem de programação para implementar a lógica de negócios.

## Estrutura do Projeto

O projeto está estruturado em componentes modulares para facilitar a manutenção e a expansão do app:

- **ContentView**: A tela principal do aplicativo, que organiza os componentes principais (como o grid de filmes e o carrossel de lançamentos).
- **FeaturesGrid**: Exibe um grid de filmes com título e imagem.
- **CarouselTabView**: Um carrossel de filmes lançados recentemente.
- **FilmeItemView**: Exibe a imagem e o título de cada filme individualmente em um item do grid.
- **Filme**: Estrutura que armazena dados relacionados ao filme, como título e imagem.

## Como Rodar o Projeto

1. **Clonar o repositório**:
   ```bash
   git clone https://github.com/Aysllan00/App_Swift_GridMovies.git

2. **Abrir o projeto no Xcode**:
  - Abra o arquivo App_SwiftUI.xcodeproj no Xcode.

4. **Executar o aplicativo**:
  - Selecione um simulador ou dispositivo físico.
  - Clique em Run (Cmd + R) para compilar e rodar o aplicativo.
