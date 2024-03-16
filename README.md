
   # IA AZure  

>> “Este repositório é dedicado à exploração e implementação de soluções de Inteligência Artificial (IA) utilizando o Azure Machine Learning. Aqui, você encontrará exemplos de como treinar, implantar e gerenciar modelos de aprendizado de máquina na nuvem com o Azure. Além disso, este repositório também contém exemplos de como integrar esses modelos com aplicativos e serviços para criar soluções de IA completas. 




![Logo](http://www.prozessgroup.com/wp-content/uploads/2017/07/AzureNube.jpg)


# Aprendizados

Vamos lá 🚀 

Faça login em sua conta da Microsoft e crie um espaço de trabalho (workspace) no Azure Machine Learning Studio. 

No ambiente do workspace, clique em “ML automatizado” no menu à esquerda. Na próxima janela, clique em “+ Novo trabalho de ML automatizado”. 

1 - Preencha o formulário com os seguintes dados de    configuração: 
    
    Nome do trabalho:mslearn-bike-automl 
    Nome do experimento: (Deixe em branco) 
    Descrição: (Deixe em branco) 
    Tags: (Deixe em branco).
 
2 - Na próxima etapa, preencha os campos com os seguintes dados: 
    
    Tipo de tarefa e dados:
    Regressão Conjunto de dados: 
 
3 - Crie um novo conjunto de dados com as seguintes configurações: 
    
    Nome: bike-rentals 
    Descrição: Dados históricos de aluguel de bicicletas 
    Tipo:Tabular Fonte de dados: 

4 - Selecione URL da Web: Dados de aluguel de bicicletas  Configurações: 
    
    Formato de arquivo: 
    Delimitado Delimitador: Vírgula
    Codificação: UTF-8 

5 - Cabeçalhos de coluna: Somente o primeiro 
    
    arquivo tem cabeçalhos Pular linhas: 
    Nenhum Esquema: Incluir todas as colunas 
    diferentes de Caminho Configurações da 
    tarefa: 
    Tipo de tarefa: Regressão Coluna de 
    destino: Aluguéis (inteiro) 
    Métrica primária: Erro quadrático médio da raiz    
    normalizada Explicar melhor modelo:Não selecionado                                           Use todos os modelos suportados: 
    
6 - Não selecionado (restrinja o trabalho para tentar apenas alguns algoritmos específicos) 
    
    Modelos permitidos: Selecione apenas 
    RandomForest e LightGBM Limites: 
    Máximo de tentativas: 3 
    Máximo de tentativas simultâneas: 3 
    Nós máximos: 3 Limiar de 
    pontuação métrica: 0,085 (se um modelo 
    atingir uma pontuação métrica abaixo desse 
    valor, o trabalho termina) 

Clique em Criar para iniciar o trabalho de ML automatizado. O Azure Machine Learning irá treinar e avaliar modelos automaticamente com base nos parâmetros especificados. Lembre-se de adaptar essas 
configurações conforme suas necessidades 
específicas. 🚴‍♂️🔮


## Autores

- [@NicolasAlexAguiarRangel](https://github.com/NicolasAlexAguiarRangel/IA-Azure)

