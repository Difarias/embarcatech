# Programa Conversor de Unidades em Linguagem C

## Introdução

Este projeto foi desenvolvido como parte da residência em Sistemas Embarcados, Unidade 3: Tarefa - Depuração e Versionamento, com o objetivo de aprender e aplicar os conceitos de versionamento utilizando Git e GitHub. Essas ferramentas foram escolhidas por sua importância em permitir o gerenciamento eficiente de alterações no código, além de promover um ambiente colaborativo para o desenvolvimento de software. O programa implementa a conversão entre diferentes unidades de medida, dividindo o trabalho entre os integrantes do grupo para simular um fluxo colaborativo de desenvolvimento.

## Funcionalidades

O programa realiza as seguintes conversões de unidades:

- **Massa**: Conversão entre quilograma, grama e tonelada.
- **Volume**: Conversão entre litro, mililitro e metros cúbicos.
- **Temperatura**: Conversão entre Celsius, Fahrenheit e Kelvin.
- **Unidades de Área**: Conversão entre metro quadrado e centímetro quadrado.
- **Comprimento**: Conversão entre metro, centímetro e milímetro.
- **Potência**: Converte a potência em watts para hp

## Divisão de Tarefas

Cada integrante do grupo foi responsável por implementar um módulo do programa. A divisão foi feita da seguinte forma:

- **Ana Beatriz Silva Aragão**: Unidades de Área
- **Caique de Brito Freitas**: Unidades de Comprimento
- **Diego Farias de Freitas**: Unidades de Volume
- **Devid Henrique Pereira dos Santos**: Unidades de potência
- **Geovani da Silva Reis**: ""
- **Juan Pablo Azevedo Sousa**: Unidades de Massa
- **Renan dos Santos Lima**: Unidades de Temperatura

## Estrutura do Projeto

O repositório foi estruturado para facilitar o desenvolvimento colaborativo:

1. Cada desenvolvedor criou uma branch específica para seu módulo, adotando a seguinte convenção de nomenclatura: nome-funcionalidade.
2. Os commits foram realizados regularmente com mensagens descritivas.
3. Issues e labels foram utilizadas para acompanhar o progresso de cada módulo.
4. Pull requests foram criados e revisados pelo time antes de serem integrados ao branch principal.

## Pré-requisitos do Projeto

Para que o programa compile e execute sem problemas, você precisará ter instalado em sua máquina o compilador gcc e o make.

### Para Linux (Ubuntu)

Atualize os repositórios:
```bash
sudo apt update
```

Instale o GCC e Make:
```bash
sudo apt install build-essential
```

Verifique a instalação:

Para verificar o GCC:
```bash
gcc --version
```

Para verificar o Make:
```bash
make --version
```

### Para Windows

Baixe e instale o MinGW-w64:

Acesse [winlibs.com](https://winlibs.com/) e baixe a versão mais recente do GCC.

Extraia os arquivos:

Extraia o conteúdo para uma pasta, por exemplo, `C:\mingw64`.

Adicione o binário ao PATH:

O binário está localizado em `C:\mingw64\bin`. Adicione esse caminho à variável de ambiente PATH:
- Windows 10/11: Pesquise por "Variáveis de Ambiente" > Edite a variável PATH > Adicione o caminho.

Verifique a instalação:

No terminal do Windows (cmd ou PowerShell), digite:
```bash
gcc --version
make --version
```

## Instruções de Uso

Para utilizar o programa:

1. Clone o repositório em sua máquina local usando o comando:
   ```bash
   git clone https://github.com/caiquedebrito/embarcatech
   ```

2. Compile o program utilizando o make:
    ```bash
    make
    ```
    O comando acima criará um executável (programa.exe) na raiz do projeto

3. Execute o programa:
   ```bash
   ./programa.exe
   ```

4. Escolha o tipo de conversão desejada e siga as instruções exibidas na tela.

## Agradecimentos

Agradecemos ao Cepedi pela oportunidade de nos permitir iniciar essa experiência em grupo, proporcionando aprendizado e crescimento conjunto.

Esta atividade foi uma experiência enriquecedora que proporcionou um aprendizado prático e significativo sobre:

- Colaboração em equipe;
- Versionamento de código utilizando Git e GitHub;
- Resolução de conflitos e integração de funcionalidades.

Agradecemos também a todos os integrantes do grupo pelo empenho e dedicação ao longo do desenvolvimento do projeto.