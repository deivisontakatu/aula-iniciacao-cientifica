## 8️⃣ Dados e Resultados

A organização estruturada dos dados garante **reprodutibilidade científica**, transparência metodológica e rastreabilidade dos resultados obtidos no projeto.

Todos os dados deverão estar versionados e organizados no repositório conforme padrão definido.

---

### 📂 Dados Brutos

- Dados coletados diretamente da fonte (sensores, questionários, APIs, experimentos).
- Arquivos originais sem alteração.
- Identificação clara de data e origem.
- Armazenamento em `/data/bruto`.
- Não devem ser sobrescritos.

Requisitos:
- Descrição da fonte.
- Descrição do método de coleta.
- Registro de variáveis.

---

### 📊 Dados Tratados

- Dados após limpeza, filtragem e padronização.
- Scripts utilizados para tratamento devem estar documentados.
- Armazenamento em `/data/tratado`.
- Manter rastreabilidade entre dado bruto e dado tratado.

Requisitos:
- Explicação das transformações realizadas.
- Justificativa metodológica para exclusões ou ajustes.
- Versionamento das bases.

---

### 💻 Scripts de Análise

- Scripts estatísticos ou computacionais.
- Devem conter comentários explicativos.
- Linguagens recomendadas: Python, R, MATLAB (ou conforme área).
- Armazenamento em `/src/experimentos`.

Boas práticas:
- Código modular.
- Reprodutibilidade garantida.
- README explicando como executar.
- Indicação de dependências e versões.

---

### 📈 Relatórios Estatísticos

- Resultados descritivos.
- Testes estatísticos aplicados.
- Intervalos de confiança.
- Nível de significância adotado.
- Justificativa da escolha do teste.

Armazenamento em `/docs/relatorios`.

---

### 📉 Gráficos

- Devem possuir título, legenda e descrição.
- Indicação clara das variáveis analisadas.
- Padronização visual.
- Exportação em formato vetorial quando possível.

Armazenamento em `/docs/graficos`.

---

📌 Todo resultado apresentado em artigo ou relatório deve possuir vínculo direto com os dados e scripts que o originaram.
