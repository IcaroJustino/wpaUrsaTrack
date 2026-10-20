---
titulo: Guia de Execucao e Testes
tags:
  - documentacao
  - angular
  - setup
  - testes
criado: 2026-10-20
atualizado: 2026-10-20
status: revisado
aliases:
  - Guia do Projeto
  - Execucao e Testes
---

# Guia de Execucao e Testes

## Resumo Direto
Instrucoes basicas para instalacao de dependencias, inicializacao do servidor de desenvolvimento, execucao da suite de testes unitarios e compilacao do projeto WpaUrsaTrack.

## Pre-requisitos
- Node.js versao 20 ou superior recomendada.
- Gerenciador de pacotes npm versao 10 ou superior.

## Instalacao

Para instalar todas as dependencias necessarias:

```bash
npm install
```

## Execucao em Desenvolvimento

Para iniciar o servidor local de desenvolvimento com recarregamento automatico:

```bash
npm start
```

Ou diretamente pelo Angular CLI:

```bash
ng serve
```

A aplicacao ficara acessivel no navegador em:
```text
http://localhost:4200/
```

## Execucao de Testes

O projeto utiliza o Vitest como executor de testes unitarios integrados ao Angular.

Para executar os testes:

```bash
npm test
```

Ou via CLI:

```bash
ng test
```

## Compilacao e Build

### Build de Producao
Gera os arquivos otimizados para producao no diretorio `dist/`:

```bash
npm run build
```

### Build em Modo Observador
Compila a aplicacao em modo de desenvolvimento observando alteracoes nos arquivos:

```bash
npm run watch
```

## Variaveis de Ambiente

As configuracoes locais e parametros da aplicacao podem ser definidos em arquivos de ambiente na raiz do projeto (como `.env`), definindo valores para portas, URLs de APIs e flags de recursos.

## Conexoes
- [[Configuracoes de Ambiente]]
- [[Arquitetura da Aplicacao]]
