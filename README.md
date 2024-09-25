# Gerenciamento de frotas

## Tabela resumo
| Código   | Nome                                         | Prioridade  |
|----------|----------------------------------------------|-------------|
| RF-001-A | Cadastrar novos veículos                     | Essencial   |
| RF-002-A | Consultar informações gerais e individuais   | Essencial   |
| RF-003-A | Realizar baixa/desativação de veículos       | Importante  |
| RF-004-A | Atualizar dados do veículo                   | Importante  |
| RF-005-A | Consultar histórico de uso                   | Desejável   |
| RF-006-A | Definir status de utilização                  | Importante  |
| RF-007-A | Exportar dados de veículos em massa          | Desejável   |
| RF-001-B | Cadastro de novos motoristas                 | Essencial   |
| RF-002-B | Consultar informações gerais e individuais de motoristas | Essencial   |
| RF-003-B | Associar motoristas e veículos               | Importante  |
| RF-004-B | Atualizar dados de motorista                  | Importante  |
| RF-005-B | Avaliação de desempenho                       | Desejável   |
| RF-006-B | Histórico de treinamento                      | Desejável   |
| RF-007-B | Gerenciar disponibilidade                    | Importante  |
| RF-001-C | Planejar rotas de entrega ou coleta          | Essencial   |
| RF-002-C | Monitoramento de localização de veículos     | Essencial   |
| RF-003-C | Simulação de rotas                          | Desejável   |
| RF-004-C | Feedback de motoristas                       | Desejável   |
| RF-005-C | Integração com sistemas de mapas             | Importante  |
| RF-005-C | Gerar relatório de rotas                    | Desejável   |
| RF-001-D | Agendar manutenções preventivas e corretivas  | Essencial   |
| RF-002-D | Registrar a execução de manutenções         | Importante  |
| RF-003-D | Gerar relatório de custos                    | Importante  |
| RF-004-D | Histórico de problemas recorrentes           | Desejável   |
| RF-005-D | Alertas personalizados                        | Importante  |
| RF-006-D | Manutenção preditiva                         | Desejável   |
| RF-001-E | Registrar abastecimentos                     | Essencial   |
| RF-002-E | Cálculo de consumo médio                     | Importante  |
| RF-003-E | Monitoramento de preços de combustível       | Desejável   |
| RF-004-E | Controle de despesas por categoria           | Importante  |
| RF-005-E | Relatório de desvios de consumo              | Importante  |
| RF-001-F | Registro de histórico de documentos          | Essencial   |
| RF-002-F | Armazenamento seguro                         | Importante  |
| RF-003-F | Integração com órgãos reguladores            | Importante  |

## Cadastro e gestão de veículos
| Código   | RF-001-A                                      |
|----------|------------------------------------------------|
| Nome     | Cadastrar novos veículos                       |
| Descrição| Permitir a inclusão de novos veículos no sistema, registrando informações como marca, modelo, ano, placa e outros dados relevantes. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente, Motorista                            |
| Prioridade| Essencial                                    |

| Código   | RF-002-A                                      |
|----------|------------------------------------------------|
| Nome     | Consultar informações gerais e individuais     |
| Descrição| Fornecer acesso a dados sobre os veículos cadastrados, tanto em formato resumido quanto detalhado. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente, Motorista                            |
| Prioridade| Essencial                                    |

| Código   | RF-003-A                                      |
|----------|------------------------------------------------|
| Nome     | Realizar baixa/desativação de veículos         |
| Descrição| Oferecer uma funcionalidade para desativar veículos que não estão mais em uso, garantindo que o registro seja mantido para consulta futura. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Importante                                    |

| Código   | RF-004-A                                      |
|----------|------------------------------------------------|
| Nome     | Atualizar dados do veículo                     |
| Descrição| Permitir a edição das informações de veículos já cadastrados, como mudança de proprietário ou atualização de status. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Importante                                    |

