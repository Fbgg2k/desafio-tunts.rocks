# desafio-tunts.rocks
desafio usando linguagens de programação

# Todos os arquivos necessários estão disponíveis nesta pasta do [Google Drive](https://drive.google.com/drive/folders/1bGkkww68Nzw__DxhtbE9c6so2kGF2FSO)

Como usar:

    
    1.Baixe o arquivo .ipynb e JSON de credenciais e acesse a planilha do Google Sheets.
    2.Execute o script Python desafio_dev.ipynb.
    3.Edite as notas dos alunos na planilha do Google Sheets. As notas devem estar no formato de 0 a 10 e podem ser inseridos vírgula ou ponto.
    4.Edite o número de faltas dos alunos na planilha do Google Sheets. As faltas devem estar no formato de 0 a 60.
    5.O script irá acessar a planilha do Google Sheets especificada e calculará as notas, faltas e a situação de cada aluno.
    6.As notas, faltas e situações atualizadas serão refletidas na planilha.
    
# Tutorial de Uso do Script de Atualização de Planilha

Este tutorial orienta sobre como usar o script Python para atualizar uma planilha do Google Sheets com as notas e situações dos alunos.
Requisitos

    Conta no Google
    Acesso à internet
    Navegador da web
    Conta no GitHub (opcional)

Passos

    1.Baixar o arquivo JSON de Credenciais do Google
        Baixe o arquivo JSON e guarde-o em seu computador.

    2.Acessar o Google Colab
        Abra o Google Colab em seu navegador.

    3.Fazer Upload do Arquivo JSON
        No Google Colab, clique no ícone "Upload" e carregue o arquivo .ipynb no canto superior direito .
        Selecione o arquivo JSON de credenciais que você baixou anteriormente.

    4.Copiar e Colar o Código
        Copie o código do script Python fornecido neste tutorial.
        Cole o código no Google Colab.

    5.Executar o Script
        Execute o script no Google Colab.
        Siga as instruções apresentadas durante a execução.

    6.Editar a Planilha
        Abra a planilha do Google Sheets que você deseja atualizar.
        Insira as notas e faltas dos alunos na planilha.
        Lembre-se de que as notas devem estar no formato de 0 a 10 e podem usar vírgulas ou pontos (por exemplo, 7.5 ou 8,2).
        As faltas devem ser no máximo 60 e também devem estar no intervalo de 0 a 60.

    7.Visualizar Resultados
        Após a execução do script, verifique a planilha para ver as situações dos alunos atualizadas.


# Tutorial: Usando Python de aplicação

Este tutorial explora um script em Python que calcula a média das notas dos alunos em uma planilha do Google Sheets e determina sua situação (aprovado, reprovado por nota, exame final) com base nas notas e no número de faltas. Além disso, o script calcula a nota necessária para aprovação final (NAF) em caso de exame final.
Pré-requisitos

Antes de começar, certifique-se de ter as seguintes dependências instaladas:

    Python 3.x
    Bibliotecas gspread e google-auth: pip install gspread google-auth

Estrutura do código

O script consiste em várias partes:

    Configuração de Credenciais: Carrega as credenciais do arquivo JSON para autenticar o acesso à API do Google Sheets.
    Leitura dos Dados da Planilha: Obtém os dados da planilha do Google Sheets.
    Cálculo das Médias e Situações: Calcula a média das notas e determina a situação de cada aluno com base nas notas e no número de faltas.
    Atualização da Planilha: Atualiza a planilha do Google Sheets com as novas notas e situações calculadas.

Se encontrar algum problema ou tiver alguma sugestão de melhoria, sinta-se à vontade para abrir uma issue ou enviar um pull request!
    
    Execute o script Python desafio_dev.ipynb.
    Edite as notas dos alunos na planilha do Google Sheets. As notas devem estar no formato de 0 a 10 e podem ser inseridos vírgula ou ponto.
    O script irá acessar a planilha do Google Sheets especificada e calculará as notas e a situação de cada aluno.
    As notas e situações atualizadas serão refletidas na planilha.
