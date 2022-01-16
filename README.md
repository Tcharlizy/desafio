# Objetivo
O desafio basicamente consiste em ler uma API pública de previsão de tempo e implementar algumas simples funcionalidades.
•	Crie um projeto flutter. Você deverá acessar a API de previsão de tempo diretamente. Não é necessário ter um sistema Back-end de apoio.

# O Desafio
A Análise de Negócios mapeou as seguintes histórias:
1.	Mostrar as temperaturas também em graus Celsius. Só que a API só permite chamar um tipo de temperatura por vez, então vamos fazer nossa própria conversão.
2.	Permitir o usuário buscar pela cidade vai querer ver a previsão.
3.	Obter a cidade do usuário automaticamente, mesmo que aproximado e deixar pré-escolhida como padrão.
4.	Ao invés de sempre ter que procurar a cidade, as pessoas poderiam se registrar e adicionar e remover cidades favoritas.

# Detalhes técnicos
Na história 1, faça uma classe para conversão de temperaturas. Ela recebe uma temperatura em Fahrenheit (F) e converte para Celsius (C). Use essa classe para exibir a temperatura na tela, ao lado da temperatura em Fahrenheit.
Na história 2, coloque um campo de texto para passar o nome da cidade, repasse para a API, e mostre a previsão da cidade selecionada. Bônus se fizer sem que seja necessário recarregar a página.
Na história 3, obtenha a cidade aproximada do usuário de alguma forma (você pode escolher alguma biblioteca ou API que te forneça essa informação) e mostre a previsão por padrão dessa cidade selecionada.

# Orientações gerais
•	Procure focar em pequenos entregáveis. Tem flexibilidade para escolher a ordem das entregas. Tudo bem se não conseguir entregar tudo. Use o tempo disponível para apresentar a qualidade do seu código, sua criatividade e perícia em resolver problemas.
•	Nós iremos avaliar a qualidade no código, as boas práticas e sua atenção com a qualidade na implementação. Tenha atenção aos detalhes e busque tratar condições anormais de execução.
•	Caso não seja possível finalizar as histórias da maneira como você gostaria (pode ser esperado de acordo com o prazo enviado). Você pode complementar seu desafio com um texto ou comentários de como teria implementado a solução caso tivesse mais tempo.
•	O README deverá ter instruções detalhadas de como rodar a aplicação e como gerar eventuais dados necessários a aplicação.
•	Envie-nos um link para um repositório seu ou um arquivo ZIP com a sua solução.
•	Não abuse das chamadas à API do OpenWeatherMap, já que é uma conta free. Você pode configurar sua própria conta caso precise de mais chamadas.
•	Documentação da API: Current weather data - OpenWeatherMap
•	Caso tenha alguma dúvida sobre esse desafio, você pode nos encaminhar via e-mail para info@tcharlizy.co.mz
