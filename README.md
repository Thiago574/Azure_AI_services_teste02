# Projeto: Laboratório AI-900 no Azure Machine Learning

Este README documenta o processo realizado para testar o **Azure AI Services**, configurar experimentos no Azure Machine Learning, e realizar testes de detecção facial e extração de texto a partir de imagens.

---

## Experimento 1: Detecção Facial

### 1. Acessando o Azure AI Services
- Acessei minha conta no Azure.
- Pesquisei por **Azure AI Services** na barra de pesquisa do portal.

### 2. Criando um Novo Workspace
- Cliquei no botão "＋Criar um recurso" e pesquisei por "Azure AI Services".
- Selecionei criar um plano de serviços Azure AI.
- Configurei o recurso conforme a [documentação oficial](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html).

### 3. Configurando o Recurso
- Nomeei o recurso como **TesteAzureDetectfaces**.
- Cliquei em "Review + Create" e, posteriormente, em "Create".
- Aguardei alguns minutos até a confirmação do deployment.
- Após a confirmação, acessei o Vision Studio em [portal.vision.cognitive.azure.com](https://portal.vision.cognitive.azure.com) e configurei o recurso como indicado na documentação.

### 4. Realizando Detecção Facial
- No Vision Studio, selecionei a guia **Face** e cliquei em **Detect Faces in an Image**.
- Li e reconheci a política de uso de recursos, marcando a caixa correspondente.
- Carreguei as imagens de amostra disponíveis e observei os dados de detecção de rosto retornados.

### 5. Resultados
- Os arquivos de entrada e saída do processo podem ser encontrados nos diretórios `input` e `output`, respectivamente.

---

## Experimento 2: Extração de Texto (OCR)

### 1. Acessando o Azure AI Services
- Acessei minha conta no Azure.
- Pesquisei por **Azure AI Services** na barra de pesquisa do portal.

### 2. Criando um Novo Workspace
- Cliquei no botão "＋Criar um recurso" e pesquisei por "Azure AI Services".
- Selecionei criar um plano de serviços Azure AI.
- Configurei o recurso conforme a [documentação oficial](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html).

### 3. Realizando Extração de Texto (OCR)
- Naveguei até o Vision Studio em [portal.vision.cognitive.azure.com](https://portal.vision.cognitive.azure.com).
- Na página inicial, selecionei **Optical Character Recognition** e cliquei no bloco **Extract Text from Images**.
- Li e reconheci a política de uso de recursos, marcando a caixa correspondente.
- Carreguei as imagens de amostra e observei os textos extraídos.

### 4. Resultados
- Os arquivos de entrada e saída do processo podem ser encontrados nos diretórios `input` e `output`, respectivamente.

---

## Diretórios
- **input/**: Contém as imagens de entrada utilizadas nos experimentos.
- **output/**: Contém os resultados dos experimentos, incluindo os dados de detecção facial e textos extraídos.

---

## Links Úteis
- [Documentação Oficial - Detecção Facial](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html)
- [Documentação Oficial - OCR](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)
- [Vision Studio Portal](https://portal.vision.cognitive.azure.com)

---

## Observações
- Esses experimentos foram realizados com base nos laboratórios fornecidos pela Microsoft Learning para AI-900.
- As funcionalidades testadas demonstram o uso do **Azure AI Services** em detecção facial e extração de texto, que podem ser aplicadas em diversos casos de uso no mundo real.
