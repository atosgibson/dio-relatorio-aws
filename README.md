# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 08/01/2026  
**Empresa:** Abstergo Industries  
**Responsável:** Seu Nome  

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Seu Nome**. O objetivo do projeto foi selecionar **3 serviços AWS** com a finalidade de promover **redução imediata de custos**, sem comprometer disponibilidade e segurança.

## Descrição do Projeto
O projeto foi dividido em **3 etapas**, cada uma com objetivos específicos:

### Etapa 1 — AWS Compute Optimizer
- **Foco da ferramenta:** rightsizing (dimensionamento correto) de recursos de computação.
- **Caso de uso:** análise de métricas para identificar instâncias EC2 superdimensionadas e sugerir tipos mais adequados, reduzindo custo com recursos ociosos.  
- **Resultado esperado:** economia imediata com troca para instâncias menores/mais custo-efetivas.

### Etapa 2 — Amazon EC2 Auto Scaling
- **Foco da ferramenta:** escalabilidade horizontal automática e redução de custos em baixa demanda.
- **Caso de uso:** criação de grupo de Auto Scaling com políticas para aumentar/reduzir instâncias conforme carga (CPU/requisições), evitando manter capacidade sobrando.  
- **Resultado esperado:** economia direta ao reduzir instâncias fora do pico.

### Etapa 3 — Amazon S3 Intelligent-Tiering + Lifecycle
- **Foco da ferramenta:** otimização de custos de armazenamento e retenção automatizada.
- **Caso de uso:** movimentar automaticamente objetos entre camadas conforme padrão de acesso, e aplicar regras de ciclo de vida para arquivar/expirar dados antigos.  
- **Resultado esperado:** redução contínua de custos sem intervenção manual.

## Conclusão
A implementação das ferramentas na **Abstergo Industries** tem como esperado:
- Redução imediata de custos via rightsizing (Compute Optimizer);
- Economia por elasticidade (Auto Scaling);
- Otimização contínua do armazenamento (S3 Intelligent-Tiering + Lifecycle).

Recomenda-se manter o monitoramento contínuo e revisar as recomendações periodicamente.

## Anexos
- Prints das recomendações do AWS Compute Optimizer  
- Políticas do Auto Scaling (min/max/desired e thresholds)  
- Regras de Lifecycle do S3  

**Assinatura do Responsável:**  
**Seu Nome**
