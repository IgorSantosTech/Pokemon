Pokemon Guesser é um projeto web desenvolvido como parte de um exercício acadêmico. O objetivo do jogo é que o usuário adivinhe o nome de um Pokémon com base em sua imagem obscurecida. Se a adivinhação estiver correta, a imagem do Pokémon será revelada, e detalhes adicionais sobre ele serão exibidos. O projeto utiliza HTML, CSS e JavaScript, consumindo a API pública de Pokémon para fornecer as imagens e informações necessárias.

1. Requisitos Funcionais:
Exibição de Pokémon Obscurecido: Ao carregar a página, um Pokémon aleatório deve ser mostrado com a imagem obscurecida.
Input do Usuário: O usuário deve poder digitar o nome do Pokémon que ele acredita ser o correto.
Validação da Resposta: O sistema deve verificar se o nome inserido pelo usuário corresponde ao Pokémon exibido.
Revelação da Imagem: Caso o usuário acerte o nome, a imagem deve ser revelada.
Exibição das Informações: Após a revelação da imagem, o sistema deve exibir informações adicionais sobre o Pokémon (como tipo, habilidades, etc.).
API de Consumo: O sistema deve consumir uma API pública de Pokémon para obter a imagem e as informações necessárias.
2. Requisitos Não-Funcionais:
Desempenho: A aplicação deve carregar rapidamente e a interação com a API deve ser feita de forma eficiente para minimizar o tempo de espera do usuário.
Compatibilidade: A aplicação deve ser compatível com os principais navegadores (Chrome, Firefox, Edge, Safari).
Responsividade: A interface deve ser responsiva, ajustando-se bem a diferentes tamanhos de tela, incluindo dispositivos móveis.
3. Requisitos de Interface de Usuário (UI):
Design Simples e Intuitivo: A tela deve ser limpa e intuitiva, com o campo de input destacado e fácil de encontrar.
Botão de Adivinhação: Um botão para confirmar a tentativa do usuário.
Feedback Visual: Caso o usuário erre, deve haver um feedback visual (como uma cor diferente ou uma mensagem de erro).
Estilo: O estilo deve ser consistente com o tema Pokémon, utilizando cores e fontes que remetem ao universo dos jogos.
4. Tecnologia:
HTML/CSS: Para estruturar e estilizar a interface.
JavaScript: Para gerenciar a lógica do jogo e a interação com a API.
API de Pokémon: Uma API pública que forneça as imagens e informações dos Pokémon (como a PokéAPI).