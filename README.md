<<<<<<< HEAD
# Simulação Quântica de Tomada de Decisão sob Incerteza

## Integrantes
- Nome 1: Gustavo Andrade Amorim
- Nome 2: Leonardo Tanaka Cortez
- Nome 3: Carlos Augusto da Cruz Possi
- Nome 4: Fabio Henrique Santos Farias
- Nome 5: João Pedro Bernardo Santos da Silva

## RM
- RM 1: 556869
- RM 2: 556781
- RM 3: 558758
- RM 4: 552453
- RM 5: 557142

## Turma
- Turma: 2ECA

---

## Descrição do Projeto
Este projeto utiliza a biblioteca Qiskit para simular um circuito quântico que representa um processo de tomada de decisão sob incerteza, inspirado em cenários reais de controle de qualidade na indústria farmacêutica. O objetivo é demonstrar como conceitos fundamentais da computação quântica, como superposição e emaranhamento, podem ser aplicados para modelar situações onde há incerteza na padronização de embalagens, impactando indicadores-chave de desempenho (KPIs) industriais.

O notebook principal está em `notebook/SPR2_Quantum.ipynb`.

---

## Como Executar
1. **Instale as dependências:**
   - Recomenda-se o uso de ambiente virtual 
   - Execute no terminal:
     ```bash
     pip install qiskit qiskit-aer matplotlib pylatexenc
     ```
2. **Abra o notebook:**
   - Use Jupyter Notebook, Jupyter Lab ou o VSCode com suporte a notebooks.
   - Navegue até a pasta `notebook/` e abra o arquivo `SPR2_Quantum.ipynb`.
3. **Execute todas as células na ordem.**
   - O circuito será criado, simulado e os resultados visualizados.
   - O histograma será salvo automaticamente em `images/histograma.png`.

---

## Estrutura do Projeto
- `notebook/SPR2_Quantum.ipynb`: Notebook principal com todo o código, comentários e explicações.
- `images/histograma.png`: Arquivo gerado com o histograma dos resultados da simulação.
- `env/`: (opcional) Ambiente virtual Python.

---

## Dependências
- Python 3.8+
- Qiskit
- Qiskit Aer
- Matplotlib
- pylatexenc

---

## Explicação do Projeto
O notebook simula um circuito quântico com dois qubits:
- O primeiro qubit recebe uma porta Hadamard, criando um estado de superposição (incerteza).
- Em seguida, uma porta CNOT é aplicada, emaranhando o segundo qubit ao primeiro.
- Ambos os qubits são medidos, e a simulação é executada 1024 vezes usando o AerSimulator.
- Os resultados das medições são apresentados em um histograma.

### O que o notebook gera?
- **Visualização do circuito quântico:** Mostra graficamente as portas aplicadas e as medições.
- **Histograma dos resultados:** Mostra a frequência de cada resultado possível após as medições dos qubits.
- **Arquivo `images/histograma.png`:** Salva o histograma para uso em relatórios ou apresentações.

### O que significa cada resultado?
- Os resultados possíveis são `00` e `11`.
  - `00`: Ambos os qubits foram medidos como 0.
  - `11`: Ambos os qubits foram medidos como 1.
- Isso ocorre devido ao emaranhamento: ao medir o primeiro qubit, o segundo colapsa para o mesmo valor.
- A distribuição entre `00` e `11` deve ser aproximadamente igual, refletindo a incerteza e a simetria do circuito.

=======
# quantum-sprint-II
>>>>>>> 5e0f80a8f694191e414ec3ee0f5aaceddf38c114
