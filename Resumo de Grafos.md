# 📊 Resumo – Grafos

## 📌 O que são Grafos?
Grafos são estruturas matemáticas muito utilizadas na computação para representar **relações entre elementos**.  
Eles são formados por:

- 🔵 **Vértices (ou nós):** representam os elementos  
- 🔗 **Arestas:** representam as conexões entre esses elementos  

Essa estrutura é útil para modelar situações do mundo real de forma clara e visual.

---

## 🚀 Aplicações dos Grafos
Grafos aparecem em diversas áreas importantes:

- 🚚 **Logística:** cálculo de rotas e caminhos mais curtos  
- ⚙️ **Engenharia:** modelagem de circuitos e projetos  
- 👥 **Redes sociais:** análise de conexões entre pessoas  
- 🧬 **Biotecnologia:** estudo de redes biológicas  
- 🎮 **Jogos:** movimentação e mapas de personagens  
- 📅 **Organização de tarefas:** planejamento e dependências  

---

## 📚 Conceitos Fundamentais

### 🧩 Representação
Um grafo pode ser representado como:
G = (V, E)
- **V:** conjunto de vértices  
- **E:** conjunto de arestas  

---

### 🔢 Grau dos Vértices
- **Grau de um vértice:** número de arestas conectadas a ele  
- **Grau máximo:** maior grau entre os vértices  
- **Grau mínimo:** menor grau entre os vértices  

Esses valores ajudam a entender o nível de conexão dentro do grafo.

---

## ➡️ Grafos Orientados (Digrafos)
Nos grafos orientados, as arestas possuem **direção**.

Exemplo: A → B (mas não necessariamente B → A)

- 📥 **Grau de entrada:** número de arestas que chegam ao vértice  
- 📤 **Grau de saída:** número de arestas que saem do vértice  

Muito usados em:
- Redes sociais (seguidores)
- Links da internet

---

## 🌐 Análise de Redes Sociais

Nos grafos aplicados a redes sociais:

- 👤 **Nós:** representam pessoas ou entidades  
- 🤝 **Arestas:** representam relações  

### 🔍 Conceitos importantes:
- ⭐ **Centralidade:** mede a importância de um nó  
- 🔗 **Coesão:** força das conexões dentro de um grupo  
- 👥 **Comunidade:** grupo de nós fortemente conectados  

---

## 💻 Representação Computacional

### 📋 Lista de Adjacência
- Cada vértice possui uma lista com seus vizinhos  
- ✅ Mais econômica em memória  
- ✅ Ideal para grafos com poucas conexões  

---

### 🔢 Matriz de Adjacência
- Tabela que indica conexões entre vértices  
- Usa:
  - `1` → existe conexão  
  - `0` → não existe conexão  

- ✅ Fácil de entender  
- ❌ Consome mais memória em grafos grandes  

---

## ✨ Conclusão
Grafos são ferramentas poderosas para representar e analisar relações complexas, sendo essenciais em diversas áreas da tecnologia e da ciência.
