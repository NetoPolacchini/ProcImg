Título do Projeto:
    Trabalho Final Processamento de Imagens

Descrição dos descritores implementados:
    Foi usado o Hu Moments e o LBP

Repositório do projeto:
    https://github.com/NetoPolacchini/ProcImg

Classificador e acurácia:


    HuMoments:
        Multilayer Perceptron: 80.36%
        Random Forest: 85.71%
        Support Vector Machine: 89.29%

    Local Binary Pattern:
        Multilayer Perceptron: 89.29%
        Random Forest: 87.5%
        Support Vector Machine: 96.43%


 Instruções de uso:
    Antes de extrair as features é necessário conferir
 se as pastas features_labels/test e features_labels/train
 estão vazias. Após isso, em grayHistogram_FeatureExtraction.py,
 nas linhas 19 e 26, é necessário alterar a função
 de extração dos dados para a função desejada no
 momento.
