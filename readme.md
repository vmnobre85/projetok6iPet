![Logo Unifor](cabecalho.jpg) 

# Integração de Teste de Carga K6 para Avaliação de Desempenho do Aplicativo iPet

## Introdução
Neste documento, descreveremos a integração de teste de carga K6 para avaliar o desempenho do aplicativo iPet. Esta integração visa validar a quantidade de avaliações por segundo do aplicativo, garantindo sua escalabilidade e robustez em face de picos de uso e demanda variável.

## Motivação
A motivação por trás desta integração reside na necessidade de garantir que o aplicativo iPet possa lidar eficientemente com um grande volume de avaliações simultâneas. Testes de carga são cruciais para identificar gargalos de desempenho e pontos fracos da infraestrutura, permitindo ajustes antes do lançamento ou atualização do aplicativo.

## Objetivos
- **Geral:** Implementar uma integração de teste de carga K6 para avaliar a capacidade de resposta do aplicativo iPet sob diferentes cargas de trabalho.
- **Específicos:**
    1. Configurar e executar testes de carga utilizando o K6.
    2. Integrar os resultados dos testes de carga ao Grafana para visualização e análise.
    3. Estabelecer métricas de desempenho, incluindo avaliações por segundo, tempo de resposta e utilização de recursos.
    4. Identificar possíveis gargalos de desempenho e áreas de melhoria no aplicativo iPet.
    5. Avaliar a escalabilidade do aplicativo sob diferentes condições de carga.
    6. Documentar os procedimentos e resultados para referência futura.

## Requisitos Funcionais
1. **Configuração do Teste de Carga:** Permitir a configuração flexível dos parâmetros de teste de carga, incluindo número de usuários virtuais, tempo de execução e cenários de teste.
2. **Execução Automatizada:** Automatizar o processo de execução dos testes de carga, garantindo consistência e reprodutibilidade.
3. **Integração com Grafana:** Integrar os resultados dos testes de carga ao Grafana para visualização em tempo real e análise histórica.
4. **Monitoramento de Métricas:** Monitorar métricas de desempenho-chave, incluindo taxa de transferência, tempo de resposta e erros.
5. **Alertas de Desempenho:** Configurar alertas no Grafana para notificar sobre eventos de desempenho abaixo dos limites especificados.
6. **Relatórios Detalhados:** Gerar relatórios detalhados dos resultados dos testes de carga, incluindo gráficos e análises.

## Implementação Técnica

Para alcançar os requisitos funcionais mencionados acima, seguiremos estas etapas:

1. **Instalação do K6:**
   - Instalar o K6 em um ambiente de desenvolvimento local ou em um servidor remoto.

2. **Desenvolvimento de Scripts de Teste:**
   - Escrever scripts de teste em JavaScript para simular diferentes cenários de carga, como criação de avaliações, leitura de dados e atualizações simultâneas.

3. **Configuração da Integração com Grafana:**
   - Configurar a integração entre o K6 e o Grafana para enviar os resultados dos testes de carga.

4. **Definição de Métricas e Alertas:**
   - Definir as métricas de desempenho a serem monitoradas, como tempos de resposta aceitáveis e taxas de erro permitidas.
   - Configurar alertas no Grafana para notificar sobre desvios nas métricas de desempenho.

5. **Execução Automatizada:**
   - Configurar a execução automatizada dos testes de carga em intervalos regulares usando ferramentas de integração contínua.

6. **Geração de Relatórios:**
   - Gerar relatórios detalhados dos resultados dos testes de carga, incluindo gráficos e análises, utilizando recursos integrados do K6 ou ferramentas externas.

## Cronograma
- **Fase 1 - Planejamento e Preparação (1 semana):**
    - Levantamento de requisitos e definição de escopo.
    - Instalação e configuração do ambiente de teste.
    - Desenvolvimento de scripts de teste preliminares.
- **Fase 2 - Implementação da Integração (2 semanas):**
    - Desenvolvimento e refinamento dos scripts de teste de carga.
    - Configuração da integração com o Grafana.
    - Testes de validação da integração.
- **Fase 3 - Execução e Análise (3 semanas):**
    - Execução de testes de carga em diferentes cenários.
    - Monitoramento e análise contínua dos resultados.
    - Identificação e correção de problemas de desempenho.
- **Fase 4 - Documentação e Entrega (1 semana):**
    - Elaboração de documentação completa da integração.
    - Preparação de relatórios finais e análise de resultados.
    - Entrega final do projeto e apresentação dos resultados.

Este cronograma está sujeito a ajustes conforme necessário durante o desenvolvimento do projeto.

## Conclusão

A integração do K6 para teste de carga do aplicativo iPet é essencial para garantir sua escalabilidade e desempenho sob condições de carga variáveis. Com a configuração correta e a análise dos resultados, podemos identificar e corrigir problemas de desempenho antes que afetem os usuários finais.
