# 🏭 Sistema Preditivo de Gestão de Tanques para Refinaria

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

## 🎯 Contexto e Origem do Projeto

Em **2004**, ainda como **Operador de Console na ExxonMobil** (antes mesmo de me formar em Engenharia), identifiquei uma necessidade operacional crítica: supervisores e operadores precisavam antecipar o enchimento de tanques para:

- 📦 Programar recebimento de matéria-prima
- 🧪 Preparar material para amostragem laboratorial  
- ⚙️ Otimizar a sequência de atividades operacionais

**Solução desenvolvida na época**: Utilizei recursos de extração de dados do Excel conectado ao sistema DCS para criar um dashboard que calculava:
- ⏱️ Previsão de tempo para enchimento de tanques
- 💧 Vazões em tempo real
- 📊 Yield (rendimento) dos produtos

Este dashboard apoiou decisões operacionais por **vários anos** na unidade.

## 🔄 Recriação Moderna (2025)

Este projeto é uma **recriação moderna** daquele sistema, utilizando Python e stack tecnológica atual para demonstrar:

1. ✅ Como problemas operacionais reais podem ser resolvidos com análise de dados
2. ✅ Minha capacidade de traduzir conhecimento de processo em código
3. ✅ Aplicação prática de Python, Pandas e visualização de dados em contexto industrial

## 📊 Funcionalidades

- ✅ **Simulação de Dados de Processo**: Geração de dados realistas simulando DCS/PI System
- ✅ **Cálculo Preditivo**: Previsão de tempo para enchimento de tanques com base em vazões
- ✅ **Análise de Yield**: Cálculo automático de rendimento de produtos
- ✅ **Dashboard Operacional**: Visualizações com alertas automáticos em tempo real
- ✅ **Relatórios de Programação**: Geração de relatórios para planejamento de atividades
- ✅ **Sistema de Alertas**: Notificações automáticas para níveis críticos

## 🛠️ Stack Tecnológica

- **Python 3.x**: Linguagem principal do projeto
- **Pandas**: Manipulação e análise de dados de processo
- **NumPy**: Cálculos numéricos e simulações
- **Matplotlib**: Visualização de dados
- **Seaborn**: Gráficos estatísticos avançados

## 📁 Estrutura do Projeto

```
tank-management-system/
├── src/
│   ├── __init__.py
│   ├── data_generator.py      # Simulação de dados DCS/PI
│   ├── tank_manager.py         # Classe GestorTanques
│   ├── analytics.py            # Cálculos de yield e KPIs
│   ├── visualization.py        # Dashboards e gráficos
│   └── reporting.py            # Relatórios de previsão
├── data/
│   ├── raw/                    # Dados brutos simulados
│   └── processed/              # Dados processados
├── output/
│   └── dashboards/             # Dashboards gerados
├── notebooks/                  # Análises exploratórias
├── tests/                      # Testes unitários
├── main.py                     # Script principal de execução
├── .gitignore
├── requirements.txt            # Dependências do projeto
└── README.md
```

## ⚙️ Como Executar

### Pré-requisitos

- Python 3.8 ou superior
- pip (gerenciador de pacotes Python)

### Instalação

1. Clone o repositório:

```bash
git clone https://github.com/fqgiord/tank-management-system.git
cd tank-management-system
```

2. Crie um ambiente virtual (recomendado):

```bash
python -m venv venv
source venv/bin/activate  # No Windows: venv\\Scripts\\activate
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

### Execução

Execute o script principal:

```bash
python main.py
```

O sistema irá:
1. Gerar dados de processo simulados (7 dias)
2. Calcular yields e KPIs operacionais
3. Simular enchimento de tanques
4. Gerar dashboard operacional (salvo em `output/dashboards/`)
5. Exibir relatório de previsão no console

## 📊 Exemplo de Uso

Após executar o sistema, você terá:

- **Dashboard Visual**: Arquivo `dashboard_operacional.png` com 4 gráficos principais
- **Dados Processados**: CSV com histórico completo em `data/processed/`
- **Relatório Console**: Previsões de enchimento e alertas operacionais

### Saída do Relatório

```
📋 RELATÓRIO DE PREVISÃO - PROGRAMAÇÃO DE ATIVIDADES
═══════════════════════════════════════════════════

🛢️ TANQUE A:
   Nível atual: 850 m³ (85.0%)
   ⚠️ Alarme em: 4.2 horas (20/01 18:30)
   📝 Ação: Preparar material para amostragem
```

## 🚀 Impacto

**Original (2004)**: 
- Melhorou programação de atividades operacionais
- Reduziu tempo de resposta para decisões críticas
- Otimizou logística de recebimento de matéria-prima

**Potencial com Stack Moderna**: 
- 🔌 Integração direta com sistemas DCS/PI via APIs
- 📧 Alertas automáticos via email/SMS
- 🤖 Machine Learning para previsões mais precisas
- 🌐 Dashboard web em tempo real com atualização automática
- 📱 Aplicativo mobile para acompanhamento remoto

## 💡 Lições Aplicadas

Este projeto demonstra minha trajetória de **20+ anos aplicando pensamento analítico** em operações industriais, agora formalizado com ferramentas modernas de Data Science e Engenharia de Software.

**Competências demonstradas**:
- ✅ Resolução de problemas operacionais reais
- ✅ Tradução de conhecimento de domínio em código
- ✅ Desenvolvimento de sistemas preditivos
- ✅ Visualização de dados para suporte à decisão
- ✅ Arquitetura de software modular e escalável

## 🔧 Melhorias Futuras

- [ ] Integração com APIs de sistemas DCS reais (OPC UA, PI Web API)
- [ ] Implementar modelos de Machine Learning para previsões adaptativas
- [ ] Dashboard web interativo com Streamlit ou Dash
- [ ] Sistema de notificações (email, SMS, Telegram)
- [ ] Análise de anomalias e detecção de padrões
- [ ] Otimização automática de sequências operacionais
- [ ] Integração com sistemas ERP para programação logística
- [ ] Versão mobile para acompanhamento em campo

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

**Fernando Giordano**

- GitHub: [@fqgiord](https://github.com/fqgiord)
- LinkedIn: [fernando-g-tech](https://www.linkedin.com/in/fernando-g-tech/)

---

⭐ **Se este projeto demonstra como experiência operacional pode ser transformada em soluções tecnológicas, considere dar uma estrela!**

---

### 📌 Nota sobre Dados

Os dados utilizados neste projeto são **simulados** para fins de demonstração. Em ambiente de produção real, o sistema seria integrado diretamente com:
- Sistemas DCS (Distributed Control System)
- Historiadores PI System
- Sistemas SCADA
- Bancos de dados de processo em tempo real
