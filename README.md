<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Bem-vindo ao Sistema de Gerenciamento de Fazenda Bananeira</h1>
    <p>Este é um sistema simples para gerenciar o gado, a produção de leite e a equipe de funcionários de uma fazenda.</p>
    <h2>Funcionalidades</h2>
    <ul>
        <li><strong>Gerenciar Gado</strong>: Registrar, remover e visualizar bovinos.</li>
        <li><strong>Gerenciar Produção</strong>: Registrar e visualizar a produção de leite.</li>
        <li><strong>Gerenciar Equipe</strong>: Registrar, demitir e visualizar funcionários da fazenda.</li>
    </ul>
    <h2>Estrutura do Sistema</h2>
    <p>O sistema possui as seguintes classes:</p>
    <ul>
        <li><strong>Bovine</strong>: Representa um bovino com propriedades como nome, gênero, raça, idade, peso e valor de mercado.</li>
        <li><strong>MilkProduction</strong>: Representa a produção de leite com data e quantidade.</li>
        <li><strong>Employee</strong>: Representa um funcionário da fazenda com informações como nome, cargo, salário, idade e gênero.</li>
    </ul>
    <h2>Funcionalidades Detalhadas</h2>
    <h3>Gerenciamento de Gado</h3>
    <p>O usuário pode:</p>
    <ul>
        <li>Registrar novos bovinos com informações detalhadas como nome, gênero, raça, idade, peso e valor de mercado.</li>
        <li>Remover bovinos do cadastro.</li>
        <li>Visualizar todos os bovinos cadastrados.</li>
    </ul>
    <h3>Gerenciamento de Produção de Leite</h3>
    <p>O usuário pode:</p>
    <ul>
        <li>Registrar novas produções de leite, incluindo data e quantidade produzida.</li>
        <li>Visualizar todas as produções registradas.</li>
    </ul>
    <h3>Gerenciamento de Equipe</h3>
    <p>O usuário pode:</p>
    <ul>
        <li>Registrar novos funcionários com informações como nome, cargo, salário, idade e gênero.</li>
        <li>Demitir funcionários da equipe.</li>
        <li>Visualizar todos os funcionários cadastrados.</li>
    </ul>
    <h2>Como Usar</h2>
    <ol>
        <li>Ao iniciar o sistema, o usuário deve se logar com nome de usuário e senha.</li>
        <li>Após o login, o menu principal será exibido, onde o usuário poderá escolher qual área deseja gerenciar: Gado, Produção ou Equipe.</li>
        <li>Escolha uma das opções e siga os prompts para registrar, remover ou visualizar os dados.</li>
        <li>Para sair, basta escolher a opção "Sair" no menu principal.</li>
    </ol>
    <h2>Observações</h2>
    <p>O sistema não possui uma interface gráfica e é executado diretamente no terminal. As interações são feitas através de prompts de texto e o usuário deve inserir as informações de acordo com as instruções fornecidas.</p>
</body>
</html>
