# Checklist Diário

Checklist de tarefas que se repete todo dia. Cada dia fica gravado com o que foi feito e o horário em que foi marcado, e qualquer dia pode ser exportado em CSV ou TXT.

## Funções

- Tarefas diárias (voltam todo dia) ou só para hoje
- Horário limite opcional por tarefa, com alerta de atraso na página e notificação do sistema (se ativada)
- Aviso a partir das 17h com o que ainda falta
- Lembrete do último dia salvo com o que ficou pendente
- Histórico por dia com exportação em CSV (abre no Excel) e TXT
- Backup e restauração em JSON

## Onde os dados ficam

Tudo é salvo no `localStorage` do navegador. Não tem servidor. Isso significa que os dados ficam presos ao navegador e ao endereço onde a página roda: o que você marca no PC não aparece no celular. Para levar os dados de um lugar para outro, use "Baixar backup" e depois "Restaurar backup" no outro navegador. Limpar os dados do site no navegador apaga o histórico, então vale baixar um backup de vez em quando.

## Publicar no GitHub Pages

1. Crie um repositório e suba o `index.html` e este `README.md` na raiz.
2. Em Settings > Pages, escolha "Deploy from a branch", branch `main`, pasta `/ (root)`.
3. O site fica em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.

Para rodar local, basta abrir o `index.html` no navegador. As notificações do sistema só funcionam em HTTPS (como no GitHub Pages).
