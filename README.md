# Vision Studio: Detect faces; Read text; e, Analyze images
## Entrega do projeto: Repositório: recog-txt-img

Desafio:

1. Criar um novo repositório no github com um nome a sua preferência;  
2. Criar uma pasta chamada 'inputs' e salve as imagens que você utilizou;  
3. Criar uma pasta chamado 'output' e salve os resultados de reconhecimento de texto nessas imagens;  
4. Criar um arquivo chamado readme.md, deixe alguns prints descreva o processo, alguns insights e possibilidades que você aprendeu durante o conteúdo;  
5. Compartilhe conosco o link desse repositório através do botão 'entregar projeto'.  
  
-------

## 1. Criar um novo repositório no github com um nome a sua preferência  

Na maquina local foi crido o diretório 'recog-txt-ing'  

'''bash
$ mkdir regog-txt-img
'''  

Depois, iniciei o diretório como um repositório no Git.

'''bash
$ git init
'''

No GItHub foi criado o repositório recog-txt-img

> Comandos/configurações:  
> 
> - "Novo repositório".  
> - Nome para o repositório: "auto-machine-learning".  
> - Descrição: "Projeto Vision Studio com três processos de identificação: Detect faces; Read text; e, Analyze images.".  
> - Visibilidade: "pública".  
> - Opção: LEIAME.  
> - Cliquei em "Criar repositório".  
> 

-------

## 2. Criar uma pasta chamada 'inputs' e salve as imagens que você utilizou  

Na maquina local, na raiz do repositório 'regog-txt-img', foi crido o diretório 'inputs'  

'''bash
$ mkdir inputs
'''  

No GItHub foi criado o diretório 'inputs' no repositório recog-txt-img

> Comandos/configurações:  
> 
> - Botão: "Add File".  
> - Opção: + Create new file.  
> - Preenchi: inputs/test.md  
> - Opção: Commit changes.  
> - Dentro do diretório 'inputs': "Add File".  
> - Opção: Upload files 
> - Cliquei em "Choose your files".  
> - Carregou o conjunto de imagens.  
>

Foram salvas as imagens, utilizadas observando os nomes para manter a ordem em que foram testadas, conforme os arquivos sugeridos na documentação, em quatro grupos: detect-faces-store-camera; exm-ocr-images; image-analysis-store-camera.  

-------

## 3. Criar uma pasta chamado 'output' e salve os resultados de reconhecimento de texto nessas imagens  

Na maquina local, na raiz do repositório 'regog-txt-img', foi crido o diretório 'output'  

'''bash
$ mkdir output
'''  

No GItHub foi criado o diretório 'inputs' no repositório recog-txt-img

> Comandos/configurações:  
> 
> - Botão: "Add File".  
> - Opção: + Create new file.  
> - Preenchi: output/test.md  
> - Opção: Commit changes.  
> - Dentro do diretório 'inputs': "Add File".  
> - Opção: Upload files 
> - Cliquei em "Choose your files".  
> - Carregou o conjunto de imagens.
>

Foram salvas as imagens, utilizadas observando os nomes para manter a ordem em que foram testadas, em quatro grupos: detect-faces-output-store-camera; exm-ocr-output-images; image-analysis-output-store-camera.  

>[!NOTE]
>
> Os arquivos de imagens foram baixados nas etapas:  
>   - 4.1. (https://aka.ms/mslearn-detect-faces), para o arquivo 'detect-faces.zip';  
>   - 4.2. ( https://aka.ms/mslearn-ocr-images), para o arquivo 'ocr-images.zip'; e,   
>   - 4.3. (https://aka.ms/mslearn-ocr-images), para o arquivo 'ocr-images.zip'.  
>
-------

## 4. Criar um arquivo readme.md, incluir Prints e descrição do processo, Insights e Possibilidades aprendidas  

-------

### 4.1. Criar um arquivo readme.md  

No GItHubna raiz do repositório 'regog-txt-img', foi crido o arquivo 'readme.md'.

> Comandos/configurações:  
>  
> - Botão: "Add File".  
> - Opção: + Create new file.  
> - Preenchi: readme.md  
> - Opção: Commit changes.  
>

Após a criação do arquivo, no diretório local foi feito o git pull do repositório.  
O arquivo foi editado no editor do GitHub e com o auxílio do VSCode no diretório local.  

-------

### 4.2. Prints e descrição do processo  

Foram abordados três processos de identificação no Vision Studio: Detect faces; Read text; e, Analyze images.  

Nos três casos é necessário criar um recurso Azure AI services, na própria inscrição Azure.  

>- 1. Entrar no portal Azure (https://portal.azure.com).  
>- 2. Clicar no botão ＋Create a resource e encnotrar o Azure AI services. Selecionei "criar um plano Azure AI services".  
>-    >> Na pagina para criar o recurso Azure AI services, configurei os seguintes itens:  
>     >> - Subscription: Azure subscription 1.  
>     >> - Resource group: LabVision.  
>     >> - Region: East US.  
>     >> - Name: DioFaceLab.  
>     >> - Pricing tier: Standard S0.  
>     >> - Selecinei o check box: "I acknowledge that I have read and understood all the terms below.  
>- 3. Selecionei Review + create then Create e aguardei a implantação se completar.

Na página "Select a resource to work with", passando o cursor do mouse sobre o recurso criado na lista, marcar o check box á esquerda do nomr do recurso, depois clicar no botão "Select as default resource".  
Com isso a configuração básica do Visioon Studio está pronta e pode-se trabalhar com as ferramentas de identificação disponíveis.

#### *4.2.1. Detect faces*  

Configuração do Detect faces no Vision Studio:  

>- 1. No navegador, ir até o Vision Studio (https://portal.vision.cognitive.azure.com).  
>- 2. Na página "Getting started with Vision", selecinar a aba "Face" e o card "Detect Faces".  
>- 3. Marcar o check box "Try It Out subheading, acknowledge the resource usage policy".  
>- 4. Selecionar as images de exemplo e observar as informações retornadas.  
>- 5. Now let’s try with some of our own images. Select https://aka.ms/mslearn-detect-faces to download detect-faces.zip. Then open the folder on your computer.  


    6. Locate the file named store-camera-1.jpg; which contains the following image:  

<img src="https://github.com/z3mafra/recog-txt-img/blob/main/inputs/detect-faces-store-camera-1.jpg" width="50%">

    7. Upload store-camera-1.jpg and review the face detection details that are returned.  
    8. Locate the file named store-camera-2.jpg; which contains the following image:  

<img src="https://github.com/z3mafra/recog-txt-img/blob/main/output/detect-faces-output-store-camera-1.jpg" width="50%">


    9. Upload store-camera-2.jpg and review the face detection details that are returned.  
    10. Locate the file named store-camera-3.jpg; which contains the following image:  
  
#### *4.2.2. Read text*  

#### *4.2.3. Analyze images*  

-------

### 4.3. Insights e Possibilidades aprendidas  

-------

## 5. Compartilhe conosco o link desse repositório através do botão 'entregar projeto'  
  
-------
