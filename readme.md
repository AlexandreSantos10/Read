# Quatro em Linha - Jogo em C

Este é um projeto desenvolvido em linguagem C que implementa o clássico jogo Quatro em Linha. O jogo pode ser jogado no modo Jogador vs. Jogador ou Jogador vs. Computador.

## Requisitos

Para compilar e executar o jogo, você precisará de um compilador C instalado no seu sistema. Recomendamos o `gcc`, disponível em sistemas Linux, macOS e Windows (via MinGW ou WSL).

## Compilação

Para compilar o código-fonte, abra um terminal na pasta do projeto e execute o seguinte comando:

```sh
gcc -o 4emlinha main.c -Wall -Wextra
```

- `main.c`: Arquivo principal do jogo.
- `-Wall -Wextra`: Ativa avisos do compilador para ajudar na detecção de erros.

## Execução

Após a compilação bem-sucedida, execute o jogo com o seguinte comando:

```sh
./4emlinha
```

No Windows, o comando será:

```sh
4emlinha.exe
```

## Funcionalidades

- **Modo Jogador vs. Jogador**: Dois jogadores se alternam para inserir peças no tabuleiro.
- **Modo Jogador vs. Computador**: O jogador enfrenta um oponente controlado pelo computador.
- **Detecção automática de vitória ou empate**.
- **Historico de partidas e leaderboard**.
- **Limpeza de partidas e leaderboard**.

## Estrutura do Projeto

```plaintext
📁 4emlinha/
├── bin/
│   ├── debug/
│   │   ├── 4emlinha.exe
│
├── obj/
│   ├── debug/
│   │   ├── main.o
│   │
│   ├── 4emlinha.cpd
│   ├── 4emlinha.depend
│   ├── historico_partidas.txt
│   ├── leaderboard.txt
│   ├── main.c
│   ├── main.exe
│   ├── main.o
│
├── README.md         # Manual de instalação e execução
```

## Observações

Se encontrar algum problema durante a compilação ou execução, verifique se todos os arquivos necessários estão na pasta correta e se o compilador está instalado corretamente.

Caso queira contribuir com melhorias, sinta-se à vontade para modificar o código e sugerir otimizações!

---

**Divirta-se jogando Quatro em Linha!** 🎮
