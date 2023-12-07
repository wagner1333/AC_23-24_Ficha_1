# Arquitetura de Computadores - Ficha 1

## Informação do aluno

    Nome: Wagner 

Escreve as respostas dentro dos blocos correspondentes.
Substitui as reticências pelo que é pedido em cada pergunta.
Não desformates o documento.

### P1. Identifica e descreve os principais componentes de um processador. Fornece uma breve explicação da função de cada componente

- Lista os componentes principais de um processador.
- Para cada componente, descreve o seu papel e função no processador.
- Considera componentes como unidade lógica aritmética (ALU), unidade de controlo (UC), registos internos, memória e interfaces de entrada/saída (I/O).

P1 - Resposta:
    1: Unidade de Controle
    Unidade Lógica e Aritmética 
    Registradores
    Unidade de Cache
    Unidade de Ponto Flutuante
    Controladores de Interrupção e Exceção
    Barramentos
    Decodificador de Instruções

2: Unidade de Controle (UC):

    Função: Coordena e controla as operações dentro do processador. Ela busca instruções na memória, decodifica-as e executa os sinais de controle necessários para realizar as operações.
    Unidade Lógica e Aritmética (ULA):
    
    Função: Realiza operações lógicas (como AND, OR, NOT) e aritméticas (como adição, subtração, multiplicação, divisão) nos dados. É responsável por executar cálculos e operações fundamentais.
    Registradores:
    
    Função: Armazenam temporariamente dados, endereços de memória e informações cruciais para as operações da CPU. Os registradores são de alta velocidade e são usados para armazenamento temporário de dados durante o processamento.
    Unidade de Cache:
    
    Função: Armazena dados frequentemente usados para reduzir o tempo de acesso à memória principal. Ele fornece dados rapidamente para a CPU, ajudando a acelerar o processamento ao armazenar cópias das informações mais utilizadas.
    Unidade de Ponto Flutuante (FPU):
    
    Função: Realiza operações matemáticas complexas envolvendo números decimais (ponto flutuante). Essa unidade é essencial para cálculos científicos, gráficos 3D, engenharia e outras tarefas que requerem alta precisão em cálculos de ponto flutuante.
    Controladores de Interrupção e Exceção:
    
    Função: Gerenciam interrupções externas, exceções e erros durante a execução do programa. Eles garantem que o processador possa lidar com eventos inesperados sem comprometer a integridade dos dados ou do sistema.
    Barramentos:
    
    Função: Permitem a transferência de dados e sinais entre os vários componentes do computador, como CPU, memória, periféricos e outros dispositivos. Existem barramentos para dados, endereços e controle, facilitando a comunicação dentro do sistema.
    Decodificador de Instruções:

Função: Interpreta as instruções recuperadas da memória. Ele traduz essas instruções em sinais de controle compreensíveis para a CPU, indicando quais operações devem ser realizadas e como devem ser executadas.

3: Unidade Lógica Aritmética (ALU):

    Função: Realiza operações lógicas (como AND, OR, NOT) e operações aritméticas (como adição, subtração, multiplicação, divisão) nos dados. A ALU executa cálculos e manipulações básicas dos dados.
    Unidade de Controle (UC):
    
    Função: Controla o fluxo de dados dentro do processador. Ela gerencia a execução das instruções, coordenando a busca, decodificação e execução das operações.
    Registradores Internos:
    
    Função: Armazenam temporariamente dados, endereços de memória e outras informações essenciais para as operações da CPU. São de alta velocidade e são usados para armazenamento temporário durante o processamento.
    Memória:
    
    Função: Armazena dados e instruções que serão processados pela CPU. Existem vários níveis de memória, incluindo a memória cache (mencionada anteriormente), memória RAM e memória de armazenamento de longo prazo, como discos rígidos ou SSDs.
    Interfaces de Entrada/Saída (I/O):
    
    Função: Facilitam a comunicação entre a CPU e dispositivos externos, como teclado, mouse, monitor, impressora, disco rígido, USB, etc. Essas interfaces permitem a transferência de dados entre a CPU e os periféricos conectados ao computador.
    
    ### P2. Compara as arquiteturas de Von Neumann e Harvard em termos de características e principais diferenças
    
    - Lista as principais características da arquitetura Von Neumann.
    - Lista as principais características da arquitetura de Harvard.
    - Explica as principais diferenças entre as duas arquiteturas, particularmente na organização da memória, busca de instruções e separação de dados.
    - Fornece exemplos de sistemas de computação que usam cada arquitetura.

