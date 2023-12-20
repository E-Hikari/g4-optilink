# Documentação de Testes de Usabilidade da Aplicação Optilink

## 1. Visão Geral dos Testes
   - **Objetivo**: Validar a eficiência, precisão e usabilidade das funcionalidades da aplicação Optilink.
   - **Escopo**: Testes cobrirão a interação com as principais telas: Alocação, Técnicos e Demandas, desenvolvidas até o momento dos testes.
   - **Metodologia**: Foram desenvolvidos 3 enunciados de testes, onde o usuário deve passar em cada para concluir os testes.

        1. **Primeiro Enunciado:** Suponha que você é o coordenador encarregado de cadastrar os técnicos disponíveis no sistema de alocação. Sua tarefa é inserir esses técnicos através de um arquivo CSV (que já está pronto, preparado previamente por você) no sistema e, em seguida, verificar se os dados apareceram na tabela.
        2. **Segundo Enunciado:** Suponha que você é o coordenador e agora está encarregado de cadastrar as demandas de serviços de Curitiba-PR no sistema. Sua tarefa é inserir as demandas através de um arquivo CSV (que já está pronto, preparado previamente por você) no sistema e, em seguida, verificar se o cadastro foi realizado e aparece na tela.
        3. **Terceiro Enunciado:** Suponha que você é o coordenador e agora está encarregado de fazer a alocação de técnicos, sua tarefa é rodar o algorítmo e ver o resultado das alocações no Mapa e na Tabela.

## 2. Preparação
   - **Ambiente de Teste**: Os testes foram realizados no Inteli (Instituto de Tecnologia e Liderança).
   - **Ferramentas de Teste**: Utilizamos os computadores dos desenvolvedores da aplicação para realizar os testes.
   - **Perfil dos Testadores**: Os testadores eram alunos, professores ou funcionários do RH, d0 Inteli, que têm experiência ou trabalham com algum tipo de Sistema de Alocação.


## 3. Execução dos Testes
   - **Procedimento de Teste**: Detalhamento passo a passo de como os testes foram realizados, seguindo a sequência das funcionalidades da aplicação.

### 3.1 Técnicos
   - **Encontrar a página de Técnicos**: Verificação se a tela de Técnicos é simples e rápida de ser encontrada.
   - **Teste de Importação de Técnicos**: Avaliação do processo de encontrar e utilizar o botão de `Importar` para inserir o arquivo CSV.
   - **Teste de Visualização de Dados dos Técnicos**: Análise da exibição correta e da funcionalidade de navegação na tabela de técnicos.

### 3.2 Demanda
   - **Encontrar a página de Demandas**: Verificação da facilidade e rapidez em encontrar a tela de Demandas.
   - **Teste de Importação de Demandas**: Teste do processo de localizar e usar o botão `Importar` para inserir o arquivo CSV.
   - **Teste de Visualização das Demandas Salvas**: Verificação da precisão na exibição do Estado, Município e data de inserção das demandas inseridas.


### 3.3 Dashboard
   - **Encontrar a página de Dashboard**: Verificação da facilidade e rapidez em encontrar a tela do Dashboard.
   - **Teste de Utilização do Algoritmo**: Análise do processo de localizar e apertar no botão `Rodar o algoritmo`, selecionar os *inputs* corretos e apertar no botão `Calcular Alocação`.
   - **Teste de Visualização no Mapa**: Verificação da interatividade do mapa, após o resultado do algoritmo, e da exibição correta dos dados.
   - **Teste de Visualização na Tabela**: Análise da funcionalidade da tabela, incluindo a navegação entre páginas e a exportação de dados.


## 4. Critérios de Avaliação
   - **Eficiência**: Tempo necessário para completar tarefas específicas.
   - **Precisão**: Corretude dos dados apresentados e resultados do algoritmo.
    - **Entedimento do Usuário**: : Análise da facilidade com que os usuários entendem o sistema.
   - **Satisfação do Usuário**: Feedback qualitativo dos testadores sobre a experiência do usuário.

## 5. Coleta de Dados
   - **Métodos de Coleta**: Durante os testes, os desenvolvedores da aplicação registraram detalhadamente todo o processo de teste de usabilidade, documentando dificuldades encontradas, comentários e feedbacks dos usuários. Ao final, foram solicitadas recomendações e sugestões.

