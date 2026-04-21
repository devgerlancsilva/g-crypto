# 🪙 g-crypto Pro

**g-crypto Pro** é um rastreador profissional de criptomoedas desenvolvido em Python que combina análise técnica, interface moderna no terminal e geração de relatórios executivos — **sem precisar de chaves de API**.

---

## ✨ Funcionalidades Pro

- **📊 Análise Técnica**: Cálculo automático de Médias Móveis (SMA-7 e SMA-20) para identificação de tendências.
- **📄 Relatórios PDF**: Geração de documentos profissionais com tabelas de mercado e gráficos integrados.
- **🖥️ Interface Moderna (TUI)**: Terminal interativo com tabelas coloridas, painéis e barras de progresso (via `rich`).
- **📉 Gráficos Avançados**: Visualização de histórico de preços com preenchimento de gradiente e indicadores.
- **💾 Exportação Multi-Formato**: Salva dados em `.json`, `.png` e `.pdf`.
- **🔍 Busca Inteligente**: Localize qualquer ativo listado no CoinGecko pelo nome ou símbolo.

---

## 📦 Instalação

### 1. Requisitos
- Python 3.8 ou superior.

### 2. Instalação das Dependências
```bash
pip install matplotlib pandas rich reportlab
```

---

## ▶️ Como usar

Execute o script principal:
```bash
python g_crypto.py
```

### 🌐 Modo Web em Tempo Real (HTML + Gráficos)

Para usar a aplicação no navegador com atualização automática e gráfico interativo:

```bash
python web_app.py
```

Depois abra no navegador:

```text
http://localhost:8000
```

No painel web você pode:

1. Buscar qualquer moeda por nome ou ID (ex: bitcoin, ethereum, solana).
2. Definir quantos dias de histórico deseja visualizar.
3. Ajustar o intervalo de atualização em segundos.
4. Acompanhar preço, variação 24h, market cap, volume e médias móveis (SMA-7 e SMA-20).

O programa oferece um fluxo intuitivo:
1. **Seleção**: Escolha uma moeda da lista VIP ou busque qualquer outra.
2. **Histórico**: Defina o período de análise (ex: 7, 30, 90 dias).
3. **Dashboard**: Visualize o status em tempo real no terminal.
4. **Relatórios**: Verifique os arquivos gerados na pasta do projeto.

---

## 📁 Arquivos Gerados

| Arquivo | Descrição |
|---|---|
| `report_[moeda].pdf` | Relatório executivo completo |
| `chart_[moeda].png` | Gráfico de análise técnica |
| `crypto_[moeda].json` | Dados brutos para desenvolvedores |

---

## 🛠 Tecnologias

- **Python 3.9+**
- **CoinGecko API** (Dados em tempo real)
- **Pandas** (Processamento de dados)
- **Matplotlib** (Visualização de dados)
- **Rich** (Interface de terminal)
- **ReportLab** (Geração de PDFs)

---

## 📄 Licença

MIT — Sinta-se à vontade para usar, modificar e distribuir.
