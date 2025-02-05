# Vellum Engine

Vellum Engine é um motor de jogo multiplataforma projetado para oferecer desempenho de ponta e flexibilidade para desenvolvedores de jogos. Com suporte para várias plataformas e uma ampla gama de recursos, o Vellum Engine é a escolha ideal para criar jogos de alta qualidade.

## Recursos

- **Multiplataforma**: Suporte para Windows, macOS, Linux, Android e iOS.
- **Gráficos Avançados**: Renderização de alta performance com suporte para DirectX, OpenGL, e Vulkan.
- **Física Realista**: Motor de física integrado para simulações realistas.
- **Audio Integrado**: Suporte para áudio 3D e efeitos sonoros.
- **Ferramentas de Desenvolvimento**: Editor de cenas, depurador e ferramentas de profiling.
- **Scriptable**: Suporte para scripts em Lua e Python.
- **Comunidade e Suporte**: Documentação abrangente e comunidade ativa de desenvolvedores.

## Instalação

### Pré-requisitos

- CMake 3.10 ou superior
- Compilador C++ (GCC, Clang, MSVC)
- Bibliotecas de desenvolvimento (OpenGL, Vulkan, SDL2)

### Compilando a partir do código-fonte

1. Clone o repositório do Vellum Engine:
    ```sh
    git clone https://github.com/seu_usuario/vellum-engine.git
    cd vellum-engine
    ```

2. Crie um diretório de build e navegue até ele:
    ```sh
    mkdir build
    cd build
    ```

3. Execute o CMake para configurar o projeto:
    ```sh
    cmake ..
    ```

4. Compile o projeto:
    ```sh
    make
    ```

## Uso

Para iniciar o editor de cenas do Vellum Engine, execute o seguinte comando no diretório de build:

```sh
./VellumEditor