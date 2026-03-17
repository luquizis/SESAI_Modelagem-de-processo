# Ecossistema SESAI — Fluxo de Execução Direta

Plataforma de validação colaborativa do fluxo de **Obra de Execução Direta** do SESAI.

## 🌐 Como colocar online (GitHub Pages)

### 1. Criar repositório no GitHub
1. Acesse [github.com](https://github.com) e faça login
2. Clique em **New repository**
3. Nome sugerido: `sesai-fluxo`
4. Marque como **Public**
5. Clique em **Create repository**

### 2. Fazer upload dos arquivos
Faça upload dos 3 arquivos para a raiz do repositório:
- `index.html`
- `flow.html`
- `bpmn.html`

### 3. Ativar GitHub Pages
1. No repositório, vá em **Settings → Pages**
2. Em **Source**, selecione `Deploy from a branch`
3. Em **Branch**, selecione `main` e pasta `/ (root)`
4. Clique em **Save**

### 4. Acessar a plataforma
Após 1-2 minutos, a plataforma estará disponível em:
```
https://seu-usuario.github.io/sesai-fluxo
```

---

## 📁 Estrutura dos arquivos

```
sesai-fluxo/
├── index.html   ← shell principal com as abas
├── flow.html    ← fluxo interativo passo a passo (13 etapas)
├── bpmn.html    ← editor BPMN com bpmn-js
└── README.md
```

---

## 🧭 Funcionalidades da plataforma

### Aba 1 — Fluxo Interativo
- Percurso guiado das 13 etapas da Execução Direta
- Cada etapa abre com descrição, itens, documentos gerados e alertas
- Botão "Comentar" em cada etapa para enviar contribuição
- Progresso por fase e mapa do fluxo no painel lateral

### Aba 2 — Editor BPMN
- Diagrama BPMN completo carregado (7 pools × 13 tarefas)
- Edição de nomes e descrições por clique
- Exportar como `.bpmn` (XML) ou `.svg`
- Importar arquivo `.bpmn` externo
- Restaurar diagrama original

### Aba 3 — Contribuições
- Registro de feedback por ator/função
- Tipos: validação, sugestão, problema, dúvida
- Vinculado a etapa específica
- Estatísticas em tempo real

---

## 👥 Atores do processo

| Ator | Cor | Responsabilidade |
|------|-----|-----------------|
| DSEI / Gabinete | 🔵 | Aprovação, designação, encerramento SEI |
| SESANI | 🟢 | Responsável técnico central |
| SEOFI | 🟡 | Financeiro, SIAFI, almoxarifado |
| SELOG | 🟨 | Logística, cadastro de obras |
| SEPAT | 🩵 | Patrimônio, retirada de material |
| DEAMB / COABS | 🟣 | Validação, ART, conclusão |
| Comunidade | 🟠 | Participação, recebimento da obra |

---

## ⚠️ Dificuldades mapeadas

- Falta de padronização nos registros de entrada e saída de materiais
- Conectividade limitada (necessário modo offline)
- Falta de rastreabilidade do material até o ponto de uso
- Escassez de pessoal técnico (AISANs) para acompanhamento em campo

---

*Versão 3.0 — Ecossistema SESAI*
