# Diagnóstico de entrada e publicação

**Verificado em:** 17/11/2026  
**Projeto Vercel:** `academiaiasobmedida`  
**Domínio de produção:** https://academiaiasobmedida.vercel.app

## Evidências verificadas

- A rota pública principal respondeu com HTTP 200 e entregou HTML da Academia IA Sob Medida.
- O último deployment de produção consultado estava em estado `READY`, associado à branch `main` e ao commit `82ff87f2c624efc4cdc40a9d44e5c7461a79a0ea`.
- O HTML servido na rota principal corresponde à estrutura e ao conteúdo do `index.html` localizado na raiz do repositório na branch `main`.
- O projeto Vercel reporta `framework: null`. Na raiz do repositório consultada não há `package.json`, `vercel.json` nem configuração de build de framework.
- Existe também `src/index.html`, uma implementação HTML alternativa/legada, com estrutura diferente. Ela não é o arquivo servido pela rota principal verificada nesta auditoria.
- A branch `feat/padrao-aprendizagem-imersiva-pch` não tinha deployment de preview listado na Vercel no momento da consulta.

## Decisão operacional

Para as próximas alterações desta branch, tratar o `index.html` da raiz como o ponto de entrada atualmente comprovado da página principal. Não alterar `src/index.html` até que seu papel seja identificado em uma decisão separada.

## Limites e cautelas

- Esta verificação confirma a origem do HTML da rota principal, mas não substitui um teste funcional completo em navegador, dispositivos móveis, áudio, armazenamento local, acessibilidade ou responsividade.
- A ausência de preview para a branch significa que as alterações em desenvolvimento não foram verificadas em uma URL de pré-visualização.
- O deployment de produção observado utiliza `main`; os commits desta branch não devem ser considerados publicados.
- Nenhum merge ou novo deployment foi realizado nesta etapa.
- Repetir a verificação antes de qualquer publicação, pois configurações e branches podem mudar.
