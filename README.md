# 🚀 ACOMPANHAMENTO-DE-VENDAS

<p>Bem-vindo ao projeto <strong>Acompanhamento de Vendas</strong>! Este repositório contém uma solução completa para análise e monitoramento de vendas e leads. Aqui você encontrará um dashboard interativo em Excel e consultas SQL que extraem e processam dados de vendas para gerar insights valiosos. 🎯</p>

## 📊 O que este projeto faz?

<ul>
    <li>Exibe <strong>relatórios mensais</strong> com:
        <ul>
            <li>Número de <strong>leads</strong> 📈</li>
            <li><strong>Vendas</strong> realizadas 🛒</li>
            <li><strong>Receita</strong> acumulada 💰</li>
            <li><strong>Conversão</strong> de leads em vendas (%) 📊</li>
            <li><strong>Ticket médio</strong> por venda 🎟️</li>
        </ul>
    </li>
    <li>Identifica <strong>os estados, marcas e lojas que mais venderam</strong> 🔝</li>
    <li>Analisa <strong>os dias da semana com mais visitas ao site</strong> 🌐</li>
</ul>

## 🗂️ Estrutura do Projeto

### 1. **Dashboard em Excel** 🖥️
<p>O dashboard permite visualizar de maneira clara e prática os seguintes indicadores:</p>
<ul>
    <li><strong>Receita</strong>, <strong>vendas</strong>, <strong>leads</strong> e <strong>ticket médio</strong> ao longo dos meses.</li>
    <li><strong>Top 5 estados</strong> e <strong>lojas</strong> com maior número de vendas.</li>
    <li><strong>Dias da semana</strong> com maior número de visitas ao site.</li>
</ul>

### 2. **Consultas SQL** 💾
<p>As queries SQL são responsáveis por coletar os dados diretamente do banco de dados. Algumas delas incluem:</p>
<ul>
    <li><strong>Receita e leads mês a mês</strong></li>
    <li><strong>Estados, marcas e lojas que mais venderam</strong></li>
    <li><strong>Dias com maior tráfego no site</strong></li>
</ul>

### 3. **Banco de Dados** 🗄️
<p>O projeto utiliza <strong>PostgreSQL</strong> com o <strong>pgAdmin 4</strong>, com os seguintes schemas e tabelas:</p>
<ul>
    <li><strong>Schema: Sales</strong> (Tabelas: <code>customers</code>, <code>funnel</code>, <code>products</code>, <code>stores</code>)</li>
    <li><strong>Schema: temp_tables</strong> (Tabelas: <code>customers_age</code>, <code>duplicados</code>, <code>ibge_genders</code>, <code>profissoes</code>, <code>regions</code>)</li>
</ul>

## 🚀 Como Executar o Projeto

### Requisitos:
<ul>
    <li><strong>PostgreSQL</strong> para as consultas SQL.</li>
    <li><strong>Excel</strong> para visualização do dashboard.</li>
</ul>

### Passos:
<ol>
    <li>Execute as queries SQL para gerar relatórios mensais de vendas.</li>
    <li>Visualize os dados no <strong>dashboard interativo</strong> em Excel.</li>
</ol>

## 🔧 Tecnologias Utilizadas
<ul>
    <li><strong>PostgreSQL</strong> para gerenciamento dos dados.</li>
    <li><strong>Excel</strong> para visualização dos resultados em forma de dashboard.</li>
    <li><strong>SQL</strong> para consultas e manipulação dos dados.</li>
</ul>

## 💡 Como Contribuir
<ul>
    <li>Faça um <strong>fork</strong> do repositório.</li>
    <li>Crie uma branch com sua feature: <code>git checkout -b minha-feature</code>.</li>
    <li>Faça um <strong>commit</strong> das suas alterações: <code>git commit -m 'Minha nova feature'</code>.</li>
    <li>Faça o <strong>push</strong> para a branch: <code>git push origin minha-feature</code>.</li>
    <li>Envie um <strong>Pull Request</strong>. 😉</li>
</ul>

### 🌟 Dê uma estrela se gostou do projeto e ajude a espalhar o conhecimento! ⭐
