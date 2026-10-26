# Meus Centros

App de tarefas organizado por centros (Trabalho, Escola, Pessoal, Igreja…), com prioridade automática, quadro Kanban, metas e envio da agenda para o Gmail e o Google Agenda.

## Estado atual

Protótipo em uma página (`public/index.html`), sem build. Os dados ficam salvos no navegador (localStorage). Os eventos da agenda do Início ainda são exemplos.

## Rodar localmente

```bash
npx firebase-tools emulators:start --only hosting
```

## Publicar

```bash
npx firebase-tools deploy --only hosting
```

## Próximos passos

- Login com Google (Firebase Authentication)
- Tarefas, metas e centros no Firestore, sincronizados entre aparelhos
- Sincronização com o Google Calendar pela API
