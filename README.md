# dio_iams_2024
Atividade com pontos de extremidade

  # About this activitie - DIO IA MS 2024 bootcamp 

  Abaixo descreverei como criei um modelo de previsão com devidos pontos de modelo configurados

     # Leticia Ferreira

    P.S.: Quase perdi a data limite mas corri para completar 

### Utilizando o modelo de treino ppronto de rental-bikes

  1. Crie um Repositório no GitHub:
    • Criei esse repositório em que está lendo meu READ.me, inclusive aradeço a atenção. Sou bem iiciante no GitHub por isso peço descupas por possíveis erros cometidos.

  2. Configuração do Azure Machine Learning:

• Acessei o Portal Azure e crie um novo recurso do Azure Machine Learning com as seguintes configurações:
    
    • Assinatura: Utilizei a de estudante que tenho.
    • Grupo de Recursos: Crie ou selecione um grupo de recursos.
    • Nome: Insira um nome exclusivo para o seu espaço de trabalho.
    • Região: Selecione a região geográfica mais próxima (recomendo EAST 2 para taxas mais acessíveis).
    • Conta de Armazenamento: Observe a nova conta de armazenamento padrão criada para o seu espaço de trabalho.
    • Cofre de Chaves: Observe o novo cofre de chaves padrão criado para o seu espaço de trabalho.
    • Insights de Aplicativo: Observe o novo recurso padrão de insights de aplicativo criado para o seu espaço de trabalho.
    • Registro de Contêiner: Nenhum (será criado automaticamente na primeira implantação de um modelo em um contêiner).

3. Acesse o Azure Machine Learning Studio:
   
       • Aguarde a criação do seu espaço de trabalho (pode demorar alguns minutos).
       • Acesse o Azure Machine Learning Studio usando sua conta da Microsoft.
       • Feche todas as mensagens exibidas.

7. Treine um Modelo com Aprendizado de Máquina Automatizado:

       • No Azure Machine Learning Studio, procure ML Autorizado e selecione Novo Trabalho de ML Automatizado.
       • Configure as seguintes opções:
       • Nome do Trabalho: mslearn-bike-automl
       • Nome do Experimento: mslearn-bike-rental
       • Descrição: Aprendizado de máquina automatizado para previsão de aluguel de bicicletas.
       • Tipo de Tarefa: Regressão
       • Conjunto de Dados: Crie um novo conjunto de dados com as seguintes configurações:
       • Nome: alugueldebicicletas (sem espaços no nome)
       • Descrição: Dados históricos de aluguel de bicicletas
       • Tipo: Tabular
       • Fonte de Dados: Selecione “De arquivos da web” e insira o URL da Web: aqui


  8. Salve o README.md e o Arquivo .json de Pontos de Extremidade:
  
    • Escreva o passo a passo desse processo no arquivo README.md.
    • Salve o README.md e o arquivo .json de pontos de extremidade no seu repositório do GitHub.



   ## ❉ Links de Refência
    https://github.com/FelipeAPiresBR/ResumoMachineLearning/blob/main/README.md
    https://gallery.azure.ai/Experiment/Bike-Rentals-complete-experiment
    https://raw.githubusercontent.com/MicrosoftLearning/mslearn-ai-fundamentals/main/data/ml/daily-bike-share.csv
    
      
