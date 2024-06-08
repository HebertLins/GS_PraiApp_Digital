# GS_PraiApp_Digital
Repositório para as entregas da Global Solution - Disciplina Digital Business Enablement 

# Nome da nossa aplicação/projeto: PraiApp

![image](https://github.com/HebertLins/GS_PraiApp_DotNet/assets/111543334/a2d1efd9-20e9-4783-a6ff-b2fab70de1e3)

# Escopo do Projeto

Para a criação do nosso projeto utilizamos dois pontos focais: Soluções para Redução da Poluição Marinha e Ferramentas de Dados para Gestão Sustentável dos Oceanos.
Diante do mar de possibilidades que tínhamos em nossa frente, decidimos focar nas regiões costeiras do nosso país e suas praias. Dessa forma surgiu a ideia do PraiApp.

## Introdução

Atualmente um dos maiores problemas a serem resolvidos pelo ser humano é a poluição deixada pelo avanço tecnológico e falta de cuidado, algo que muitos vêm tentando 
solucionar em várias frentes como reciclagem e produtos reutilizáveis. Dentro deste contexto um dos locais do meio ambiente em que podemos proteger é o oceano, contendo a vida marinha. 
Considerando este contexto, vê-se a necessidade de tomar uma atitude e mudar a realidade de nossos oceanos, e no caso desta proposta, melhorar a qualidade de vida da vida marinha 
a partir do controle da poluição em praias.

## O que é o PraiApp?

Uma aplicação voltada para a gestão ambiental criada com o intuito de auxiliar instituições responsáveis e interessadas em cuidar das nossas praias, levando a elas as 
informações necessárias sobre o estado atual de uma região específica, podendo assim focar seus recursos nos pontos principais a serem melhorados de modo rápido e intuitivo.
Dados esses que só serão atualizados por instituições de confiança, ONGs com histórico positivo e instituições governamentais relacionadas, fazemos essa seleção para 
que tenhamos certeza de que estaremos trabalhando com dados de confiança. Assim, uma pessoa que gostaria de ajudar o meio ambiente e utilizar a nossa aplicação como 
uma ferramenta deveria procurar se afiliar a uma dessas organizações.

## Sistema de Avaliações

Antes de tudo, é necessário entender os pontos de cada tópico de avaliação:

1. **Limpeza**: Trata de avaliar a quantidade de resíduo deixada na faixa de areia da praia em questão.
2. **Estrutura**: Trata de avaliar o quanto a praia está preparada (ou não) para receber seus visitantes, considerando pontos relacionados à infraestrutura, ou seja, se está se preocupando em manter uma infraestrutura que não agride o meio ambiente, disposição de banheiros, pontos para descarte de lixo, entre outros.
3. **Sinalização**: Trata de avaliar quão bem sinalizada está aquela praia, considerando pontos como sinalização de perigo em pontos de risco, sinalização para informar aos banhistas sobre as condições do mar, sinalização para indicar os pontos adequados onde o descarte de lixo deve ser realizado, etc.
4. **Monitoramento**: Avalia quanto as organizações responsáveis estão se preocupando em monitorar e contribuir para o controle de todos os outros pontos de avaliação. Esse ponto é fundamental para a educação das pessoas que frequentam determinada região.
5. **Poluição**: Trata de avaliar o quanto de resíduo está sendo descartado na praia. Estamos falando de canais, resíduos químicos, lixo contaminante e materiais não biodegradáveis, ou seja, tudo aquilo que é descartado indevidamente e acaba parando no mar.
6. **Conservação Ambiental**: Avalia o quão bem cuidada está aquela praia para a conservação do habitat natural dos seres vivos da região, se o uso daquela praia está sendo feito de maneira sustentável e que não agride o meio ambiente.
7. **Total**: Considera todos os pontos avaliados acima e gera uma avaliação geral sobre a praia.

De certo modo, todos os pontos estão interligados. É evidente que todos os pontos de avaliação se correlacionam em certo nível, porém abordam separadamente diferentes tópicos. É assim que desejamos entregar uma solução de fácil entendimento e análise.

# Guia para Executar a aplicação (PraiApp):

1. Maiores detalhes para isso podem ser conferidos no vídeo (Último Item) de apresentação da nossa aplicação, onde teremos um exemplo de uso da mesma.

2. É recomendado que para os testes se utilize o banco de dados H2, que pode ser acessado via url "http://localhost:8080/h2-console". Com o intuito de não acabar impactando o nosso banco de dados para outras entregas, estará nessa configuração por padrão.

3. A aplicação possui integração com um banco de dados Oracle, porém para que ela funcione corretamente é necessário remover os comentários das linhas que se referem ao Oracle no "application.properties" e comentar as linhas referentes ao H2.

4. Essa aplicação funciona com a autenticação via Github a partir do OAuth2, portanto para realizar login com Sucesso e assim utilizá-la devidamente, por favor, crie um ID e um SECRET pelo próprio GITHUB e insira os mesmo na "application.properties". Após esses passos será possível fazer login na aplicação.

5. Rodar a classe principal da aplicação, classe "QuoteLevellingApplication";

6. Com a nossa aplicação rodando será possível realizar o Login e navegar por todas as nossas telas.

7. Vale lembrar que existem validações em nosso sistema, então atente-se ao utilizá-la


#   Vídeo Pitch

PlaceHodler

#   Vídeo de Apresentação

PlaceHolder

# Deploy em Nuvem

https://dev.azure.com/RM97221/PraiApp


https://praiapp.azurewebsites.net/
