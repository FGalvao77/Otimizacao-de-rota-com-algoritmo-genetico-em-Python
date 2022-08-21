## Otimização de rota com algoritmo genéticos em Python
---
---

**Problema do caixeiro-viajante**

O **Problema do Caixeiro Viajante (_PCV_)** é um problema que tenta determinar a menor rota para percorrer uma série de cidades (visitando uma única vez cada uma delas), retornando à cidade de origem. Ele é um problema de [otimização](https://pt.wikipedia.org/wiki/Otimiza%C3%A7%C3%A3o_combinat%C3%B3ria) [NP-difícil](https://pt.wikipedia.org/wiki/NP-dif%C3%ADcil) inspirado na necessidade dos vendedores em realizar entregas em diversos locais (as cidades) percorrendo o menor caminho possível, reduzindo o tempo necessário para a viagem e os possíveis custos com transporte e combustível.

- Fonte: https://pt.wikipedia.org/wiki/Problema_do_caixeiro-viajante

Segue abaixo o grafo direcionado representado o nosso problema!

![image](https://user-images.githubusercontent.com/63373520/185788955-d0034fef-a43c-4ea3-82bd-e43e10d09993.png)

**Descrição do problema:**<br>
>Encontrar a melhor rota que percorre todas as distribuidoras de bebidas.
- `melhor` = _menor distância_.

E para esse desafio, utilizaremos uma estrutura de _algoritmos genéticos evolucionário_, nesse caso, o `DEAP` - Distributed Evolutionary Algorithms in Python | Algoritmos Evolutivos Distribuídos em Python.

![image](https://user-images.githubusercontent.com/63373520/185788978-626bf624-2194-43bf-8718-089d952fcd5f.png)
- https://deap.readthedocs.io/en/master/
- https://pypi.org/project/deap/
