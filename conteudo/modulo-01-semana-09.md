# Academia IA Sob Medida — Módulo 1, Semana 9
## Fabricação, CNC e produtividade

**Carga horária estimada:** 4 horas  
**Competência:** compreender o fluxo de fabricação, preparar informações para produção, interpretar plano de corte e otimização, entender fundamentos de usinagem CNC e acompanhar qualidade, produtividade e segurança.

### Objetivos
- Mapear o fluxo de fabricação do pedido à expedição.
- Preparar lista de peças, plano de corte e identificação.
- Compreender otimização de chapas e aproveitamento de materiais.
- Entender o fluxo CAD/CAM/CNC e os cuidados de preparação.
- Definir indicadores de produtividade, qualidade, perdas e retrabalho.
- Reconhecer riscos de máquinas, poeira e movimentação de materiais.

## Aula 1 — Fluxo produtivo: do projeto liberado à peça pronta
A produção depende de projeto liberado, revisão identificada, medidas conferidas, materiais, ferragens, acabamento, bordas, usinagens, quantidades e prazos. Defina um ponto formal de liberação: dúvidas críticas sobre dimensões, sentido de veio, ferragens, furação ou interferências bloqueiam a fabricação até serem resolvidas.

Etapas típicas:
1. Conferência de projeto, revisão, lista de peças e materiais.
2. Separação e identificação de chapas e lotes.
3. Plano de corte com margens, kerf, veio e restrições.
4. Seccionamento e usinagem.
5. Bordagem.
6. Furação e operações complementares.
7. Pré-montagem e conferência.
8. Embalagem e expedição.

Etiqueta ou registro digital: código, ambiente, móvel, quantidade, material, espessura, dimensões finais, acabamento, fita por lado, sentido do padrão, operações e revisão. A convenção deve ser compartilhada por projeto, produção e montagem.

Observe tempo de processamento, espera, setup, retrabalho, paradas e falta de componentes. O gargalo é a etapa que limita a capacidade naquele contexto e pode mudar com o mix de produtos.

**Estudo de caso:** cozinha com duas frentes em padrão de veio contínuo e ferragem pendente. Separe itens liberados e bloqueados, confirme insumos, planeje a sequência e comunique o impacto no prazo.

**Exercício 1:** desenhar o fluxo de uma peça, com entrada, saída, responsável, risco e critério de liberação; identificar um gargalo e como medi-lo.

**Referências da Aula 1**
1. Slack, N.; Brandon-Jones, A.; Burgess, N. *Operations Management*. Pearson. https://www.pearson.com/
2. Groover, M. P. (2015). *Automation, Production Systems, and Computer-Integrated Manufacturing* (4th ed.). Pearson.
3. HSE. *Training and supervision in woodworking*. https://www.hse.gov.uk/woodworking/training.htm

## Aula 2 — Plano de corte, otimização e aproveitamento de chapas
A lista de peças deve indicar dimensões de fabricação, quantidade, espessura, material, acabamento, sentido do padrão e operações. Confirme se as dimensões são finais ou incluem sobremedidas.

O plano de corte distribui peças respeitando dimensões úteis, largura de serra, margens, defeitos, veio, acabamento, dimensão mínima segura e capacidade da máquina. Otimização não significa apenas reduzir sobras: considere tempo, reposicionamentos, estabilidade, sentido do padrão, sequência, identificação e risco de danos.

Não rotacione automaticamente peças amadeiradas. A orientação pode ser requisito estético e de fabricação. Separe perdas inevitáveis (kerf, geometria, dimensão comercial) das evitáveis (erro, avaria, versão errada, falha operacional, retrabalho e sobra sem identificação).

Indicadores: consumo de chapas por pedido; aproveitamento estimado e real; retalhos reutilizáveis; custo de material por móvel; peças refeitas; tempo de preparação; paradas por falta de insumo.

**Estudo de caso:** lote de cozinha e lavanderia no mesmo padrão. Compare plano com rotação irrestrita e plano com orientação obrigatória; registre a escolha e suas razões.

**Exercício 2:** criar lista de 10 peças fictícias, simular distribuição em chapas comerciais e declarar kerf, margens e restrições.

