# Prévia Linear para Vercel

Demonstração estática com dados de exemplo. Não exige banco, servidor de IA ou segredos.
As alterações ficam no navegador, não são compartilhadas entre usuários. Use apenas dados fictícios.

## Publicar

Importe este repositório na Vercel, branch `main`, framework `Other`.
O `vercel.json` define o comando `node scripts/build.mjs` e a saída `public`.
Alternativamente, neste diretório: `npx vercel login` e `npx vercel --prod`.
Se usar o pacote ZIP entregue, extraia-o e execute esses comandos no diretório extraído.
Escolha o projeto e a equipe corretos durante a vinculação. A produção só existe após o deploy terminar.

## Escopo

Leads, score, checklist, pipeline, preços, reuniões, propostas e contratos simulados são navegáveis.
A aba Plataforma explica os módulos adicionais da versão de servidor. A prévia não representa
uma reprodução completa da interface atual das 13 fases. Meet, envio de mensagens, assinatura,
inferência Hugging Face e RPA não são executados. A versão completa será hospedada separadamente.

## Validar

Execute `node scripts/build.mjs`. O deploy publica somente `public`, evitando a publicação
por acidente de documentação ou capturas da antiga página de apresentação.