| Código   | RF-005-A                                      |
|----------|------------------------------------------------|
| Nome     | Consultar histórico de uso                     |
| Descrição| Disponibilizar um registro das atividades de cada veículo, incluindo datas de uso, distâncias percorridas e finalidades. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente, Motorista                            |
| Prioridade| Desejável                                     |

| Código   | RF-006-A                                      |
|----------|------------------------------------------------|
| Nome     | Definir status de utilização                    |
| Descrição| Classificar os veículos com status que indicam se estão ativos, inativos ou em manutenção. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Importante                                    |

| Código   | RF-007-A                                      |
|----------|------------------------------------------------|
| Nome     | Exportar dados de veículos em massa            |
| Descrição| Permitir a extração de dados em formatos como CSV ou Excel, facilitando análises externas ou relatórios. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Desejável                                     |

## Cadastro e gestão de motoristas
| Código   | RF-001-B                                      |
|----------|------------------------------------------------|
| Nome     | Cadastro de novos motoristas                   |
| Descrição| Registro de novos motoristas com informações como nome, CPF, habilitação e dados de contato. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Essencial                                     |

| Código   | RF-002-B                           |
|----------|------------------------------------------------|
| Nome     | Consultar informações gerais e individuais de motoristas |
| Descrição| Acesso a dados dos motoristas, permitindo visualização de informações específicas ou resumos. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente, Motorista                            |
| Prioridade| Essencial                                     |

| Código   | RF-003-B                                      |
|----------|------------------------------------------------|
| Nome     | Associar motoristas e veículos                 |
| Descrição| Vincular motoristas a veículos específicos, gerenciando quem pode operar cada veículo. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Importante                                    |

| Código   | RF-004-B                                      |
|----------|------------------------------------------------|
| Nome     | Atualizar dados de motorista                    |
| Descrição| Edição das informações de motoristas conforme necessário, como alterações de endereço ou status de habilitação. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Importante                                    |

| Código   | RF-005-B                                      |
|----------|------------------------------------------------|
| Nome     | Avaliação de desempenho                        |
| Descrição| Criar um sistema para avaliar motoristas com base em métricas como segurança e feedback de clientes. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Desejável                                     |

| Código   | RF-006-B                                      |
|----------|------------------------------------------------|
| Nome     | Histórico de treinamento                        |
| Descrição| Registro das formações e certificações obtidas pelos motoristas ao longo do tempo. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Desejável                                     |

| Código   | RF-007-B                                      |
|----------|------------------------------------------------|
| Nome     | Gerenciar disponibilidade                      |
| Descrição| Funcionalidade para motoristas informarem sua disponibilidade em tempo real, ajudando na alocação de tarefas. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente, Motorista                            |
| Prioridade| Importante                                    |

## Gerenciamento de Rotas
| Código   | RF-001-C                                      |
|----------|------------------------------------------------|
| Nome     | Planejar rotas de entrega ou coleta            |
| Descrição| Criar e otimizar rotas para transporte de mercadorias ou coleta de clientes. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Essencial                                     |

| Código   | RF-002-C                                      |
|----------|------------------------------------------------|
| Nome     | Monitoramento de localização de veículos       |
| Descrição| Implementar rastreamento em tempo real da localização dos veículos em operação. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Essencial                                     |

| Código   | RF-003-C                                      |
|----------|------------------------------------------------|
| Nome     | Monitoramento de localização de veículos       |
| Descrição| Implementar rastreamento em tempo real da localização dos veículos em operação. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Essencial                                     |

| Código   | RF-004-C                                      |
|----------|------------------------------------------------|
| Nome     | Simulação de rotas                            |
| Descrição| Permitir a criação de simulações de diferentes rotas, ajudando na escolha da melhor opção. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Desejável                                     |

| Código   | RF-005-C                                      |
|----------|------------------------------------------------|
| Nome     | Feedback de motoristas                        |
| Descrição| Coletar opiniões dos motoristas sobre as rotas, promovendo melhorias contínuas no planejamento. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Desejável                                     |

| Código   | RF-006-C                                      |
|----------|------------------------------------------------|
| Nome     | Integração com sistemas de mapas              |
| Descrição| Utilizar APIs de mapas para obter informações atualizadas sobre trânsito e condições das vias. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Importante                                    |

