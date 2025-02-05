# Página de Redirecionamento

Este projeto consiste em uma simples página HTML que redireciona os usuários automaticamente para uma URL específica. O propósito é facilitar o acesso a uma página do Notion que contém informações sobre relatórios e painéis de controle de dados gerenciais.

## URL de Destino

O redirecionamento levará o usuário para a seguinte página:

[Módulo 9 - SI: Relatórios e Painéis de Controle de Dados Gerenciais](https://cobalt-blarney-8b3.notion.site/M-dulo-9-SI-Relat-rios-e-Pain-is-de-Controle-de-Dados-Gerenciais-123256ceaea78055b7b4c38aed637d74)

## Como Funciona

O HTML utiliza uma meta tag de redirecionamento que automaticamente leva o usuário para a URL alvo assim que a página é carregada.

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="refresh" content="0; url='https://cobalt-blarney-8b3.notion.site/M-dulo-9-SI-Relat-rios-e-Pain-is-de-Controle-de-Dados-Gerenciais-123256ceaea78055b7b4c38aed637d74'" />
    <title>Redirecionamento</title>
</head>
<body>
    <p>Se você não foi redirecionado automaticamente, <a href="https://cobalt-blarney-8b3.notion.site/M-dulo-9-SI-Relat-rios-e-Pain-is-de-Controle-de-Dados-Gerenciais-123256ceaea78055b7b4c38aed637d74">clique aqui</a>.</p>
</body>
</html>
