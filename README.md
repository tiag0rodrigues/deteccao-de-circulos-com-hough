<h1>Detecção de Círculos com Hough</h1>

<dl>
<dt>Alunos:</dt>
<dd>Lais Vitória Batista Santos</dd>
<dd>Tiago Rodrigues dos Santos</dd
</dl>

<h2>Descrição</h2>
Esse projeto visa criar uma aplicação para detectar círculos em imagens usando a transformada de hough para círculos.
Foi feito um pré-processamento nas imagens antes de aplicar hough para limpar ruídos. Além disso, houve um processo para a previsão dos raios.

<h2>O nosso projeto possui a seguinte estrutura de diretório:</h2>
  
  deteccao-de-circulos-com-hough/ <br>
  ├── app/ <br>
  │   └── deteccao_circulos.ipynb <br>
  ├── dataset_metadata/ <br>
  │   └── ground_truth_boxes.json <br>
  ├── images/ <br>
  ├── .gitignore <br>
  ├── README.md <br>
  └── requirements.txt <br>

- Na pasta APP está o arquivo do código principal, onde estão os algoritmos.<br>
- Na pasta DATASET_METADATA está o arquivo com os valores conhecidos dos círculos disponíveis no Roboflow para comparar e testar eficiência do algoritmo.<br>
- Na pasta IMAGES estão as imagens utilizadas pelo algoritmo para detectar os círculos.<br>
- O arquivo requirements.txt possui as dependências que precisam ser instaladas para funcionamento do algoritmo.<br>

<h2>Instalação</h2>

<ol>
 <li>Crie uma pasta, exemplo "meuProjeto" # Nessa pasta ficará todo o projeto na sua máquina local </li>
 <li>Abra o terminal com diretório dentro da pasta "meuProjeto" # Se preferir utilize o terminal do editor da sua escolha</li>
 <li>Execute o comando "git clone https://github.com/tiag0rodrigues/deteccao-de-circulos-com-hough.git"</li>
 <li>No terminal, navegue até a pasta do repositório clonado "deteccao-de-circulos-com-hough" e execute o seguinte comando:    </li>
 <ul>
   <li>
     pip install -r requirements.txt
   </li>
 </ul>
</ol>