| Código   | RF-007-C                                      |
|----------|------------------------------------------------|
| Nome     | Gerar relatório de rotas                      |
| Descrição| Criar relatórios detalhados sobre as rotas realizadas, incluindo tempo, distância e eventuais desvios. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Desejável                                     |

## Gerenciamento de manutenção
| Código   | RF-001-D                                      |
|----------|------------------------------------------------|
| Nome     | Agendar manutenções preventivas e corretivas  |
| Descrição| Planejamento de manutenções programadas e resolução de problemas emergenciais. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Essencial                                     |

| Código   | RF-002-D                                      |
|----------|------------------------------------------------|
| Nome     | Registrar a execução de manutenções           |
| Descrição| Documentar todas as manutenções realizadas em cada veículo. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Importante                                    |

| Código   | RF-003-D                                      |
|----------|------------------------------------------------|
| Nome     | Gerar relatório de custos                     |
| Descrição| Criar relatórios sobre os custos associados às manutenções, ajudando no controle orçamentário. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Importante                                    |

| Código   | RF-004-D                                      |
|----------|------------------------------------------------|
| Nome     | Histórico de problemas recorrentes            |
| Descrição| Identificar e registrar falhas frequentes em veículos para melhorar a gestão. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Desejável                                     |

| Código   | RF-005-D                                      |
|----------|------------------------------------------------|
| Nome     | Alertas personalizados                        |
| Descrição| Desenvolver um sistema de notificações para lembrar sobre manutenções e verificar o estado dos veículos. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Importante                                    |

| Código   | RF-006-D                                      |
|----------|------------------------------------------------|
| Nome     | Manutenção preditiva                          |
| Descrição| Uso de dados para antecipar a necessidade de manutenções antes que se tornem críticas. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Desejável                                     |

## Gerenciamento de combustível
| Código   | RF-001-E                                      |
|----------|------------------------------------------------|
| Nome     | Registrar abastecimentos                      |
| Descrição| Manter um registro de todos os abastecimentos realizados nos veículos. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Essencial                                     |

| Código   | RF-002-E                                      |
|----------|------------------------------------------------|
| Nome     | Cálculo de consumo médio                      |
| Descrição| Calcular a média de consumo de combustível de cada veículo ao longo do tempo. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Importante                                    |

| Código   | RF-003-E                                      |
|----------|------------------------------------------------|
| Nome     | Monitoramento de preços de combustível        |
| Descrição| Acompanhar as variações nos preços do combustível e sugerir momentos estratégicos para abastecimento. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Desejável                                     |

| Código   | RF-004-E                                      |
|----------|------------------------------------------------|
| Nome     | Controle de despesas por categoria            |
| Descrição| Classificar despesas com combustível para um controle financeiro mais eficiente. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Importante                                    |

| Código   | RF-005-E                                      |
|----------|------------------------------------------------|
| Nome     | Relatório de desvios de consumo               |
| Descrição| Gerar relatórios que identifiquem quando o consumo de combustível ultrapassa a média esperada. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Importante                                    |

## Gerenciamento de documentação
| Código   | RF-001-F                                      |
|----------|------------------------------------------------|
| Nome     | Registro de histórico de documentos           |
| Descrição| Acompanhar a renovação e as alterações de documentos de veículos e motoristas. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Essencial                                     |

| Código   | RF-002-F                                      |
|----------|------------------------------------------------|
| Nome     | Armazenamento seguro                          |
| Descrição| Implementar práticas de segurança para proteger documentos sensíveis, como criptografia e controle de acesso. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Importante                                    |

| Código   | RF-003-F                                      |
|----------|------------------------------------------------|
| Nome     | Integração com órgãos reguladores             |
| Descrição| Facilitar a comunicação e a atualização automática com órgãos responsáveis pela regulamentação de veículos e motoristas. |
| Plataforma| Desktop e mobile                             |
| Atores   | Gerente                                       |
| Prioridade| Importante                                    |
