# Compartimentação: o princípio mais importante para privacidade e segurança digital

O advento da maior crise de saúde pública do século XXI trouxe consigo a necessidade de nos isolarmos fisicamente uns dos outros, movendo todos os aspectos de nossas vidas pessoais, acadêmicas e profissionais para o âmbito virtual. Essa diáspora digital tornou essencial o aprendizado de boas práticas de privacidade e segurança na internet, sendo a principal delas o tema desse texto: Compartimentação.

Em resumo, o princípio da compartimentação consiste em decentralizar o acesso aos seus registros eletrônicos. Uma maneira simples de visualizar esse conceito é imaginando os compartimentos como "caixas", nas quais você organiza diferentes aspectos da sua vida digital. Por exemplo, você pode ter "caixas" diferentes para atividades pessoais, acadêmicas e profisionais. Assim, se a "caixa de atividades pessoais" for comprometida, a sua vida profissional e a sua vida acadêmica mantêm-se intactas. Entedido isso, vamos ver como colocar a compartimentaćão em prática!

Vale relembrar aqui que eu não sou um especialista em segurança, e mantenho esse blog apenas como *hobbie*. Se você considera que está em uma situação de alto risco, é recomendada a consultoria de um profissional. 

## Compartimentação de Serviços

Por maior que seja a conveniência fornecida pelos serviços do Google, o uso dos mesmo não é muito atrativo do ponto de vista da privacidade. Isto, pois uma única conta acumula dados de diversos frontes de nossas vidas como mostra a tabela abaixo:

| Serviço                | Produto          | Provedor | Dados Coletados                |
| ---------------------- | ---------------- | -------- | ------------------------------ |
| Pesquisa na Internet   | Google Search    | Google   | Seus interesses                |
| Navegação              | Google Maps      | Google   | Sua localização                |
| Armazenamento na nuvem | Google Drive     | Google   | Seus documentos                |
| Sincronização de fotos | Google Photos    | Google   | Seu rosto                      |
| Loja de aplicativos    | Play Store       | Google   | Seus aplicativos               |
| Sistema operacional    | Android          | Google   | Seus hábitos de uso do celular |
| Vídeos online          | YouTube          | Google   | Suas preferências de mídia     |
| Conferência de vídeo   | Meets e Hangouts | Google   | Sua voz e seus manerismos      |
| Email                  | Gmail            | Google   | Suas incrições em serviços     |
| Calendário             | Google Calendar  | Google   | Sua rotina e seus eventos      |

A ubiquidade de uma única empresa em todas as suas atividades digitais permite que a mesma agregue quantidades obcenas de informação sobre você. Por mais que a informação coletada por um único serviço pareça inofensiva a primeira vista (ex: "suas prefências de mídia" coletadas pelo YouTube), a verdade é que, nesse caso, o todo é maior que a soma das partes. A combinação de tais permite a elaboração de um modelo extremamente sofisticado e preciso para prever todos os aspectos de sua vida, o que constitui uma tremenda invasão de privacidade.

Além disso, todos esses serviços são vinculados a uma única Conta Google. Isso significa que basta a um hacker invadir essa conta para se apossar indevidamente de todas as informações mencionadas na tabela. Outra desvantagem da centralização de serviços é a dificuldade que se cria para trocar de provedor e testar novidades que possivelmente atenderiam melhor às suas necessidades.

Em vista disso, eu recomendo o uso de serviços que sejam oferecidos por empresas diferentes, que não compartilham dados entre si (ou, nos melhores casos, nem sequer coletam seus dados!). Isso isola (ou seja *compartimentaliza*) sua atividade online, oferecendo significativo grau de proteção a sua privacidade. A seguir estão listados alguns serviços que cumprem tais requerimentos. Se quiser testá-los, basta clicar no nome deles!

| Serviço                | Produto                                                      | Provedor                    | Dados Coletados                                              |
| ---------------------- | ------------------------------------------------------------ | --------------------------- | ------------------------------------------------------------ |
| Pesquisa na internet   | [DuckDuckGo](https://duckduckgo.com/)                        | DuckDuckGo Inc.             | Nenhum (apenas suas configurações, caso você queira)         |
| Navegação              | [Open Street Maps](https://www.openstreetmap.org)            | Open Street Maps Foundation | Nenhum ou apenas o necessário para criar uma conta, caso você queira |
| Armazenamento na nuvem | [CryptPad](https://cryptpad.fr)                              | XWiki                       | Apenas o necessário para criar uma conta (os documentos em si são encriptados de ponta a ponta) |
| Sincronização de fotos | [Syncthing](https://syncthing.net/)                          | Syncthing Community         | Nenhum                                                       |
| Loja de aplicativos    | [Aurora Store](https://auroraoss.com/)                       | Aurora Open Source Software | Nenhum                                                       |
| Sistema operacional    | [CalyxOS](https://freerobot.org/)                            | Calyx Institute             | Nenhum                                                       |
| Vídeos online          | [Invidious](https://invidious.snopyta.org/)                  | Invidious Community         | Nenhum ou apenas o necessário para criar uma conta, caso você queira |
| Conferência de vídeo   | [Jami](https://jami.net/)                                    | Savoir-Faire Linux          | Nenhum                                                       |
| Email                  | [Protonmail](https://protonmail.com/)                        | Proton Technologies Ltd.    | Apenas o necessário para criar uma conta (os emails em si são encriptados de ponta a ponta) |
| Calendário             | [Etar](https://play.google.com/store/apps/details?id=ws.xsoh.etar) | Etar Group                  | Nenhum                                                       |

Dos serviços acima, minha mais fortes recomendações são DuckDuckGo e Protonmail. Eles não só oferecem serviços mais justos e menos invasivos que os serviços do Google, como também oferecem, na minha opinião, serviços melhores. 

## Compartimentação de Credenciais

```mermaid
graph LR
A["fulano-silva@protonmail.com"] --> B{"senha123"}
B --> C("Armazenamento")
B --> D("Compras online")
B --> E("Conta no Banco")
B --> F("Rede social")
B --> G("Mensageiro")
```

```mermaid
graph LR
A["fulano-silva@protonmail.com"]
A --> AC{"6FIMql8B2t"} --> C("Armazenamento")
A --> AD{"G9AqgebUvo"} --> D("Compras online")
A --> AE{"I3JG7DYtVu"} --> E("Conta no Banco")
A --> AF{"FMRwWP5LR4"} --> F("Rede social")
A --> AG{"IVy3od4L6W"} --> G("Mensageiro")
```

```mermaid
graph LR
V["1cff58fa-4ecd-436f-a56a-7cc94d612993@anonaddy.me"] --> AC{"6FIMql8B2t"} --> C("Armazenamento")
W["931baf8d-90af-4678-8142-bde29b1ff501@anonaddy.me"] --> AD{"G9AqgebUvo"} --> D("Compras online")
X["222ad294-b826-4309-9bf3-abf539f3eb55@anonaddy.me"] --> AE{"I3JG7DYtVu"} --> E("Conta no Banco")
Y["bb60d2da-6567-44a1-9311-40197b1f4606@anonaddy.me"] --> AF{"FMRwWP5LR4"} --> F("Rede social")
Z["49d34896-cafb-4026-9ea8-c30da820e368@anonaddy.me"] --> AG{"IVy3od4L6W"} --> G("Mensageiro")
```