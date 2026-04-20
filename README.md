# Jogo da Vida 

> 🎓 **Projeto Acadêmico**
> Repositório destinado aos projetos e atividades desenvolvidos para o curso de **Ciência da Computação da PUC**.

Implementação em **C++** do clássico autômato celular concebido pelo matemático John Horton Conway. 

Para garantir um código organizado e de fácil manutenção, a estrutura do projeto foi dividida utilizando o padrão arquitetural **MVC (Model-View-Controller)**:

* **Model (`_Model.cpp/h`)**: Gerencia o estado da grade e aplica as regras de sobrevivência e reprodução das células.
* **View (`_View.cpp/h`)**: Responsável por renderizar a simulação visualmente no terminal.
* **Controller (`_Controller.cpp/h`)**: Orquestra a execução do laço principal e a comunicação entre os dados e a interface.

## 🚀 Como Compilar e Executar

Abra o terminal na raiz do projeto e utilize um compilador C++ (como o `g++`):

```bash
# 1. Compilar os arquivos
g++ JVIDA2_ALGG_Main.cpp JVIDA2_ALGG_Model.cpp JVIDA2_ALGG_View.cpp JVIDA2_ALGG_Controller.cpp -o jogo_da_vida

# 2. Executar (Linux ou macOS)
./jogo_da_vida

# 2. Executar (Windows)
jogo_da_vida.exe