## 6. Resultados dos Testes

   - **1° teste**: 
        - **Sobre o Testador:**
            - **Nome:** Ana Carolina Martire.
            - **Descrição do testado**: Aluna de Sistemas de Informação no Inteli e, atualmente, ocupa o cargo de Secretária na Central Estudantil do Inteli. Encarregada do projeto de alocação de apadrinhamento de veteranos para calouros no ano de 2024.
            - **Persona:** Coordenadora.

        - **Resultado do 1° teste:** Conseguiu cumprir todas as etapas com dificuldade.
            - Encontrou dificuldade ao localizar a página de técnicos, não compreendeu onde deveria clicar para mudar de página.
            - Na página de técnicos, encontrou facilmente o botão de importação e teve sucesso na operação.
            - Conseguiu importar o arquivo correto com êxito.
            - Na etapa de visualização na tabela, enfrentou dificuldades para compreender os dados.

        - **Resultado do 2° teste:** Conseguiu cumprir todas as etapas com facilidade.
            - Localizou a página de demandas com facilidade, uma vez que era semelhante à página de técnicos, e ela já havia compreendido o processo.
            - Na página de demandas, encontrou facilmente o botão de importação e teve sucesso na operação.
            - Conseguiu importar o arquivo correto com êxito.
            - Na etapa de visualização na tabela, conseguiu entender a tabela com facilidade.

        - **Resultado do 3° teste:** Conseguiu cumprir todas as etapas com sucesso e pouca dificuldade.
            - Localizou a página do Dashboard com facilidade, dado sua semelhança com as páginas de técnicos e demandas, e sua compreensão prévia do processo.
            - Na página de demandas, encontrou facilmente o botão para rodar o algoritmo.
            - Teve dificuldade em compreender qual data selecionar na etapa de selecionar os *inputs*.
            - Entendeu com facilidade como calcular a alocação ideal através do algoritmo, através do botão "Calcular a alocação".
            - Conseguiu visualizar o resultado do algoritmo no mapa com facilidade.
            - Encontrou um pouco de dificuldade ao mudar para a guia da Tabela.
            - Na guia da Tabela, conseguiu visualizar e percorrer a tabela com facilidade.

        - **Comentários**: Após os testes, comentou que no ínicio estava com a sensação de *perdida* no site. Pois, não sabia em que página ela estava no momento de inicialização.
        


   - **2° teste**: 
        - **Sobre o Testador:**
            - **Nome:** Andre Leal.
            - **Descrição do testado**: Técnico do laboratório do Inteli.
            - **Persona:** Coordenador.

        - **Resultado do 1° teste:** Conseguiu cumprir todas as etapas com sucesso e sem dificuldades.
            
            - Na página de técnicos, encontrou facilmente o botão de importação e teve sucesso na operação.
            - Conseguiu importar o arquivo correto com êxito.
            - Conseguiu visualizar os dados na tabela com facilidade.
            

        - **Resultado do 2° teste:** Conseguiu cumprir todas as etapas com facilidade.
            - Conseguiu achar com facilidade a guia de Demandas.
            - Na página de Demandas, encontrou facilmente o botão de importação e teve sucesso na operação.
            - Conseguiu importar o arquivo correto com êxito.
            - Na etapa de visualização na tabela, conseguiu entender a tabela com facilidade.

        - **Resultado do 3° teste:** Conseguiu cumprir todas as etapas com sucesso e pouca dificuldade.
            - Localizou a página do Dashboard com facilidade.
            - Na página de demandas, encontrou com facilidade o botão para rodar o algoritmo.
            - Entendeu com facilidade como calcular a alocação ideal através do algoritmo, através do botão "Calcular Alocação".
            - Conseguiu visualizar o resultado do algoritmo no mapa com facilidade.
            - Encontrou um pouco de dificuldade de entender e percorrer pela tabela de alocação.

   - **3° teste**: 
        - **Sobre o Testador:**
            - **Nome:** Lucas Henrique Sales.
            - **Descrição do testador**: Aluno de Engenharia da Computação no Inteli. Ocupa o cargo de vice-presidente na Inteli Jr. Responsável por fazer um sistema de alocações de pessoas para montar equipes de projetos.
            - **Persona:** Coordenador.

        - **Resultado do 1° teste:** Conseguiu cumprir todas as etapas com sucesso e facilidade.
            - Demonstrou entendimento da tarefa, encontrando a tela de técnicos com facilidade.
            - Intuitivamente, clicou no botão de importar sem dificuldades.
            - Inseriu o arquivo .CSV indicado com êxito.
            - Entendeu como a tabela funcionava e como percorre-la.

        - **Resultado do 2° teste:** Conseguiu cumprir todas as etapas com sucesso.
            - Acessou a página de demanda com bastante facilidade, já que era semelhante à página de técnicos.
            - Intuitivamente, clicou no botão de importar sem dificuldades.
            - Inseriu o arquivo .TXT das demandas de Curitiba com êxito;
            - Ficou confuso, inicialmente, em como a tabela funcionava, porém rapidamente começou a entender.
        - **Resultado do 3° teste:** Conseguiu cumprir todas as etapas com sucesso com um nível mais alto de dificuldade.
            - Teve dificuldades para saber onde rodar o algoritmo. 
            - Encontrou a opção na página de Dashboard.
            - Após entrar no Dashboard, rapidamente entendeu como rodar o o algorimo.
            - Apertou o botão e selecionou os *inputs* com facilidade e rapidez.
            - Verificou o resultado da alocação no mapa e na tabela com facilidade.
        - **Feedbacks:** O usuário sugeriu a inclusão de uma página na aplicação que permitisse o fácil acesso aos algoritmos previamente executados. Essa funcionalidade facilitaria a revisitação dos resultados e dos dados utilizados sem a necessidade de procurar e importar os arquivos novamente  para rodar na aplicação.

   - **4° teste**: 

        - **Sobre o Testador:**
             - **Nome:** Sophia.
             - **Descrição do testador**: Estagiária de RH do Inteli.
             - **Persona:** Coordenadora.

        - **Resultado do 1° teste:** Conseguiu cumprir todas as etapas com dificuldade.
            - Procurou cadastrar os técnicos na guia de Dashboard, levou um tempo para encontrar a aba certa de técnicos.
            - Após encontrar a aba técnicos, subiu os arquivos sem dificuldades.
            - Verificou os técnicos inseridos com sucesso.

       - **Resultado do 2° teste:** Conseguiu cumprir todas as etapas com sucesso e facilidade.
            - Encontrou facilmente a aba de demanda.
            - Encontrou o arquivo com facilidade e concluiu a tarefa com êxito.
            - Verificou a inserção com sucesso.
      - **Resultado do 3° teste:** Conseguiu cumprir todas as etapas com sucesso.
           - Encontrou a guia de Dashbard com facilidade, pois havia visto logo no início.
        - Selecionou os *inputs* UF, Cidade e data de execução de forma correta.
        - Executou o agoritmo e verificou as alocações no mapa e na tabela com sucesso.

   - **5° teste**: 

        - **Sobre o Testador:**
             - **Nome:** Sergio Venancio.
             - **Descrição do testador**: Professor de User Experience do Inteli.
             - **Persona:** Coordenador.
        - **Resultado do 1° teste:** Conseguiu cumprir todas as etapas com facilidade.
                
            - Analisou o dashboard e repetiu qual a tarefa a ser feita.
            - Após encontrar a guia técnicos, subiu os arquivos sem dificuldades.
            - Verificou os técnicos inseridos com sucesso.

        - **Resultado do 2° teste:** Conseguiu cumprir todas as etapas com sucesso e facilidade.
            - Encontrou facilmente a guia de demanda.
            - Encontrou o arquivo com facilidade, pois os desenvolvedores indicaram na inicialização do teste.
            - Verificou a inserção com sucesso.
        - **Resultado do 3° teste:** Conseguiu cumprir todas as etapas com sucesso e um pouco de dificuldade.
            - Encontrou a tela de Dashboard com êxito.
            - Na página de demandas, encontrou o botão para rodar o algoritmo e entendeu como usa-lo com facilidade.
            - Selecionou os *inputs* corretamente e apertou no botão "Calcular Alocação" com êxito.
            - Após a execução do calculo do algoritmo, conseguiu entender e analisar os dados no mapa com facilidade.
            - Na tabela dos dados de alocação, teve um pouco de dificuldade de entender os dados. Porém, percorreu pela tabela com facilidade.
        - **Feedbacks:** Recomendou que o nome da tela `Dashboard` fosse trocado por `Alocação`, para o usuário entender de forma mais intuita o objetivo da página, que é para rodar o algoritmo e obter a alocação indicada.
        

        

## 7. Ações Corretivas
Os testadores conseguiram, em sua maioria, concluir com êxito os enunciados, mesmo enfrentando algumas dificuldades em certas etapas. No entanto, observamos questões de usabilidade durante os testes, o que levou à implementação de ações corretivas.

Uma ação recorrente era procurar subir os arquivos com os técnicos na aba de `Dashboard`, que é a página inicial da aplicação. Por isso, o nome da página `Dashboard` foi trocado por `Alocação`.

Além disso, os desenvolvedores identificaram que os usuários tinham dificuldade em determinar a página em que estavam durante os testes. Para solucionar esse problema, introduzimos um indicativo visual na barra lateral. Agora, o nome da página atual é destacado com uma mudança de cor, proporcionando uma orientação mais clara sobre a localização do usuário na aplicação. Essas melhorias visam aprimorar a experiência do usuário e facilitar a navegação na plataforma.

Ademais, implementamos uma página de histórico de alocações, visando proporcionar ao usuário acesso fácil a todos os cálculos de alocação ideal que ele realizou. Essa adição tem como objetivo oferecer uma maneira conveniente de revisitar e analisar os resultados de alocações anteriores, contribuindo para uma experiência mais completa e informativa na utilização da aplicação.