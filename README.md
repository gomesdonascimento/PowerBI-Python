# PowerBI-Python


## Resolvendo problema da execução de script python no powerbi

Abra o Prompt do Anaconda: Em seguida, você deve ir para o Ambiente Conda que deseja usar no PowerBI. Estou tendo um ambiente 'temp', então eu o ativo primeiro no 'Prompt do Anaconda':

(base) C:\Users\ashish>conda activate temp
Em seguida, vou para o diretório que contém o arquivo executável "PowerBI" na pasta de instalação:

(temp) C:\Users\ashish>cd "C:\Program Files\Microsoft Power BI Desktop\bin"
Então, eu inicio o PowerBI a partir do Prompt:

(temp) C:\Program Files\Microsoft Power BI Desktop\bin>PBIDesktop.exe
Isso corrige o erro NumPy que você está recebendo. Se você quiser qualquer outro pacote para usar com o PowerBI, instale esse pacote no respectivo "Ambiente Conda" (no meu caso é "temp").

Certifique-se de que o diretório inicial do Python (Anaconda3) foi adicionado às opções globais do 'Power BI Desktop' na seção de script Python.
