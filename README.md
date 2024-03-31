# Dio-MS-ai900-DP02-VisionStudioAzure
Desafio de Projeto da DIO para bootcamp ai900 Azure AI Fundamentals - Vision Studio Azure
- Dentro desse desafio estaremos seguindo as três documentações a seguir, mas note que o inicio de criação e deploy do Resource é igual. Apenas dentro do Vision Studio hvera distinção das documentações.
  - Detect faces => https://aka.ms/ai900-face
  - Tead Text => https://aka.ms/ai900-ocr
  - Analyze Images => https://aka.ms/ai900-image-analysis

## STEP 01
- No partal do Azure: https://portal.azure.com/ 
- Crie um novo recurso, dependendo em qual tela estiver pode clicar em "**+ Create a resurce**" ou "**Create**".
![Screenshot 2024-03-30 235038](https://github.com/c23b/Dio-MS-ai900-DP02-VisionStudioAzure/assets/12342627/2749b252-76fa-4fa4-8e78-a859e3e4b8dd)

- O recurso a ser criado será o "**Azure Ai Services**", pode pesquisar por esse nome na barra de pesquisa ou dentro da categori "**AI + Machine Learning**".
![Screenshot 2024-03-30 235219](https://github.com/c23b/Dio-MS-ai900-DP02-VisionStudioAzure/assets/12342627/9069ea44-4fb7-412d-9098-a2dce652285a)

- Preencha o "**Resource Group**", "**Name**", "**Pricing tier**" com o valor "**Standard S0**" e por fim marque o checkbox. Agora Clique em "**Review + create**" e na tela final "**Create**".
- "**Lembre**": Criar os resources com a "**Region**" nos EUA consome menos créditos do Azure.
![Screenshot 2024-03-30 235621](https://github.com/c23b/Dio-MS-ai900-DP02-VisionStudioAzure/assets/12342627/01b7c6fa-08af-4d55-af8a-fc64297cb4e2)
![Screenshot 2024-03-30 235652](https://github.com/c23b/Dio-MS-ai900-DP02-VisionStudioAzure/assets/12342627/ebf9ba6b-73ba-4f35-a60f-298242f74e47)

- Aguarde o deploy do resource estar completo.
![Screenshot 2024-03-30 235726](https://github.com/c23b/Dio-MS-ai900-DP02-VisionStudioAzure/assets/12342627/ca1e35e1-2a93-4064-b698-71f439149830)

## STEP 02
- Abra em uma nova aba do navegador o https://portal.vision.cognitive.azure.com.
- Verifique se ao abrir o link você ja esta logado, caso contrario faça login.
- Clique em "**View all resources**"
![Screenshot 2024-03-30 235954](https://github.com/c23b/Dio-MS-ai900-DP02-VisionStudioAzure/assets/12342627/aa67debb-4943-43b2-8ffc-d819a5df19a9)
![Screenshot 2024-03-31 000125](https://github.com/c23b/Dio-MS-ai900-DP02-VisionStudioAzure/assets/12342627/bf3e8231-a21c-446e-ae55-09cd5c05b264)

- Na tabela de resources selecione o resource desejado e clique em "**Select as default resource**".
![Screenshot 2024-03-31 000149](https://github.com/c23b/Dio-MS-ai900-DP02-VisionStudioAzure/assets/12342627/6ffa5476-87ee-4cc6-8a33-8c31dba054fa)

- Ao selecionar o resource para ser o default, a tela ira apresenta-lo dessa forma.
![Screenshot 2024-03-31 000237](https://github.com/c23b/Dio-MS-ai900-DP02-VisionStudioAzure/assets/12342627/04a1d930-7820-48e9-b85c-8300027b58a7)

## STEP 03 -  Detect faces
- seguindo a documentação [Detect faces](https://aka.ms/ai900-face) 
- Na tela inicial do Vision Studio clique em "**Face**" e entre em "**Detect faces in an image**"
![Screenshot 2024-03-31 000316](https://github.com/c23b/Dio-MS-ai900-DP02-VisionStudioAzure/assets/12342627/93d9f420-d9c8-471c-b816-acfaec9609bf)

- Selecione o checkbox.
- E selecione uma foto  em "**Browse for a file**".
![Screenshot 2024-03-31 001628](https://github.com/c23b/Dio-MS-ai900-DP02-VisionStudioAzure/assets/12342627/9f46e59f-1c50-44fd-a6cd-3991c2d949a0)

- Após selecionar a foto a ferramente ja vai identificar os rostos "**humanos**" presentes na imagem selecionada.
![Screenshot 2024-03-31 002227](https://github.com/c23b/Dio-MS-ai900-DP02-VisionStudioAzure/assets/12342627/bef0703a-29d1-4126-a40a-cc77444892be)

## STEP 04 - Read Text
- seguindo a documentação [Read Text](https://aka.ms/ai900-ocr)
- Na tela inicial do Vision Studio clique em "**Optical character recognition**" e entre em "**Extract text from images**".
![Screenshot 2024-03-31 002734](https://github.com/c23b/Dio-MS-ai900-DP02-VisionStudioAzure/assets/12342627/4e97db28-fd3a-4d12-9d92-8859c738f2b1)

- Selecione o checkbox.
- E selecione uma foto  em "**Browse for a file**".
![Screenshot 2024-03-31 003549](https://github.com/c23b/Dio-MS-ai900-DP02-VisionStudioAzure/assets/12342627/b7e32e75-16c2-4062-96fa-c7d1bfe281f7)

- Após selecionar a foto a ferramente ja vai identificar todos os textos presentes na imagem.
![Screenshot 2024-03-31 003651](https://github.com/c23b/Dio-MS-ai900-DP02-VisionStudioAzure/assets/12342627/a24b7328-374a-4675-b111-772cd7b25dab)

## STEP 05 - Analyze Images
- seguindo a documentação [Analyze Images](https://aka.ms/ai900-image-analysis)
- Na tela inicial do Vision Studio clique em "**Image analysis**" e entre em "**Add captions to images**".
![Screenshot 2024-03-31 192326](https://github.com/c23b/Dio-MS-ai900-DP02-VisionStudioAzure/assets/12342627/b48e8239-8f91-4c71-b250-bc5c43a26478)

- Selecione o checkbox.
- E selecione uma foto  em "**Browse for a file**".
![Screenshot 2024-03-31 004348](https://github.com/c23b/Dio-MS-ai900-DP02-VisionStudioAzure/assets/12342627/d78675be-23c6-4b54-a030-c8199878b290)

- Após selecionar a foto a ferramente ja vai tentar descrever o que esta presente ou ocorrendo na imagem.
![Screenshot 2024-03-31 004403](https://github.com/c23b/Dio-MS-ai900-DP02-VisionStudioAzure/assets/12342627/88c42583-52b7-4cbf-ad93-365fb33abb06)

## Conclusão
- O Azure possui boas ferramentas de AI referente a Visão Computacional.
- Os exemplos usados podem ser simples, mas com treinamento a ferramenta pode capturar itens ou ações desejadas, assim temos um leque gigantesco de possíbilidades.
  - Identificar a necessidade de limpar algo
  - Algém realizando uma ação não permitida em determinado local.
  - Identificar pessoas desaparecidas ou procuradas.
- Os paginas disponibilisam documentação para acessar as ferramentas via API, mas como há o consumo de créditos não tirei tempo para implementar algo sitado a cima. Mas a voltade não falta! kkkkkk
