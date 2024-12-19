# 🕹️ Jogo 2D: Movimentação e Colisões 🚀

Bem-vindo ao **Jogo 2D: Movimentação e Colisões**, um projeto interativo desenvolvido em **C++** com a biblioteca **SFML**! Explore o mundo 2D, controle seu personagem e interaja com inimigos enquanto testa habilidades de movimentação e colisões.

---

## 📚 **Descrição do Jogo**

Este é um jogo 2D simples e divertido que demonstra conceitos básicos de:
- **Movimentação do Jogador**: Controle seu personagem usando as teclas de direção.
- **Colisão com Inimigos**: Os inimigos se movem automaticamente e você deve interagir com eles.
- **Pontuação Dinâmica**: Cada colisão aumenta sua pontuação, exibida no console.

---

## 🎮 **Como Jogar**

### **1. Objetivo**
- Mova seu jogador (um bloco azul) pela tela e colida com os inimigos (blocos coloridos).
- A cada colisão, sua pontuação aumenta.

### **2. Controles**
- Use as teclas **W, A, S, D** para movimentar o jogador:
  - **W**: Move para cima.
  - **A**: Move para a esquerda.
  - **S**: Move para baixo.
  - **D**: Move para a direita.

---

## 🛠️ **Requisitos**

Para executar o jogo, você precisará de:
- **SFML** instalada no sistema (versão 2.6.2 ou superior).
- Um compilador compatível com **C++20** (ex.: GCC, Clang ou MSVC).

---

## 🚀 **Como Executar**

### **1. Configuração do Ambiente**
Certifique-se de que a biblioteca SFML está configurada corretamente:
- As DLLs da SFML devem estar na mesma pasta que o executável ou no `PATH` do sistema.

### **2. Compilação**
1. Compile o código usando o **CMake**:
   ```bash
   cmake -S . -B build
   cmake --build build
   ```
2. Navegue até a pasta `build` e localize o executável do jogo.

### **3. Executando o Jogo**
Execute o jogo diretamente pelo terminal:
```bash
./jogo2D
```
No Windows:
```cmd
jogo2D.exe
```

---

## 📦 **Estrutura do Projeto**

- **`main.cpp`**: Ponto de entrada do jogo.
- **`Engine.cpp/h`**: Gerencia a janela, eventos, e renderização.
- **`GameObject.cpp/h`**: Representa os objetos (jogador e inimigos).
- **`CMakeLists.txt`**: Configuração para a compilação com CMake.

---

## ✨ **Destaques**

1. **Jogabilidade Simples e Intuitiva**:
   - Controle suave do jogador com as teclas **W, A, S, D**.
   - Movimento automático de inimigos para maior dinamismo.

2. **Pontuação**:
   - Cada colisão adiciona 10 pontos à sua pontuação, exibida no console.

3. **Extensibilidade**:
   - Fácil de expandir com novos inimigos, obstáculos e animações.

---

## 🛠️ **Como Expandir**

1. **Adicione Obstáculos**:
   - Insira objetos fixos que dificultem a movimentação.

2. **Desenvolva um Sistema de Níveis**:
   - Aumente a velocidade dos inimigos conforme a pontuação cresce.

3. **Implemente Gráficos Avançados**:
   - Substitua os retângulos por sprites ou animações.

---

## 📄 **Licença**

Este projeto está licenciado sob a licença MIT. Use, modifique e compartilhe à vontade!

---

🎮 **Divirta-se explorando o mundo 2D!** Se tiver dúvidas ou sugestões, entre em contato. 🚀
```

1. **Estrutura Clara**:
   - Dividido em seções como descrição, controles e requisitos.
2. **Manual de Jogabilidade**:
   - Instruções detalhadas e fáceis de seguir.
3. **Destaques do Projeto**:
   - Mostra o que torna o jogo interessante e extensível.

Se precisar de mais alterações ou adaptações, é só avisar! 😊
