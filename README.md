# SESAI — Fluxo de Execução Direta · Plataforma de Validação

Plataforma institucional para validação colaborativa do fluxo de **Obra de Execução Direta** da Secretaria Especial de Saúde Indígena (SESAI) / Ministério da Saúde.

---

## 🌐 Como publicar no GitHub Pages (5 minutos)

### 1. Criar repositório
1. Acesse [github.com](https://github.com) e faça login
2. Clique em **New repository**
3. Nome sugerido: `sesai-fluxo`
4. Marque como **Public** → **Create repository**

### 2. Fazer upload
Faça upload dos arquivos para a raiz do repositório:
```
index.html   ← plataforma principal
flow.html    ← fluxo interativo
bpmn.html    ← editor BPMN
README.md
```

### 3. Ativar GitHub Pages
**Settings → Pages → Source: Deploy from branch → main / root → Save**

### 4. Acessar
```
https://seu-usuario.github.io/sesai-fluxo
```

---

## 🔑 Credenciais de acesso (modo de edição)

| Usuário | Senha | Perfil |
|---------|-------|--------|
| `editor` | `sesai2024` | Editor de fluxo |
| `admin` | `sesai@admin` | Administrador |

> Para adicionar novos usuários, edite o objeto `USERS` no `index.html`.

---

## 📋 Funcionalidades

### Aba 1 — Fluxo Interativo
- 13 etapas desbloqueáveis sequencialmente
- Descrição detalhada, itens, documentos e alertas por etapa
- Botão **"Comentar"** em cada etapa → abre formulário de contribuição
- Modo de edição: botão **"Editar"** nas etapas (título e descrição editáveis)
- Edições salvas no navegador (localStorage)

### Aba 2 — Diagrama BPMN
- Diagrama BPMN completo com 7 raias (pools) e todos os atores
- **Somente leitura** para visitantes
- **Modo de edição** (login): clique em qualquer elemento para editar propriedades
- Exportar: `.bpmn` (XML padrão) e `.svg`
- Importar arquivo `.bpmn` externo

### Aba 3 — Contribuições
- Registro aberto para todos (sem login)
- Tipos: ✅ Validação, 💡 Sugestão, ⚠️ Problema, ❓ Dúvida
- Vinculado a etapa específica
- **Modo de edição**: marcar como resolvido, excluir

---

## 👥 Atores do processo

| Ator | Responsabilidade |
|------|-----------------|
| DSEI / Gabinete | Aprovação, designação, encerramento SEI |
| SESANI | Responsável técnico central |
| SEOFI | Financeiro, SIAFI, almoxarifado |
| SELOG | Logística, cadastro de obras |
| SEPAT | Patrimônio, retirada de material |
| DEAMB / COABS | Validação, ART, conclusão |
| Comunidade | Participação, recebimento da obra |

---

*SESAI · Secretaria Especial de Saúde Indígena · Ministério da Saúde · v4.0*