P2 - Resposta:

    1: Unidade Central de Processamento 
    Memória Única e Compartilhada
    Bus de Dados e de Endereços
    Sequência Controlada de Instruções
    Execução Programada
    Armazenamento de Programas e Dados no Mesmo Espaço de Memória
    Arquitetura de Máquina de Propósito Geral
    Conceito de "Stored Program"
    
    2: Memória Separada para Instruções e Dados
    Buses de Acesso Diferentes
    Acesso Paralelo à Memória
    Pipeline Aprimorado
    Programação Restrita em Cenários Específicos
    Maior Potencial de Desempenho
    Complexidade Adicional no Projeto

3: 

### P3. Descreve o ciclo *fetch-decode-execute* num processador, detalhando cada etapa e explicando a sua importância na execução de programas de computador

- Fornece uma explicação detalhada da fase de busca de instrução, incluindo o que ela envolve e por que é importante na operação do processador.
- Explica a fase de descodificação e o seu papel na interpretação das instruções de execução.
- Descreve a fase de execução, destacando a execução propriamente dita das instruções e quaisquer interações com dados.
- Conclui explicando a ordem destas fases e como elas garantem a execução adequada dos programas de computador.
- Usa um diagrama para ilustrar o ciclo.

P3 - Resposta:

    1 - 
    A fase de busca de instrução é vital para a CPU. Ela busca a próxima instrução na memória, decodifica-a e garante que as operações sejam executadas na ordem correta. Isso mantém a CPU ocupada, sincronizada e ajuda no desempenho geral do sistema.
    2 - 
    A fase de decodificação segue a busca de instruções, interpretando o código binário para identificar a operação a ser realizada, os operandos envolvidos e preparando a CPU para executar a instrução. Garante que a CPU compreenda corretamente a instrução e a execute de acordo com a intenção do programa.
    3 - 
    Na fase de execução, a CPU realiza as operações das instruções usando as unidades funcionais e os dados preparados. Isso inclui cálculos, manipulação de dados e acesso à memória, se necessário, resultando na atualização dos registros da CPU e na obtenção de resultados para instruções subsequentes.
    4 - Busca: Começa com a obtenção da próxima instrução na memória. Isso garante que o processador sempre tenha uma instrução pronta para execução, mantendo a CPU ocupada e o fluxo do programa contínuo.
    
    Decodificação: Após a busca, a CPU interpreta a instrução, identifica a operação a ser realizada e prepara os recursos necessários. Isso é crucial para garantir que a CPU compreenda corretamente o que precisa ser feito.
    
    Execução: Aqui, a CPU de fato executa a operação especificada pela instrução, usando as unidades funcionais e manipulando os dados conforme necessário. Isso resulta na atualização dos registros e possivelmente na memória, preparando o terreno para a próxima instrução.
    
    Essa sequência é vital para a execução adequada dos programas porque garante:
    
    Ordem correta: Assegura que as instruções sejam executadas na sequência correta, mantendo a lógica do programa.
    
    Interpretação precisa: Cada fase prepara o terreno para a seguinte, garantindo que a CPU entenda corretamente o que cada instrução requer.
    
    Utilização eficiente dos recursos: Ao manter a CPU ocupada com instruções prontas para execução, otimiza-se o desempenho do sistema.
    5 - Fase de Busca: O PC (Contador de Programa) aponta para a próxima instrução na memória. A instrução é buscada na memória e trazida para a CPU.
    
    Decodificação: A instrução é interpretada e decodificada para determinar a operação a ser realizada e os recursos necessários.
    
    Execução: A operação é realizada utilizando as unidades funcionais e os operandos, resultando na atualização de registros e possivelmente da memória.

