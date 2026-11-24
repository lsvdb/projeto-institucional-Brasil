# Guia de Contribuição e Revisão Técnica

Obrigado pelo interesse em revisar e aprimorar o **Projeto Institucional para o Desenvolvimento**.

Este repositório utiliza a lógica de desenvolvimento aberto (*open source*) aplicada a políticas públicas: qualquer cidadão, pesquisador, jurista, economista ou gestor pode apontar falhas, propor dados atualizados ou sugerir novas redações. Todas as alterações passam por curadoria técnica transparente antes de serem incorporadas à versão consolidada (`branch main`).

---

## 1. Princípios da Curadoria

Para que uma sugestão seja incorporada ao documento oficial, ela deve observar quatro critérios objetivos:

1. **Rigor e Fontes Verificáveis:** Toda afirmação quantitativa ou diagnóstico institucional deve citar fontes oficiais (Tesouro Nacional, IBGE, CNJ, CGU, FGV, OCDE, CEPEJ) ou literatura acadêmica revisada por pares.
2. **Viabilidade Constitucional:** Propostas de alteração legislativa ou emenda constitucional devem respeitar as cláusulas pétreas da Constituição Federal de 1988 (Art. 60, § 4º) e o princípio da segurança jurídica/direito adquirido.
3. **Caráter Suprapartidário:** O foco é a arquitetura de incentivos das instituições, nunca ataques pessoais ou defesa de partidos e lideranças específicas.
4. **Clareza e Concisão:** O documento foi desenhado como uma Nota Técnica executiva de leitura ágil, mantendo rigor acadêmico sem jargão excessivo.

---

## 2. Como Enviar Sugestões

### Opção A — Para Pesquisadores e Colaboradores sem Familiaridade com Git (Interface Web)

Você não precisa instalar nenhum programa nem saber programar para contribuir:

1. Acesse a aba [**Issues**](https://github.com/lsvdb/projeto-institucional-Brasil/issues) no topo deste repositório (será necessário apenas uma conta gratuita no GitHub).
2. Clique no botão verde **"New issue"**.
3. No **Título**, indique o eixo e o resumo do ponto (ex.: `[Sistema Eleitoral] Fragilidade na regra de transição dos distritos`).
4. Na **Descrição**, apresente sua crítica técnica, sugestão de redação ou referência bibliográfica e clique em **"Submit new issue"**.

### Opção B — Para Colaboradores Familiarizados com Git / GitHub (Pull Request)

1. Faça um **Fork** deste repositório.
2. Crie uma branch descritiva a partir da `main`:\
   git checkout -b revisao/eixo-judiciario-metricas
3. Realize suas alterações nos arquivos em Markdown e faça commits claros explicando o motivo técnico da mudança.
4. Envie um **Pull Request** detalhando:
    - Qual seção foi alterada;
    - Qual problema jurídico, fiscal ou institucional a alteração corrige;
    - Quais referências ou dados fundamentam a mudança.

---

## 3. Modelos de Contribuição

Ao abrir uma **Issue** ou **Pull Request**, utilize preferencialmente um dos formatos abaixo para agilizar a análise:

### A) Crítica Constitucional ou Jurídica

- **Seção / Item:** (ex.: Item 3.1 — Mandatos Fixos no STF)
- **Risco ou Fragilidade Identificada:** (ex.: conflito com o Art. X da CF/88 ou jurisprudência do STF)
- **Proposta de Ajuste:** (como mitigar o risco sem perder o objetivo institucional)
- **Referência:** (doutrina, artigo ou precedente)

### B) Atualização de Dados, Gráficos ou Fontes

- **Gráfico / Dado:** (ex.: Gráfico 1 — Emendas Parlamentares)
- **Dado Atualizado:** (valor, período de apuração e metodologia)
- **Fonte Oficial:** (link direto para o relatório ou base de dados pública)

### C) Sugestão de Redação / Novo Mecanismo

- **Texto Atual:** (trecho que deseja aprimorar)
- **Texto Sugerido:** (nova redação proposta)
- **Justificativa:** (impacto esperado sobre incentivos políticos, fiscais ou administrativos)

---

## 4. Política de Versionamento e Créditos

Adotamos o versionamento semântico adaptado a documentos públicos (`vMAJOR.MINOR.PATCH`):

- **`PATCH`** **(`v1.0.1`):** Correções ortográficas, ajustes de formatação, atualização de links ou correções pontuais de citações.
- **`MINOR`** **(`v1.1.0`):** Atualização de séries históricas de dados, incorporação de novas referências bibliográficas ou refinamentos técnicos dentro dos eixos existentes.
- **`MAJOR`** **(`v2.0.0`):** Mudança estrutural em alguma proposta central ou inclusão de um novo eixo temático de reforma.

### Registro de Alterações e Reconhecimento

- Toda contribuição aceita é registrada publicamente no arquivo `CHANGELOG.md` com a data, o resumo da mudança e o link para a discussão original.
- Pesquisadores e colaboradores que tiverem sugestões incorporadas podem optar por incluir seu nome e afiliação institucional na seção de **Revisão Técnica e Contribuições** das versões seguintes — ou permanecer anônimos, caso prefiram.