**Referências da Aula 2**
1. Wäscher, G.; Haußner, H.; Schumann, H. (2007). An improved typology of cutting and packing problems. *European Journal of Operational Research, 183*(3), 1109–1130. DOI: https://doi.org/10.1016/j.ejor.2005.12.047
2. Groover, M. P. (2015). *Automation, Production Systems, and Computer-Integrated Manufacturing* (4th ed.). Pearson.
3. Manuais do software de otimização e da seccionadora efetivamente utilizados. A largura de corte, margens, rotação e regras devem seguir a configuração validada do equipamento.

## Aula 3 — CNC, preparação de usinagem e controle de qualidade
Fluxo:
- **CAD:** geometria e informações do projeto.
- **CAM:** operações e trajetórias de ferramenta.
- **Pós-processador:** converte operações para o formato do controle.
- **CNC:** executa movimentos conforme programa, configuração, ferramenta e fixação.

Arquivo CAD/CAM não está automaticamente pronto para máquina. Confirmar unidade, escala, origem, eixos, face, espessura, ferramenta, compensações, pós-processador, fixação, sequência e limites do equipamento.

Parâmetros dependem de material, geometria da ferramenta, diâmetro, número de cortes, rotação, avanço, profundidade de passe, estratégia de entrada e evacuação de cavacos. Não há tabela universal de avanço e rotação para todos os MDF, MDP, compensados, madeiras, máquinas e ferramentas. Usar documentação dos fabricantes e procedimentos de teste autorizados.

Antes do ciclo: conferir ordem e revisão, material, espessura, face, ferramenta, fixação, origem, limites, proteções, extração, simulação e primeira peça. Não neutralizar proteções ou intertravamentos. Limpeza, manutenção e intervenções seguem procedimentos seguros e isolamento de energias quando necessário.

Poeira de madeira pode causar danos respiratórios e outros agravos; também pode gerar risco de incêndio/explosão em determinadas condições. Priorizar avaliação de riscos, enclausuramento, extração dimensionada e mantida, limpeza adequada e EPI como complemento. Não espalhar pó com ar comprimido nem varrição seca.

Inspecionar primeira peça: dimensões, esquadro, posição de furos, rasgos, profundidade, bordas, acabamento, identificação e compatibilidade com ferragens. Se houver desvio, interromper liberação, identificar peças afetadas, investigar revisão, origem, unidade, face, ferramenta e fixação; corrigir e validar antes de continuar.

**Estudo de caso:** furação deslocada no primeiro componente. Bloquear lote, conferir revisão e parâmetros, validar teste e registrar causa e ação corretiva.

**Exercício 3:** elaborar ficha de inspeção da primeira peça CNC com código, revisão, material, espessura, dimensões, operações, operador autorizado, resultado, desvios e aprovação.

**Referências da Aula 3**
1. Ministério do Trabalho e Emprego. *NR-12 — Segurança no Trabalho em Máquinas e Equipamentos*. https://www.gov.br/trabalho-e-emprego/pt-br/acesso-a-informacao/participacao-social/conselhos-e-orgaos-colegiados/comissao-tripartite-paritaria-permanente/normas-regulamentadora/normas-regulamentadoras-vigentes/norma-regulamentadora-no-12-nr-12
2. Ministério do Trabalho e Emprego. *NR-1 — Disposições Gerais e Gerenciamento de Riscos Ocupacionais*. https://www.gov.br/trabalho-e-emprego/pt-br/acesso-a-informacao/participacao-social/conselhos-e-orgaos-colegiados/comissao-tripartite-paritaria-permanente/normas-regulamentadora/normas-regulamentadoras-vigentes/nr-1
3. HSE. *Wood dust: Controlling the risk*, WIS23 (rev. 3), 2022. https://www.hse.gov.uk/PUBNS/wis23.htm
4. HSE. *Woodworking Information Sheets* — inclui orientações para proteção de CNC routers e centros de usinagem. https://www.hse.gov.uk/woodworking/wis.htm
5. WorkSafe New Zealand. *Woodworking CNC Machines*. https://www.worksafe.govt.nz/topic-and-industry/machinery/woodworking/woodworking-cnc-machines/
6. Manual técnico, biblioteca de ferramentas, pós-processador e documentação de segurança do fabricante da máquina e ferramentas efetivamente utilizadas.

