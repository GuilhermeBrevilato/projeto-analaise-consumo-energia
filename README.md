
# 📊 Análise do Parque de Equipamentos de Climatização — Unidades Hospitalares do Estado de SP

## 🏥 Contexto

Este projeto analisa o parque de equipamentos de climatização de **quatro unidades hospitalares** pertencentes ao **Módulo Leste II** da Secretaria de Estado da Saúde de São Paulo. A proposta visa avaliar o **consumo energético dos sistemas convencionais de climatização (split e ACJ)** e propor **cenários de retrofit com tecnologia Inverter**, buscando **eficiência energética, sustentabilidade e viabilidade financeira**.

As unidades analisadas foram:
- Hospital Infantil Cândido Fontoura  
- Hospital Padre Bento  
- NGA — Ambulatório de Especialidades  
- Maternidade Leonor Mendes de Barros  

## 🎯 Objetivos

- Realizar a **limpeza e o tratamento** dos dados do parque de equipamentos.
- Analisar o comportamento de consumo energético por unidade, considerando dados históricos de temperatura externa.
- Simular o consumo energético com a substituição dos sistemas atuais por **equipamentos com tecnologia Inverter**.
- Realizar **análises econômicas** com base em três cenários de economia (20%, 30% e 40%), calculando:
  - TIR (Taxa Interna de Retorno)
  - VLP (Valor Líquido Presente)
  - Payback Simples

## 🛠️ Tecnologias Utilizadas

- **Python**
  - pandas
  - matplotlib
  - seaborn
  - numpy
- **Jupyter Notebook**
- **Git/GitHub**

## 🧼 Etapas do Projeto

1. **Coleta e estruturação dos dados**  
2. **Exploração e limpeza de dados**  
3. **Análise do consumo energético atual**  
4. **Simulação de cenários com tecnologia Inverter**  
5. **Avaliação financeira dos cenários propostos**  
6. **Documentação e entrega do projeto**

## 📂 Organização dos Dados

```
├── data/
│   ├── raw/              # Base original (equipamentos e temperaturas)
│   └── processed/        # Dados tratados
├── notebooks/            # Análise exploratória, limpeza e simulações
├── src/                  # Scripts de limpeza e cálculo
├── outputs/              # Gráficos e relatório final
```

## 🚀 Como Executar Localmente

1. Clone o repositório:
```bash
git clone https://github.com/seuusuario/analise-parque-equipamentos-hospitais.git
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

3. Execute os notebooks na pasta `notebooks/`.

## 👨‍💼 Autor

**Guilherme Brevilato**  
Engenheiro Mecânico • Fiscal de Manutenção Predial  
Grupo Técnico de Edificações – SES/SP  
📧 gbrevilato@saude.sp.gov.br  
