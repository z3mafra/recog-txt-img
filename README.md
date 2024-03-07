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
> - .  

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
> - Opção: [Upload files](https://fontawesome.com/icons/arrow-up-from-bracket?f=classic&s=solid)  
> - Cliquei em "Criar repositório".  
> - .  

-------

## 3. Criar uma pasta chamado 'output' e salve os resultados de reconhecimento de texto nessas imagens  

Na maquina local, na raiz do repositório 'regog-txt-img', foi crido o diretório 'output'  

'''bash
$ mkdir output
'''  

Foram salvas as imagens, utilizadas observando os nomes para manter a ordem em que foram testadas, em quatro grupos: detect-faces-output-store-camera; exm-ocr-output-images; image-analysis-output-store-camera.  

-------

## 4. Criar um arquivo readme.md, incluir Prints e descrição do processo, Insights e Possibilidades aprendidas  

-------

### 4.1. Criar um arquivo readme.md  

Na maquina local, na raiz do repositório 'regog-txt-img', foi crido o arquivo 'readme.md'  

'''bash
$ touch readme.md
'''  

Com o arquivo criado abri o VSCode para editar

-------

### 4.2. Prints e descrição do processo  

Foram abordados três processos de identificação no Vision Studio: Detect faces; Read text; e, Analyze images.  

Nos três casos é necessário criar um recurso Azure AI services, na própria inscrição Azure.  

>- 1. Entrar no portal Azure (https://portal.azure.com).  

>- 2. Clicar no botão ＋Create a resource e encnotrar o Azure AI services. Selecione  create um plano Azure AI services.  

       Na pagina para criar o recurso Azure AI services, Configure os seguintes itens:  
       
          - Subscription: Azure subscription 1.  
          - Resource group: LabVision.  
          - Region: East US.  
          - Name: DioFaceLab.  
          - Pricing tier: Standard S0.  
          - By checking this box I acknowledge that I have read and understood all the terms below: Selected.  

>- 3. Select Review + create then Create and wait for deployment to complete.

On the Select a resource to work with page, hover your mouse cursor over the resource you created above in the list and then check the box to the left of the resource name, then select Select as default resource.



#### *4.2.1. Detect faces*  

Detect faces no Vision Studio  

    1. In a web browser, navigate to Vision Studio at https://portal.vision.cognitive.azure.com.  
    2. On the Getting started with Vision landing page, select the Face tab and then select the Detect Faces in an image tile.  
    3. Under the Try It Out subheading, acknowledge the resource usage policy by reading and checking the box.  
    4. Select each of the sample images and observe the face detection data that is returned.  
    5. Now let’s try with some of our own images. Select https://aka.ms/mslearn-detect-faces to download detect-faces.zip. Then open the folder on your computer.  


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
