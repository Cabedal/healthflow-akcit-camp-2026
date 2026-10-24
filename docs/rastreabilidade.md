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
| `healthflow-backend/app/api/v1/clinical.py` | `691fc0a920a706916e14f6da1d9543bc1b777bc15c97a68152f181cf96b08e57` |

## O que foi conferido

- Cinco papéis de IA e seus registros de ferramentas.
- Busca própria do Auditor antes da conferência da proposta.
- Comunicador limitado à seleção de aberturas aprovadas.
- Curadoria offline com propostas pendentes de aprovação.
- Observabilidade determinística e separação de conteúdo clínico.
- Revisão profissional obrigatória e ausência de confirmação autônoma de destino/despacho.
- Entrada do painel com idempotência, autorização e revisão esperada.

Esta conferência é documental e de engenharia. Não equivale a validação clínica.
Os exemplos JSON foram escritos para fins didáticos e não são prontuários ou logs reais.
