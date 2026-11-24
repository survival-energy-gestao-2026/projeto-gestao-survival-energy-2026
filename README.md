# Survival Energy

Projeto em Gestão de Sistemas Computacionais, UNINOVE, 2026/2. O estudo usa vendas simuladas de uma marca de vestuário para decidir quantas camisetas e moletons produzir e como distribuir as peças com o menor custo de transporte.

## Como executar

Abra `03-analise-de-dados/Survival_Energy_integrado.ipynb` no Google Colab. No painel **Arquivos**, envie `03-analise-de-dados/base_original.csv` e selecione **Ambiente de execução → Executar tudo**. Se a base estiver ausente, o notebook recria a simulação com a mesma semente. Ao terminar, baixe `survival_resultados.zip` pelo painel Arquivos.

Para executar no computador, abra um terminal na pasta `03-analise-de-dados`. O notebook entregue registra Python 3.13 e as versões das bibliotecas estão em `requirements.txt`.

```sh
python -m pip install -r requirements.txt
python survival.py
```

O script grava arquivos em `resultados/`. A simulação tem 322 itens válidos e 237 pedidos. A solução de produção indica 400 camisetas e 108 moletons com margem de contribuição de R$ 29.180. O plano de transporte atende 600 peças por R$ 2.820.

## Conteúdo

| Pasta | Material |
|---|---|
| [Documentação](00-documentacao/) | Relatório público anonimizado em PDF e Word |
| [Empresa e problema](01-empresa-e-problema/) | Caracterização da empresa, requisitos e diagnóstico do cenário |
| [Gestão de projetos](02-gestao-de-projetos/) | TAP, EAP, Gantt, RACI, backlog, riscos e orçamento |
| [Análise de dados](03-analise-de-dados/) | Base, dicionário, notebook, script e dependências para reproduzir os indicadores |
| [Segurança da informação](04-seguranca-da-informacao/) | Matriz GUT, políticas de acesso e mapeamento de privacidade |
| [Pesquisa operacional](05-pesquisa-operacional/) | Formulação dos dois modelos, restrições e interpretação dos cenários. O código dos modelos está no notebook integrado |
| [Evidências](06-evidencias/) | Resultados da execução, gráficos, testes e registros do backlog |
| [Vídeo](07-video/) | Roteiro de demonstração. O link do YouTube está pendente da gravação pela equipe |
| [Referências](08-referencias/) | Fontes usadas no estudo |
