# Azura, Vision Studio: Detect faces; Read text; e, Analyze images
## Entrega do projeto: Repositório: recog-txt-img

Desafio:

1. Criar um novo repositório no github com um nome a sua preferência;  
2. Criar uma pasta chamada 'inputs' e salve as imagens que você utilizou;  
3. Criar uma pasta chamado 'output' e salve os resultados de reconhecimento de texto nessas imagens;  
4. Criar um arquivo chamado readme.md, deixe alguns prints descreva o processo, alguns insights e possibilidades que você aprendeu durante o conteúdo;  
5. Compartilhar conosco o link desse repositório através do botão 'entregar projeto'.  
  
-------

## 1. Criar um novo repositório no github com um nome a sua preferência  

Na maquina local foi crido o diretório 'recog-txt-ing'  

~~~bash
$ mkdir regog-txt-img
~~~  

Depois, iniciei o diretório como um repositório no Git.

~~~bash
$ git init
~~~

No GitHub foi criado o repositório recog-txt-img

> Comandos/configurações:  
> 
> - "Novo repositório".  
> - Nome para o repositório: "recog-txt-img".  
> - Descrição: "Projeto Vision Studio com três processos de identificação: Detect faces; Read text; e, Analyze images.".  
> - Visibilidade: "pública".  
> - Opção: LEIAME.  
> - Cliquei em "Criar repositório".  
> 

-------

## 2. Criar uma pasta chamada 'inputs' e salve as imagens que você utilizou  

Na maquina local, na raiz do repositório 'regog-txt-img', foi crido o diretório 'inputs'  

~~~bash
$ mkdir inputs
~~~  

No GitHub foi criado o diretório 'inputs' no repositório recog-txt-img

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

Foram salvas as imagens, utilizadas observando a codificação dos nomes para manter a ordem em que foram testadas, conforme os arquivos sugeridos na documentação, em quatro grupos: detect-faces-store-camera; exm-ocr-images; image-analysis-store-camera.  

