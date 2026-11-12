# Formato da app Script Spot

App: https://scriptspotaeroagency.lovable.app — gestão de guiões de vídeo.

## Campos de cada script

| Campo | Notas |
|---|---|
| Título | Nome do vídeo. Os títulos de "Variação" e "Remake" levam o prefixo `Variação \|` ou `Remake \|`. |
| Categoria | Usada para arquivar em pastas `ano / mês / tema`. Categorias em uso: `AI`, `Big Query`, `Server-Side`, `Youtube`, `Dicas Gerais`, `Auditoria`, `Comunidade WhatsApp`, `Recuperação Encomendas \| Métodos de Pagamento`. Para Black Friday usar `Black Friday`. |
| Hooks | Lista de variações do hook. Os melhores scripts têm 6 a 10. |
| Script | Corpo principal. |
| CTA | Uma linha. |
| Estado | `por_gravar` ao importar; passa a `gravado` na app. |

## Marcadores do teleponto

A app pinta a amarelo dois marcadores dentro do script:

- `[↺]` — início de bloco / novo take. Põe-se no início de cada bloco de ideia.
- `[/]` — fim de frase / pausa. Opcional; os scripts de agosto não o usam e funcionam bem.

Indicações de realização vão entre parênteses retos em maiúsculas, numa linha própria: `[APONTAR PARA CIMA]`, `[IMAGEM: stand — Porsche 911, 280.000€]`.

## Importação em bulk

Botão "Importar em bulk" na app. Cola-se texto com este formato; cada script separado por **uma linha em branco antes de `Título:`**.

```
Título: Nome do vídeo
Categoria: Dicas Gerais
Hooks:
Primeira variação do hook.
Segunda variação do hook.
Script:
[↺] Primeira linha do bloco.
Segunda linha.
[↺] Novo bloco.
CTA: Queres saber quanto a tua loja está a perder? Clica aqui.
```

Regras do parser (lidas do código da app):

- `Título:`, `Categoria:` (ou `Tema:`), `Hooks:`, `Script:` (ou `Script Principal:`), `CTA:` no início da linha.
- Depois de `Hooks:`, cada linha não vazia é um hook até aparecer outro campo.
- Depois de `Script:`, as linhas juntam-se ao script; **as linhas em branco são ignoradas**, por isso os blocos marcam-se com `[↺]` e não com linhas vazias.
- **Não pôr linhas em branco dentro de um script seguidas de uma linha começada por `Título:`**, senão parte o script em dois.
- Depois da importação a app arquiva sozinha por `ano · mês · tema`.

## Exportar

"Exportar backup" descarrega um JSON com todos os scripts (`scripts[]` com `title`, `category`, `hooks`, `mainScript`, `cta`, `status`, `createdAt`, `recordedAt`, `folderId`). A cópia de 12 nov 2026 está em [../fontes/scripts-app/](../fontes/scripts-app/).
