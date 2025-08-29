# 📈 crewAI-AnaliseMercado — Agentes Inteligentes para Análise de Tendências

## 💡 Visão Geral

Este projeto foi desenvolvido como parte dos estudos do curso [Desenvolvimento de Agentes de IA: Do Zero ao Avançado](https://www.udemy.com/course/desenvolvimento-de-agentes-de-ia-do-zero-ao-avancado) na Udemy, ministrado por Rodrigo Macedo e Paulo Andrade, PhD.

O objetivo é simular uma análise de mercado automatizada utilizando o framework **CrewAI**, que permite a criação de agentes colaborativos com tarefas especializadas. Cada agente neste projeto contribui com uma etapa da análise — desde a coleta de dados até a geração de insights — formando um fluxo inteligente e coordenado.

---

## 🧠 Conceitos Aplicados

- **CrewAI**: Framework para criação de agentes multitarefa que colaboram entre si.
- **Agentes Especializados**: Cada agente tem uma função clara e atua com autonomia.
- **Tarefas Encadeadas**: As tarefas são organizadas em sequência lógica para gerar uma análise completa.
- **Prompt Engineering**: Uso de instruções otimizadas para guiar o comportamento dos agentes.

---

## 🛠️ Tecnologias Utilizadas

- `Python`  
- `CrewAI`  
- `LangChain`  
- `OpenAI API`  
- `dotenv` para variáveis de ambiente  
- `Streamlit` (opcional para interface)

---

## 🚀 Primeiros Passos

### ✅ Pré-requisitos
- Python 3.12+
- pip
- Chave de API (OpenAI ou outro provedor LLM)

### 📦 Instalação e Ambiente Virtual

```bash
python3.12 -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```
Configure o arquivo .env com sua chave de API:
```env
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxx
```

### ▶️ Executando o Projeto
```bash
python main.py
```
Ou, se houver interface web:
```bash
streamlit run app.py
```

## 📁 Estrutura do Projeto
```
crewAI-AnaliseMercado/
├── main.py               # Execução principal
├── agents/               # Definição dos agentes
├── tasks/                # Tarefas atribuídas aos agentes
├── .env                  # Chave de API
├── requirements.txt      # Dependências
└── README.md             # Documentação
```

## 📚 Aprendizados
- Modelagem de agentes com CrewAI
- Coordenação de tarefas entre agentes autônomos
- Geração de insights com base em dados simulados
- Aplicação de IA generativa em análise de mercado
- Estruturação de fluxos inteligentes com prompts e lógica sequencial

## 🔮 Próximos Passos
- Adicionar novos agentes com especializações em setores específicos
- Integrar fontes de dados reais (ex: APIs financeiras)
- Criar relatórios automatizados com visualizações
- Testar integração com LangGraph para controle de fluxo condicional

## 👩‍💻 Autora

Aline Assunção

Engenheira de Qualidade em transição para Inteligência Artificial

📫 [LinkedIn](https://www.linkedin.com/in/alineassuncaoai/)  

📬 aline.jassuncao@gmail.com

>_"Analisar o mercado com inteligência é mais do que números — é colaboração entre agentes que pensam."_