>[!NOTE]
>
> Os arquivos de imagens foram baixados, respectivamente, nas etapas:  
>   - 4.2.1. (https://aka.ms/mslearn-detect-faces), para o arquivo 'detect-faces.zip';  
>   - 4.2.2. ( https://aka.ms/mslearn-ocr-images), para o arquivo 'ocr-images.zip'; e,   
>   - 4.2.3. (https://aka.ms/mslearn-ocr-images), para o arquivo 'ocr-images.zip'.  
>
-------

## 3. Criar uma pasta chamado 'output' e salve os resultados de reconhecimento de texto nessas imagens  

Na maquina local, na raiz do repositório 'regog-txt-img', foi crido o diretório 'output'  

~~~bash
$ mkdir output
~~~  

No GitHub foi criado o diretório 'output' no repositório recog-txt-img

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

Foram salvas as imagens, utilizadas observando a codificação dos nomes para manter a ordem em que foram testadas, em quatro grupos: detect-faces-output-store-camera; exm-ocr-output-images; image-analysis-output-store-camera.  

>[!NOTE]
>
> Os arquivos de imagens foram gerados nos testes, respectivamente, nas etapas:  
>   - 4.2.1. Detect faces, passo 7;  
>   - 4.2.2. Read text, passo 6; e,   
>   - 4.2.3. Analyze images, passo 6.  
>

-------

## 4. Criar um arquivo readme.md, incluir Prints e descrição do processo, Insights e Possibilidades aprendidas  

-------

### 4.1. Criar um arquivo readme.md  

No GitHub na raiz do repositório 'regog-txt-img', foi crido o arquivo 'readme.md'.

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

*Configurando para o Visio Studio*:
>
>- 1. Entrar no portal Azure (https://portal.azure.com).  
>- 2. Clicar no botão ＋Create a resource e encnotrar o Azure AI services. Selecionei "criar um plano Azure AI services".  
>     >> Na pagina para criar o recurso Azure AI services, configurei os seguintes itens:  
>     >> - Subscription: Azure subscription 1.  
>     >> - Resource group: LabVision.  
>     >> - Region: East US.  
>     >> - Name: DioFaceLab.  
>     >> - Pricing tier: Standard S0.  
>     >> - Selecinei o check box: "I acknowledge that I have read and understood all the terms below.  
>- 3. Selecionei Review + create then Create e aguardei a implantação se completar.

Na página "Select a resource to work with", passando o cursor do mouse sobre o recurso criado na lista, marcar o check box à esquerda do nome do recurso, depois clicar no botão "Select as default resource".  
Com isso a configuração básica do Visioon Studio está pronta e pode-se trabalhar com as ferramentas de identificação disponíveis.

#### *4.2.1. Detect faces*  

Configuração do Detect faces no Vision Studio:  

>- 1. No navegador, ir até o Vision Studio (https://portal.vision.cognitive.azure.com).  
>- 2. Na página "Getting started with Vision", selecinar a aba "Face" e o card "Detect Faces".  
>- 3. Marcar o check box "Try It Out subheading, acknowledge the resource usage policy".  
>- 4. Selecionar as images de exemplo e observar as informações retornadas.  
>- 5. Selecionar imagens em (https://aka.ms/mslearn-detect-faces) para baixar o arquivo "detect-faces.zip". Abrir folder no computador.  
>- 6. Localizar e subir o arquivo nameado 'store-camera-1.jpg'que contém a seguinte imagem:  

<img src="https://github.com/z3mafra/recog-txt-img/blob/main/inputs/detect-faces-store-camera-1.jpg" width="50%">

>- 7. Observe e revise os detalhes de detecção de rosto retornados, conforme mostrado aqui:  

<img src="https://github.com/z3mafra/recog-txt-img/blob/main/output/detect-faces-output-store-camera-1.jpg" width="50%">
  
#### *4.2.2. Read text*  

Configuração para extrir texto de imagens no Vision Studio:  

>- 1. No navegador, ir até o Vision Studio (https://portal.vision.cognitive.azure.com).  
>- 2. Na página "Getting started with Vision", selecinar a aba "Optical character recognition”, e o card com o título "Extract text from images”.
>- 3. Marcar o check box "Try It Out subheading, acknowledge the resource usage policy".  
>- 4. Selecionar imagens em (https://aka.ms/mslearn-ocr-images) para baixar o arquivo "ocr-images.zip". Abrir folder no computador.  
>- 5. Localizar e subir o arquivo nameado 'exm-ocr-images-advert.jpg', que contém a seguinte imagem:  

<img src="https://github.com/z3mafra/recog-txt-img/blob/main/inputs/exm-ocr-images-advert.jpg" width="50%">

>- 6. Observe a informação que retorna da análise. Na imagem, a localização do texto é indicada por uma caixa delimitadora, conforme mostrado aqui:  

<img src="https://github.com/z3mafra/recog-txt-img/blob/main/output/exm-ocr-output-images-advert.jpg" width="50%">

-------
 
#### *4.2.3. Analyze images*  

Vejamos a funcionalidade de gerar legendas para uma imagem, do Azure AI Vision.  
As legendas das imagens estão disponíveis por meio dos recursos Caption e Dense Captions.  

>- 1. Em um navegador da web, navegue até Vision Studio (https://portal.vision.cognitive.azure.com).  
>- 2. Na página inicial Getting started with Vision, selecione a guia Image analysis e, em seguida, selecione o bloco Add captions to images. 
>- 3. No subtítulo "Try It Out", ler o termo e marcar o check box “acknowledge the resource usage policy”.
>- 4. Selecionar imagens em (https://aka.ms/mslearn-images-for-analysis) para baixar o arquivo "image-analysis.zip". Abrir folder no computador.  
>- 5. Localizar e subir o arquivo nameado 'image-analysis-store-camera-4.jpg'; que contém a seguinte imagem:  

<img src="https://github.com/z3mafra/recog-txt-img/blob/main/inputs/image-analysis-store-camera-4.jpg" width="50%">

>- 6. Observe o texto da legenda gerada, visível no painel Atributos detectados à direita da imagem. A funcionalidade Caption fornece uma frase única e legível que descreve o conteúdo da imagem, conforme mostrado aqui:  

<img src="https://github.com/z3mafra/recog-txt-img/blob/main/output/image-analysis-output-store-camera-4.jpg" width="50%">  
  
-------

### 4.3. Insights e Possibilidades aprendidas  

São muitas as ideias e aplicações possíveis quando se pensa nas possibilidades aprendidas durante conteúdo deste desafio. Seguem alguns insights e possibilidades que podem ser desenvolvidos em aplicações práticas com esses três recursos.  

**Detect Faces**: Este recurso pode ser utilizado em sistemas de segurança para identificar pessoas em tempo real em locais públicos ou privados, como aeroportos ou prédios corporativos. Também pode ser empregado em aplicativos de organização de fotos, automatizando o processo de marcação de pessoas. Além disso, em aplicações de entretenimento, como filtros de redes sociais, pode proporcionar uma experiência interativa aos usuários.[[1](https://learn.microsoft.com/pt-br/visualstudio/ide/navigating-code?view=vs-2022)]  
   
Read Text: Essa funcionalidade é útil para aplicativos de acessibilidade, convertendo texto em imagens em texto legível por máquina para pessoas com deficiência visual. Em ambientes empresariais, pode ser utilizado para automatizar a extração de informações de documentos, como faturas e contratos. Além disso, em aplicativos de tradução instantânea, pode ajudar os usuários a entenderem conteúdos em diferentes idiomas.[[2](https://azure.microsoft.com/pt-br/)]  

Analyze Images: Esse recurso permite extrair insights valiosos de imagens. Em aplicações de saúde, pode ser utilizado para analisar imagens médicas, auxiliando médicos no diagnóstico de doenças. Em comércio eletrônico, pode ser usado para recomendar produtos com base nas preferências do usuário, analisando suas interações visuais. Além disso, em aplicativos de segurança, pode identificar objetos perigosos em imagens de vigilância.[[3](https://medium.com/cwi-software/reconhecimento-facial-com-python-b2d0981a1aaa)]    

🌐 Sources  
[[1] learn.microsoft.com - Opções de revisão para navegar pelo código no editor](https://learn.microsoft.com/pt-br/visualstudio/ide/navigating-code?view=vs-2022)  
[[2] azure.microsoft.com - Microsoft Azure: Serviços de computação em nuvem](https://azure.microsoft.com/pt-br/)  
[[3] medium.com - Reconhecimento Facial com Python](https://medium.com/cwi-software/reconhecimento-facial-com-python-b2d0981a1aaa)  

-------

## 5. Compartilhar o link do repositório através do botão 'entregar projeto'  

Antes de finalizar o desafio, uma providência importate é limpar (Clean up) o Visio Studio, deletando os recrusos para não gerar custos desnecessários.

### **Clean up**  
Como é recomendado na documentção, senão se pretende fazer mais exercícios, excluir todos os recursos que não precisa mais. Isso evita acumular custos desnecessários.  

>    1. Abra o portal do Azure (<https://portal.azure.com/>) e selecione o grupo de recursos que contém o recurso que você criou.  
>    2. Selecione o recurso e selecione Excluir e depois Sim para confirmar. O recurso é então excluído.
>
>>  - **Observação:** Uma curiosidade que, nesta etapa, a plataforma informou que o consumo de recursos na modalidade de acesso gratuito, foi de R$ 0,79. Restando ainda um crédito de R$ 988,18.
 
### **Postar link do repositório**

Como é solicitado no enunciado do desafio, o link do GitHub deve ser compartilhado na plataforma da DIO. Para isso, segui os seguintes passos:
>
>>    1. Abra o portal da DIO (<https://www.dio.me/>), com as credenciais e selecione o [Bootcamp Microsoft AZure AI Fundamentals](https://web.dio.me/track/microsoft-azure-ai-fundamentals).
>    2. Entra na Atividade Desafio de projeto: "Reconhecimento Facial e transformação de imagens em Dados no Azure ML"
>    3. Clica no botão "ENTREGAR PROJETO" 
>    4. Cola o link do projeto na caixa de texto "Repositório do Projeto"; Cola a descrição do repositório; Ler e marcar o Check box "Termos de uso", concordando com os termos o recurso; e,
>    5. Selecione Entregar. O Desafio é então entregue.
>

-------

-------
