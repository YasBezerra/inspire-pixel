
# Inspire Pixel

O Inspire é um projeto desenvolvido durante o desafio do curso Vai na Web, que funciona como uma galeria de imagens interativa. Cada imagem pode receber likes, tornando a experiência do usuário mais dinâmica e engajante. O projeto também utiliza uma API para buscar e exibir imagens, permitindo que o conteúdo seja carregado de forma dinâmica com base no tema escolhido
## Stack utilizada

**Front-end:** JavaScript (ES6+), SCSS, Vue.js 3 e API externa – para carregamento dinâmico de imagens.



## Funcionalidades

* Carregamento de imagens de uma API externa.

* Sistema de likes para cada imagem, atualizando o contador de forma interativa.

* Hover nos cards para destacar o botão de like, que fica sobreposto à imagem.

* Responsividade para diferentes tamanhos de tela usando SCSS.

## Aprendizados

Durante o desenvolvimento deste projeto, aprofundei meus conhecimentos em:

* Posicionamento avançado com CSS (absolute, relative, layering)

* Uso de SCSS para modularizar estilos

* Criação de componentes visuais simples e elegantes

* Melhor compreensão da estrutura e fluxo do Vue 3

* Controle de eventos de usuário (@click) e atualização de estado

* Entender o fluxo de dados entre componentes e props no Vue 3.

* Aprender a manipular o estado de componentes com ref e eventos.

* Melhorar a experiência do usuário com efeitos de hover e UI interativa.

## Maiores desafios

Os principais desafios que enfrentei foram:

* Trabalhar com props e comunicação entre componentes no Vue 3.

* Implementar a lógica de likes de forma reativa e eficiente.

* Ajustar a sobreposição do botão sobre a imagem, mantendo responsividade.

* Integrar e consumir a API externa corretamente, tratando carregamento e erros.

* Garantir a responsividade do layout para dispositivos de diferentes tamanhos.

## Como enfrentei esses desafios

Para superar essas dificuldades, utilizei as seguintes estratégias:

Como enfrentei os desafios

* Comunicação entre componentes (props): Estudei como passar dados e emitir eventos no Vue 3, criando componentes organizados e reutilizáveis.

* Lógica de likes reativa: Usei ref para armazenar o estado de likes e atualizei dinamicamente cada card, garantindo contagem independente para cada imagem.

* Sobreposição do botão sobre a imagem: Ajustei o posicionamento com CSS (position: absolute e z-index), mantendo o botão visível e funcional.

* Integração com API externa: Implementei fetch assíncrono, tratei erros e carregamento de dados para exibir imagens corretamente sem travar a aplicação.

* Responsividade do layout: Usei media queries e unidades relativas (%, vw, vh) para garantir que a galeria ficasse organizada e funcional em qualquer dispositivo.


## Screenshots

<details>
  <summary>Visualizar imagens do Inspire</summary>

  ![iPhone Inspire](https://github.com/user-attachments/assets/c64d9070-acc7-46b6-a486-6980d785ee33)
  
  ![Captura de Tela](https://github.com/user-attachments/assets/c535e1fc-7a8c-441c-8ee3-7a85415549d7)

</details>

## Autores

- [@YasBezerra](https://www.github.com/YasBezerra)

