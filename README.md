## <img src="https://clubpetro.com/wp-content/themes/clubpetro/src/images/logo-clubpetro-color.svg" alt="ClubPetro" width="76" /> Desafio QA

Parabéns! Se você chegou até aqui significa que você passou pelas etapas mais difíceis do nosso processo seletivo. Somos extremamente criteriosos com as pessoas que vão integrar nosso time porque só aceitamos pessoas incríveis!

Agora é a parte fácil. Chegou a hora de mostrar todas as suas habilidades de transformar café em código. Vamos lá?

Nesse desafio iremos avaliar suas habilidades em:

* **JavaScript**
* **Postman**
* **Cypress**

## Postman

No dia-a-dia de trabalho uma de suas atribuições será validar a API do nosso produto. Portanto, vamos testar seu domínio do Postman e sua capacidade de interpretar e descrever um caso de uso.

Escolha na lista de APIs públicas (https://github.com/public-apis/public-apis) por uma API de sua preferência e crie uma coleção no Postman que execute 3 casos de uso utilizando disponíveis nesta API. 

Por exemplo:

* **Unsplash** https://unsplash.com/documentation#search-photos 
* Caso de uso **“Search Photos”**
* Documente o **cenário** e o **retorno esperado**
* Crie a **request**

## Automação (Cypress)

Nesta etapa, você fará a validação de uma página da web, neste caso, a nossa landing page https://clubpetro.com/
Analise a página e crie uma automação que valide os seguintes cenários:

Obs: As linhas marcadas com um (*) no final, não é obrigatório para o desafio de automação, será mais um diferencial

- Em nossa navbar, temos o item "O ClubPetro", devemos validar se quando o usuário interagir com um clique neste item,
ele abrirá o Dropdown Menu com mais três itens;
- Dentre esses três itens do Dropdown Menu, vamos validar se ao clicar no item "Quem Somos" acontece o redirecionamento
para a página https://clubpetro.com/sobre
- Validar URL após o redirecionamento*;
- Validar o carregamento do texto descritivo "Feito de revendedor para revendedor", na página sobre;
- Ainda na mesma página, devemos validar o carregamento da imagem do CEO da ClubPetro*;
- Ainda na mesma página, devemos validar o carregamento do vídeo "O que é o ClubPetro"*;
- Ainda na mesma página, devemos descer até o final e validar se todo o texto de copyright está escrito da maneira correta:
"2021 ClubPetro. Todos os direitos reservados.";
- Voltando a interagir com a navbar, devemos validar o redirecionamento do item "Contato";
- Validar URL após o redirecionamento*;
- Ainda na página de contato, deve-se preencher o formulário e enviar;
- Validar confirmação de envio*;

## Requisitos

* O projeto precisa estar configurado para rodar em um ambiente macOS ou Ubuntu.
* Deve anexar ao seu projeto a coleção do postman com todos os endpoints validados e exemplos de utilização.

**Para executar seu código devemos executar apenas os seguintes comandos**:

* git clone $seu-fork
* cd $seu-fork
* comando para instalar dependências
* comando para executar a aplicação

## Critério de avaliação

* **Organização do código**
* **Clareza**
* **Assertividade**
* **Legibilidade do código**
* **Reaproveitamento de código**
* **Escolhas técnicas**

## Dúvidas

Quaisquer dúvidas que você venha a ter, consulte as issues para ver se alguém já não a fez e caso você não ache sua resposta, abra você mesmo uma nova issue!

Ao completar o desafio, submeta um pull-request a esse repositório com uma breve explicação das decisões tomadas e principalmente as instruções para execução do projeto.

**Boa sorte! ;)**