## Aplicação prática na MadePrimer
1. Selecionar móvel aprovado e cópia controlada do projeto.
2. Montar lista de peças com código, ambiente, material, espessura, dimensões e orientação.
3. Definir roteiro de fabricação e pontos de conferência.
4. Simular plano de corte com regras explícitas.
5. Identificar bordas, furações e usinagens.
6. Revisar arquivo com responsável autorizado; não operar máquina sem capacitação.
7. Criar ficha de inspeção da primeira peça.
8. Medir espera, setup, processamento, retrabalho e perdas.

## Indicadores
- Produtividade: peças conformes por hora ou conjuntos por turno, com unidade definida.
- Rendimento de material: aproveitamento em relação ao consumo, com regra para retalhos reutilizáveis.
- Retrabalho: peças refeitas em relação ao total.
- Tempo de ciclo: processamento em etapa definida.
- Setup: tempo de preparação para nova operação ou lote.
- Entrega no prazo: etapas ou pedidos concluídos até a data acordada.

## Checklist de liberação
1. Projeto aprovado e revisão identificada?
2. Medidas e interferências conferidas?
3. Lista de peças completa?
4. Material, espessura, acabamento e veio definidos?
5. Ferragens e operações especificadas?
6. Plano de corte respeita restrições e kerf?
7. Arquivo CNC compatível com máquina e pós-processador?
8. Ferramentas e parâmetros confirmados?
9. Fixação, proteções e extração verificadas?
10. Primeira peça inspecionada?
11. Peças etiquetadas por conjunto?
12. Pendências registradas?

## Entrega avaliativa
- Mapa de fluxo.
- Lista de peças codificada.
- Simulação de plano de corte com premissas.
- Ficha de preparação e inspeção da primeira peça CNC.
- Plano simples de controle de qualidade.
- Três indicadores com fórmula, unidade e frequência.
- Proposta de melhoria baseada em gargalo ou perda observada.

**Critérios:** completude, clareza do fluxo, respeito às restrições, rastreabilidade, inspeção, consistência dos indicadores e reconhecimento dos riscos.

## Glossário
Ordem de produção; lista de peças; plano de corte; nesting; kerf; CAD; CAM; CNC; pós-processador; setup; gargalo; não conformidade.

## Referências gerais da semana
1. Groover, M. P. (2015). *Automation, Production Systems, and Computer-Integrated Manufacturing* (4th ed.). Pearson.
2. Slack, N.; Brandon-Jones, A.; Burgess, N. *Operations Management*. Pearson.
3. Wäscher, G.; Haußner, H.; Schumann, H. (2007). *European Journal of Operational Research, 183*(3), 1109–1130. DOI: https://doi.org/10.1016/j.ejor.2005.12.047
4. MTE. Normas Regulamentadoras vigentes, conforme riscos e atividades: https://www.gov.br/trabalho-e-emprego/pt-br/acesso-a-informacao/participacao-social/conselhos-e-orgaos-colegiados/comissao-tripartite-paritaria-permanente/normas-regulamentadora/normas-regulamentadoras-vigentes
5. HSE. *Woodworking: training, risk management and wood dust control*. https://www.hse.gov.uk/woodworking/

**Nota de rigor e segurança:** esta aula é introdutória e não habilita ninguém a operar máquinas. Operação, programação, manutenção e intervenções devem seguir capacitação, autorização, apreciação de riscos, proteções, procedimentos internos, manuais e normas brasileiras vigentes. Parâmetros numéricos universais não são fornecidos porque dependem de máquina, ferramenta, material, fixação e estratégia. Extração e medidas de proteção devem ser dimensionadas e verificadas por pessoas competentes.

---
## ACADEMIA IA SOB MEDIDA
**Formação profissional independente em móveis planejados, marcenaria e ambientes sob medida.**  
Aprender · Aplicar · Evoluir.

**Natureza educacional**  
Programa de formação independente. O conteúdo não equivale a diploma, graduação, certificação profissional regulamentada ou habilitação legal.

**Responsabilidade técnica e segurança**  
Projetos, fabricação, operação de máquinas, instalações e especificações devem observar normas técnicas, legislação aplicável, manuais dos fabricantes e avaliação de profissionais legalmente habilitados, quando exigido.

**Direitos e atualização**  
© 2026 Academia IA Sob Medida. Todos os direitos reservados. Conteúdo didático sujeito a revisão e atualização.
