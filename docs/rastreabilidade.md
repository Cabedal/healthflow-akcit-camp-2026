# Rastreabilidade da documentação dos agentes

Conferência da implementação local em 24/10/2026. Os caminhos abaixo são
referências ao projeto HealthFlow; este repositório contém somente documentação.
Os hashes SHA-256 identificam os arquivos lidos, sem publicar seu conteúdo.

| Módulo conferido | SHA-256 |
| --- | --- |
| `healthflow-backend/app/services/clinical_conversation.py` | `c95671d5397920311972e32742deffc9a7118c5a947228592c8c57d90b5d80c3` |
| `healthflow-backend/app/services/clinical_agent_tools.py` | `7953019bf9d1a82669333e9e08ca38816ef023213300850cfa43bf4eafc383f9` |
| `healthflow-backend/app/services/clinical_agents.py` | `c791d4df3f0eaba0e0e842de36c94468dfe36ce92c14f1c56baa4185d0d02699` |
| `healthflow-backend/app/services/clinical_communication.py` | `9740bd43d14ba1ad5db981f64648e981db64b911288d41652fdb7e86d7c993e3` |
| `healthflow-backend/app/services/clinical_learning.py` | `252490fa65565e12875894b8526fe69c0c4ffe0a4032b0fac31a30765bd6863b` |
| `healthflow-backend/app/services/clinical_observability.py` | `915f75dad22d23da8e3ccece1d4b7b8f47b297ff01e69c4126a85cdefe5e943a` |
| `healthflow-backend/app/clinical/kernel.py` | `b3c97714031422e2439572f3283079d7e31174bb5b0987dcd3b5b695e4e17da8` |
| `healthflow-backend/app/clinical/contracts.py` | `1f65157eb4caa4ab14c74a60b9e62aaf81d8d579e61282ccc86202407be40556` |
| `healthflow-backend/app/api/v1/clinical.py` | `691fc0a920a706916e14f6da1d9543bc1b777bc15c97a68152f181cf96b08e57` |
| `healthflow-backend/app/services/clinical_persistence.py` | `cc13e0dc7a4516a38ce15c627f3723cf677bd9f7b2338662165642af2d4f5578` |
| `healthflow-backend/app/api/v1/integration.py` | `721d9fe57a52f843a93a54915e758cc0002d1cb49c564fda60e768aecb6e92ff` |
| `src/components/SbarModal.tsx` | `7509eadf8d5cfa43a5b639338382763cc452adc68d3b58e6adbfbc1eb73b720d` |
| `src/domain/sbar.ts` | `e5fda3774a52c569cfe7c8b10b97128dc699b7ce932ad9fe031ee5bf900ca857` |

## O que foi conferido

- Cinco papéis de IA e seus 18 registros de ferramentas.
- Busca própria do Auditor antes da conferência da proposta.
- Comunicador limitado à seleção de aberturas aprovadas.
- Curadoria offline com propostas pendentes de aprovação.
- Observabilidade determinística e separação de conteúdo clínico.
- Ficha digital no painel: proposta de prioridade, encaminhamento, recursos, prazo, apoio, alternativas e pendências.
- Três estados de prioridade propostos: alerta imediato, revisão prioritária e inconclusivo.
- Revisão profissional obrigatória e ausência de confirmação autônoma de destino/despacho.
- Entrada do painel com idempotência, autorização e revisão esperada.
- Distinção entre ficha digital, composição SBAR e o PDF básico de decisão assinada.

Esta conferência é documental e de engenharia. Não equivale a validação clínica.
Os exemplos JSON foram escritos para fins didáticos e não são prontuários, logs reais
ou resultados de uma execução do modelo. O plano de encaminhamento ilustrativo foi
validado estruturalmente contra o contrato ReferralPlan, sem consulta à API de IA.
