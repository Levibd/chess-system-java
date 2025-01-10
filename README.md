
# Chess System Java ♟️

Este é um projeto desenvolvido como parte do curso do **Nelio Alves**, focado na criação de um sistema de xadrez utilizando **Java**. O objetivo principal foi aplicar conceitos de programação orientada a objetos (POO), como herança, polimorfismo, encapsulamento, e manipulação de matrizes, além de reforçar a lógica de programação e boas práticas de design de software.

---

## 📜 Descrição

O **Chess System Java** é uma aplicação baseada em console que simula um jogo de xadrez. A aplicação permite:  
- Configurar e visualizar um tabuleiro de xadrez.  
- Movimentar peças de acordo com as regras do jogo.  
- Detectar jogadas especiais, como **roque**, **promoção de peão** e **xeque**.  
- Gerenciar turnos e alternar entre os jogadores.  
- Identificar situações de **xeque-mate** e encerrar a partida.  

Este projeto foi desenvolvido como um estudo para reforçar conceitos de POO e estruturas de dados.

---

## 🛠️ Tecnologias Utilizadas

- **Java 17+**  
- Desenvolvimento baseado em **IDE Eclipse** (ou outra IDE, se aplicável).  

---

## 🛠️ Estrutura do Projeto

O projeto segue uma estrutura modular, com as principais classes organizadas em pacotes como:  
- **boardgame**: Classes responsáveis por abstrair o tabuleiro e as peças genéricas.  
- **chess**: Classes específicas das regras e peças do xadrez.  
- **application**: Classe principal com o programa executável.  

---

## 🚀 Como Executar

1. Clone este repositório:  
   ```bash
   git clone https://github.com/seu-usuario/chess-system-java.git
   cd chess-system-java
   ```

2. Importe o projeto para sua IDE preferida (Eclipse, IntelliJ, etc.).  

3. Compile e execute a aplicação:  
   - A aplicação será executada no console.  
   - Siga as instruções exibidas para movimentar peças e jogar a partida.  

---

## 🖼️ Demonstração

### Inicialização do Tabuleiro  
```
8  r n b q k b n r
7  p p p p p p p p
6  - - - - - - - -
5  - - - - - - - -
4  - - - - - - - -
3  - - - - - - - -
2  P P P P P P P P
1  R N B Q K B N R
   a b c d e f g h
```

### Movendo uma peça  
- Insira as coordenadas de origem e destino:  
  ```
  Origem: e2  
  Destino: e4  
  ```
- O tabuleiro será atualizado após cada jogada.  

---

## 📦 Funcionalidades em Destaque

- **Validação de Movimentos**: O sistema valida se a jogada é permitida antes de realizá-la.  
- **Tratamento de Exceções**: Feedback claro para entradas inválidas, como posições fora do tabuleiro ou jogadas ilegais.  
- **Jogadas Especiais**: Suporte a regras específicas do xadrez, como **roque** e **promoção de peão**.  

---

## 🎯 Aprendizados e Conceitos Aplicados

- Programação Orientada a Objetos: Herança, polimorfismo e encapsulamento.  
- Manipulação de matrizes para representar o tabuleiro.  
- Uso de exceções para tratar situações inválidas.  
- Design modular com separação de responsabilidades.  

---

## 🤝 Contribuição

Embora este projeto seja de caráter educacional, contribuições são bem-vindas! Caso deseje sugerir melhorias ou criar novas funcionalidades, sinta-se à vontade para abrir uma **Issue** ou enviar um **Pull Request**.

---

## 📝 Licença

Este projeto foi desenvolvido como parte de um curso e segue um objetivo educacional. Consulte o curso original do **Nelio Alves** para mais informações sobre o conteúdo abordado.

---

## 📫 Contato

- **Autor**: Levi Braga Dantas  
- **E-mail**: [levibdantas@gmail.com](mailto:seu-email@example.com)  
- **LinkedIn**: [https://www.linkedin.com/in/levi-dantas-a088a318b/](https://linkedin.com/in/seu-perfil)

---

Se precisar de ajustes, como adicionar mais detalhes ou destacar outros pontos, é só pedir! 😊
