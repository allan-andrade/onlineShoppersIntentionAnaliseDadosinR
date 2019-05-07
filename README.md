# onlineShoppersIntentionAnaliseDadosinR
Análise de previsão a intenção de compra de usuários online.

Exercício tende a responder a seguinte pergunta:

Análise de dados 
 
BASE 
online_shoppers_intention.csv 
 
FONTE 
Sakar, C.O., Polat, S.O., Katircioglu, M. et al. Neural Comput & Applic (2018) 
 
CENÁRIO 
Vocês devem modelar a previsão a intenção de compra de usuários online. 
O conjunto de dados oferece informações de sessões de compra, sem tendência.  
 
DESCRIÇÃO DOS DADOS 
O conjunto de dados consiste em 10 atributos numéricos e 8 categóricos. 
O atributo binário "Revenue" indica se a sessão terminou em uma compra efetiva ou não. 
 
• "Administrative", "Administrative Duration", "Informational", "Informational Duration", "Product Related" and "Product Related Duration" represent the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories. The values of these features are derived from the URL information of the pages visited by the user and updated in real time when a user takes an action, e.g. moving from one page to another.  
 
• The "Bounce Rate", "Exit Rate" and "Page Value" features represent the metrics measured by "Google Analytics" for each page in the ecommerce site. The value of "Bounce Rate" feature for a web page refers to the percentage of visitors who enter the site from that page and then leave ("bounce") without triggering any other requests to the analytics server during that session. The value of "Exit Rate" feature for a specific web page is calculated as for all pageviews to the page, the percentage that were the last in the session. The "Page Value" feature represents the average value for a web page that a user visited before completing an e-commerce transaction.  
 
• The "Special Day" feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with transaction. The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date. For example, for Valentina’s day, this value takes a nonzero value between February 2 and February 12, zero before and after this date unless it is close to another special day, and its maximum value of 1 on February 8.  
 
• The dataset also includes operating system, browser, region, traffic type, visitor type as returning or new visitor, a Boolean value indicating whether the date of the visit is weekend, and month of the year. 
 
EXERCÍCIO 
De posse destes dados crie um modelo que indique a propensão de compra de um novo cliente com este mesmo conjunto de atributos. 
Documente seu processo de análise em um relatório com as escolhas, justificativas, testes, gráficos explicativos e qualquer outra informação que ache pertinente. 
 
