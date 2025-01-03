<div align="center">
		<h1>🚀Código Postal Challenge</h1>
    <br>
</div>

## 📚Introdução
Gostaríamos de propor um exercício prático que envolva o enriquecimento de dados de geolocalização da nossa empresa. O objetivo é que o candidato desenvolva uma solução para complementar as informações de um conjunto de dados com informações de concelho e distrito. Este desafio permitirá avaliar a capacidade de automatização, integração de dados e construção de APIs.

## 🧩Desafio
1) 📂Dados de Entrada:
   
   Um ficheiro CSV será fornecido contendo uma lista de códigos postais (CP7) Podes consulta o mesmo aqui.

3) 🎯Tarefa:
   
   Utilizando ferramentas de pesquisa, sites com informações de Códigos Postais ou APIs disponíveis na internet, deverás encontrar as informações correspondentes ao concelho e distrito para cada código postal.

5) ⚙️Processo:

   Desenvolve um script ou programa que automatize essa busca e enriquecimento dos dados.
   Complementa o código postal presente no CSV com as informações de concelho e distrito.

4) 💾Armazenamento dos Dados:

   O resultado final deve ser salvo em uma tabela num banco de dados.

6) Estrutura mínima da tabela:
   
   codigo_postal (string ou varchar)
   
   concelho (string ou varchar)
   
   distrito (string ou varchar)

<div align="center">
    <br>
		<h1>
        🚀 Desafio Bônus: API para Consulta dos Dados
    </h1>
    <br>
</div>
Desenvolver um serviço de API para o acesso à tabela criada no desafio base.

Permitir consultas aos dados enriquecidos diretamente pela API.

🔗 Requisitos:

Endpoints:

GET /codigos_postais: Retorna todos os registros.

GET /codigos_postais/{codigo_postal}: Retorna o registro correspondente ao código postal informado.

Formato de resposta:

JSON contendo as informações do código postal, concelho e distrito.

<div align="center">
    <br>
		<h1>
        🛠️ Sugestão de Ferramentas
    </h1>
    <br>
</div>

Linguagem: Python

Banco de Dados: MySQL, PostgreSQL, SQLite, MariaDB, Oracle, outros

<div align="center">
    <br>
		<h1>
        📦 Entrega
    </h1>
    <br>
</div>

Disponibilizar o código desenvolvido no GitHub e compartilhar o link do projeto.

Enviar o CSV com os dados enriquecidos para manoel.leal@nos.pt

<div align="left">
    <br>
		<h1>
        🍀 Boa sorte!
    </h1>
    <br>
</div>


