# Repositório de Práticas com Javascript

Este repositório foi criado para armazenar as práticas realizadas com javaScript, jQuery, requisições AJAX e consumo de JSON.

* Listas de exercicios
 > Para revisar os conceitos vistos no módulo de javascript

* Configuração básica
>Abrir uma pasta no VSCODE
Ter a extensão Live Server
Criar um arquivo index.html com a semântica básica escrita em html
Incluir Bootstrap CSS+JS (Opcional)
Incluir jQuery JS (Opcional, mas é recomendado)
Javascript especifico para a página na ultima linha útil do body, após todo o conteúdo e JS de terceiros


* Variaveis
> * Manipular html com Javascript
 - Com javascript puro (É importante saber o básico)
 - Localize um elemento no html por id
 - Localize um ou mais elementos por class
 - Localize um ou mais elementos por nome do seletor <tag>
 - Crie um novo paragrafo no body
 - Crie um novo paragrafo em algum elemento por ID,CLASS,ou seletor

> Com jQuery (É importante otimizar o trabalho)
 - Localize um elemento por ID
- Exiba em log o conteúdo desse elemento
- Exiba em log o conteúdo HTML desse elemento 
- Altere o conteúdo dese elemento por outro
- Insira um novo elemento internamente a esse com append

> Localize uma lista de elementos por class
- Converta esses elementos em uma lista e exiba de forma individual o seu conteúdo
- Altere o conteúdo desses elementos por outro

> Localize uma lista de elementos por nome de seletor
-  Converta esses elementos em uma lista e exiba de forma individual o seu conteúdo
- Altere o conteúdo desses elementos por outro

* Eventos entre HTML e JS
> Com javascript puro (É importante saber o básico)
- No html utilize o atributo de seletor onclick para executar funções existente no javascript
- No javascript crie funções para as operações matemáticas onde o resultado deve ser exibido em log

> Com jQuery(É importante otimizar o trabalho)
- No html não teve ter menção ao javascript, mas deve permitir o acesso facilitado ao mesmo por id,class ou nome do seletor
- Crie eventos de click para botoes onde a função deve exibir em log apenas que o click funcionou
- Crie evento de submit que exiba em log os dados capturados nos inputs

* CRUD
> Crie com semântica HTML uma página com um formulário e uma tabela. O formulário deve ter id nos campos para facilitar o rastreio individual.

- Botões do tipo submit disparam o submit do form
- Botão tipo reset limpa os campos habilitados
- A tabela deve ter estilo e semântica necessária para que seja acessível no jQuery
- Os eventos devem ser todos escritos no JS e também a manipulação de elementos HTML como
- Alternar visibilidade de botões
- Limpar tabela para reescrever as linhas
- Escrever linhas e colunas ta tabela
- EM cada linha botoes individuais com clicks previstos em jQuery que sabem manipular o item do loop