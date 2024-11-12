# postGraduateProgramInDataScienceAndAI

### Instalação das Dependências

Para instalar as bibliotecas necessárias, execute o seguinte comando:

```bash
pip install -r requirements.txt
```

## Bibliotecas Utilizadas

Neste módulo, utilizamos diversas bibliotecas para manipulação de dados, visualização e aprendizado de máquina. Abaixo está a lista de importações organizadas por categoria.

# Manipulação e Análise de Dados
import pandas as pd
import numpy as np

# Visualização de Dados
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px  # Gráficos dinâmicos
import plotly.offline as py
import plotly.graph_objects as go  # Criar e concatenar gráficos

# Pré-processamento e Machine Learning
from sklearn.preprocessing import LabelEncoder
from sklearn.cluster import KMeans
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
from sklearn import datasets, model_selection, preprocessing, metrics
