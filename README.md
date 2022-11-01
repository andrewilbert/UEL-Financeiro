# UEL-Financeiro
`Esta documentação está em elaboração.`

Projeto aberto e colaborativo para desenvolvimento de um sistema que simplifique e automatiza ao máximo a administração financeira de uma Unidade Escoteira Local.

## Objetivos
Desta forma, os objetivos serão norteados da seguinte forma:
- **Simplicidade e facilidade** no uso diário é imprescindível;
- Recursos que facilitem a vida do diretor financeiro;
- Recursos que incentivem o **planejamento financeiro**;
- Recursos que reduzam o erro administrativo de controle (integração com banco, templates, etc).
- Se possível, integração direta com o **Paxtu**. Neste caso:
   - Alterações cadastrais serão feitas somente via Paxtu;
   - Nenhuma funcionalidade já existente no Paxtu será replicada ou copiada, salvo situações em que não esteja prevista a implementação naquele sistema, ou que seja considerada inviável para isso;
   - A autenticação de usuários será feita via Paxtu.

> A integração com o **Paxtu** ainda depende de negociação com a UEB e a equipe responsável por aquele sistema, para que sejam disponibilizados web-services ou outro tipo de comunicação.

## Funcionalidades previstas
1. Planejamento e controle financeiro geral da UEL [^financGeral].
1. Planejamento e controle financeiro de atividades escoteiras [^ativEscoteira], facilitado com o uso de templates e estimativas com base nas atividades anteriores e orçamentos.
1. Planejamento e controle financeiro de projetos específicos, tal como os voltados para atendimento da comunidade local ou arrecadação de fundos à médio e longo prazos.

[^financGeral]: O planejamento e controle financeiro GERAL, apesar de óbvio para este sistema, se refere à administração financeira em todos os escopos, incluindo as atividades escoteiras e projetos escoteiros, também mencionados neste documento.
[^ativEscoteira]: O termo "Atividade Escoteira" se refere às atividades realizadas junto com as tropas e alcatéias, seja em sede ou externas.

### Integrações
1. Integração bancária para registro automático de recebimentos e pagamentos.
1. Exportação de registros para controle contábil, que poderá ser feito através de planilhas ou outros sistemas que permitam a importação destes dados; o objetivo principal é evitar erro humano e retrabalho.

### Recursos periféricos (necessários para viabilizar as funcionalidades):
1. Cadastros de membros juvenis e adultos.
1. Cadastro de plano de contas financeiro.
1. Cadastro de plano de contas contábil.
1. Cadastro de atividades escoteiras.
1. Cadastro de fornecedores.
1. Cadastro de produtos e serviços consumidos.
1. Cadastro de orçamentos.
1. ...
