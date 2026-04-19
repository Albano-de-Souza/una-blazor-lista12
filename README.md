# Projeto EcoMonitor - Lista 12 (ADS UNA)

1. Identificação
- **Nome Completo:** Albano de Souza
- **Curso:** Análise e Desenvolvimento de Sistemas (ADS)
- **Unidade:** UNA Barreiro / Contagem

2. Heurísticas de Nielsen Aplicadas
Neste projeto, focamos em duas heurísticas principais:
* **Visibilidade do Status do Sistema:** Através do componente `EcoStatus`, o sistema comunica claramente o nível de impacto ambiental de cada atividade usando rótulos de "Peso" e bordas destacadas, permitindo que o usuário entenda o estado atual do monitoramento.
* **Consistência e Padronização:** O uso de um componente reutilizável garante que todas as instâncias de monitoramento (Plástico, Árvores, Eletrônicos) sigam o mesmo padrão visual e funcional, evitando confusão no reconhecimento da interface.

3. Guia de Execução (Terminal)
Para rodar este projeto na sua máquina:
1. Abra o terminal na pasta raiz do projeto (`EcoMonitor`).
2. Execute o comando:
   ```bash
   dotnet run --launch-profile https
