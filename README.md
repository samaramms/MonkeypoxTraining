

# MonkeyPox: treinamento e análises exploratórias

#### Nota 1: o arquivo original/“cru” pode ser obtido [aqui](https://raw.githubusercontent.com/globaldothealth/monkeypox/main/latest.csv)
#### Nota 2: o arquivo pode sofrer alterações ser a medida que surgirem novos casos e/ou novas análises.
#### Nota 3: os números de casos do Brasil foram obtidos a partir do Boletim Epidemiológico (n. 60 - 16/09/22) disponibilizado em .pdf pelo Ministério da Saúde e trasnformado em .csv via Power BI.

### Sobre as informações, dados e dataset:

Por não ter muita experiência, usei um arquivo .csv já tratado a partir [deste dataset](https://www.kaggle.com/code/deepcontractor/monkey-pox-dataset) atualizado diariamente a partir do arquivo original (ver Nota 1) da Global Health. Os 2 datasets utilizados aqui contém dados em relação aos Casos Mundiais (suspeitos ou confirmados) e Casos Confirmados por gênero, idade, sintomas, data da confirmação, etc.

### **O que é a monkeypox/varíola dos macacos?**

É uma doença causada pelo vírus Monkeypox, da família dos vírus Orthopoxvirus, de onde também faz parte o vírus da varíola humana (erradicada na década de 80). Seus sintomas incluem lesões cutâneas, febre, dor de cabeça, dor nos músculos e fadiga, e pode ser transmitida por fluidos corporais, lesões ou qualquer outro tipo de contato com um humano/animal infectado (1,2,3)

### **Quando ela foi descoberta?**

Em 1958, quando cientistas dinamarqueses descobriram primatas infectados com esse vírus, daí o nome “monkeypox” . O primeiro caso em humanos foi registrado em 1970, na República Democrática do Congo (1,2).

### **Os macacos e outros primatas são culpados?**

Não! Apesar do nome ser varíola dos macacos, eles não são os  culpados do surto atual. Não há um estudo conclusivo que demonstre que o surto atual tenha começado por eles. Obviamente, um humano pode se contaminar se tiver contato com animais (primatas ou roedores) infectados. Mas, até agora os casos notificados tem sido de transmissões humano-humano (4)

### **Os humanos são os únicos afetados?**

Não, primatas e roedores também podem ser contaminados. A OMS recomenda também que humanos infectados evitem contato com PETs (1,6). Um exemplo (acessado em 24/08/2022) é este caso brasileiro onde houve a transmissão do vírus de [um humano para  um cachorro](https://g1.globo.com/mg/zona-da-mata/noticia/2022/08/23/juiz-de-fora-confirma-primeiro-caso-de-variola-dos-macacos-em-cachorro.ghtml)

### **O que este dataset mostra?**

As seções foram divididas em:

  - 10 países com maior número de casos
  - Número de casos a partir de viajantes
  - Há relação entre os hospitalizados e viajantes?
  - Números da Monkeypox no Brasil
  - Sintomas mais frequentes (em construção)


### **Qual o objetivo desse dataset?**

Além de ser um dataset de treinamento de ETL/visualização de dados sobre o número de casos de Monkeypox do Brasil e do Mundo (5,6), serve também para mostrar um pouco mais sobre a doença e combater o equívoco de que os primatas são os principais transmissores/culpados do surto atual 


## FONTES

1. [World Health Organization/ Organização Mundial da Saúde](https://www.who.int/news-room/fact-sheets/detail/monkeypox) 
2. Bunge EM, Hoet B, Chen L, Lienert F, Weidenthaler H, Baer LR, Steffen R. The changing epidemiology of human monkeypox-A potential threat? A systematic review. PLoS Negl Trop Dis. 2022 Feb 11;16(2):e0010141. doi: 10.1371/journal.pntd.0010141. PMID: 35148313; PMCID: PMC8870502. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8870502/
3. Kraemer, M., Tegally, H., Pigott, D. M., Dasgupta, A., Sheldon, J., Wilkinson, E., Schultheiss, M., Han, A., Oglia, M., Marks, S., Kanner, J., O'Brien, K., Dandamudi, S., Rader, B., Sewalk, K., Bento, A. I., Scarpino, S. V., de Oliveira, T., Bogoch, I. I., Katz, R., … Brownstein, J. S. (2022). Tracking the 2022 monkeypox outbreak with epidemiological data in real-time. The Lancet. Infectious diseases, 22(7), 941–942. https://doi.org/10.1016/S1473-3099(22)00359-0
4. [Nota da Sociedade Brasileira de Primatologia](https://linktr.ee/sbprimatologia?utm_source=linktree_profile_share&ltsid=c532f81d-702f-49a5-a890-b64a2670728d)
5. [Global Health](https://www.monkeypox.global.health/)
6. [BRASIL Ministério da Saúde](https://www.gov.br/saude/pt-br/composicao/svs/resposta-a-emergencias/coes/monkeypox) acesso em 30/08/2022.
