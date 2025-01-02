# Olho na Quadra: Sistema Inteligente para Análise de Dados de Voleibol

O Olho na Quadra é uma plataforma de análise de dados voltada para o voleibol profissional, utilizando técnicas avançadas de machine learning e análise estatística para processar dados de partidas em tempo real. O sistema é capaz de identificar padrões de jogo, avaliar o desempenho individual e coletivo dos atletas, e gerar insights estratégicos para times e treinadores. Nossa solução integra processamento de vídeo para rastreamento de movimentação dos jogadores, análise de dados estatísticos das partidas e um modelo preditivo para apoio à tomada de decisão durante os jogos.

O projeto utiliza uma combinação de algoritmos de visão computacional e aprendizado de máquina para processar dados coletados durante as partidas, oferecendo uma interface intuitiva para visualização e análise dos resultados. O sistema é projetado para ser escalável e adaptável a diferentes níveis de competição, desde categorias de base até competições profissionais.

## Instruções de Utilização

### Pré-requisitos
* Python 3.8+
* PostgreSQL 12+
* OpenCV 4.5+
* TensorFlow 2.8+

### Instalação

1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/olho-na-quadra.git
cd olho-na-quadra
```

2. Crie e ative um ambiente virtual
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. Instale as dependências
```bash
pip install -r requirements.txt
```

4. Configure as variáveis de ambiente
```bash
cp .env.example .env
# Edite o arquivo .env com suas configurações
```

5. Inicialize o banco de dados
```bash
python scripts/init_db.py
```

### Execução
```bash
python main.py
```

A interface web estará disponível em `http://localhost:5000`

## Histórico de Versões

* 0.1.1
    * CHANGE: Atualização da documentação e correção de bugs na interface de visualização de estatísticas
    * CHANGE: Otimização do algoritmo de tracking de jogadores
    * FIX: Correção do cálculo de eficiência de ataque

* 0.1.0
    * NEW: Implementação do primeiro modelo de análise preditiva
    * NEW: Interface web básica para visualização de dados
    * NEW: Sistema de captura e processamento de vídeo em tempo real

* 0.0.1
    * Desenvolvimento inicial
    * Preparação e estruturação do dataset de treinamento
    * Implementação da pipeline básica de processamento de dados

## 📝 Licença

Este projeto está sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.
