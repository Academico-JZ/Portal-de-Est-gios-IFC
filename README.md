# Portal-de-Est-gios-IFC

# Transcrição do Documento: Estágios IFC

## Estrutura de Módulos

Módulo de Vitrine de Oportunidades
Módulo de Onboarding e Validação Acadêmica
Módulo do Painel da Concedente
Módulo de Formalização e Conformidade Legal
Módulo de Triagem e Seleção
Módulo de Adesão Institucional
Módulo de Moderação e Auditoria da Extensão
Módulo de Métricas e Retenção
Módulo de Governança, LGPD e Segurança

---

## Detalhamento de Requisitos

### Módulo de Vitrine de Oportunidades

_Deve exibir/permitir para o usuário:_

- **Segmentação por Campus e Curso:** Apresentação dinâmica de oportunidades vinculadas estritamente à matriz curricular e à unidade de matrícula do estudante.
- **Modalidade Legal de Estágio:** Etiquetagem padronizada distinguindo Estágio Obrigatório de Não-Obrigatório, com restrição visível de carga horária máxima de 30 horas semanais.
- **Cards Responsivos de Vagas:** Visualização em cartões informativos adaptados para dispositivos móveis, contendo dados sintéticos de remuneração, benefícios e localização.
- **Acesso Gratuito Universal:** Disponibilização integral e sem custos dos serviços de busca e candidatura para estudantes vinculados ao IFC.
- **Sinalizadores de Status da Vaga:** Indicadores visuais do ciclo da vaga (Aberta, Em Seleção, Encerrada ou Vaga Urgente).
- **Índice de Compatibilidade:** Cálculo e exibição da taxa de aderência entre as competências requeridas e a fase atual da matriz curricular do discente.
- **Mural de Vagas Salvas:** Funcionalidade de favoritamento e acompanhamento unificado das oportunidades em que o discente manifestou interesse.
- **Busca Indexada Multicritério:** Motor de busca estruturado por curso, regime de trabalho (presencial/híbrido/remoto), valor de bolsa-auxílio e cidade.

### Módulo de Onboarding e Validação Acadêmica

_Deve orientar o usuário por uma sequência progressiva:_

- **Autenticação Institucional:** Autenticação federada para validação de vínculo institucional ativo e bloqueio de discentes evadidos ou jubilados.
- **Identificação Acadêmica:** Extração e conferência automática do semestre letivo, campus de origem e projeto pedagógico do curso.
- **Preenchimento Progressivo:** Formulário passo a passo para estruturação do perfil discente (contato, competências e histórico) antes do primeiro envio.
- **Completude de Perfil:** Bloqueio de submissão de candidaturas até que 100% dos campos de identificação obrigatórios estejam preenchidos.
- **Indicador de Conclusão:** Exibição de barra de progresso com tempo estimado de conclusão do cadastro em até 5 minutos.
- **Persistência de Sessão:** Armazenamento contínuo em cache para resguardar dados informados em caso de desconexão.

### Módulo do Painel da Concedente

_Deve transformar o conteúdo em recursos rápidos de compreensão:_

- **Sumário Executivo de Candidaturas:** Visão consolidada da listagem de inscritos para triagem ágil por recrutadores corporativos.
- **Funil Visual de Conversão:** Gráficos sintéticos das etapas da vaga (Visualizações > Candidaturas > Selecionados).
- **Catálogo Histórico de Vagas:** Repositório de todas as postagens ativas, inativas e arquivadas vinculadas ao CNPJ da concedente.
- **Triagem Comparativa:** Painel para ordenação de candidatos por período letivo, formação técnica e proximidade geográfica.
- **Registro Interno de Pareceres:** Campo privativo para anotações e notas do recrutador sobre o andamento de entrevistas individuais.

### Módulo de Formalização e Conformidade Legal

_Deve conectar a teoria com situações práticas/reais:_

- **Aderência à Lei 11.788/2008:** Enquadramento regulatório estrito aos dispositivos legais quanto a direitos, benefícios e vedações.
- **Validação de Travas Legais:** Bloqueio automático de publicação para vagas de estágio não-obrigatório sem bolsa-auxílio ou sem apólice de seguro contra acidentes.
- **Assistente de Plano de Atividades:** Seleção via checklist de macroatividades homologadas pelo IFC por matriz curricular, eliminando texto livre com desvio de função.
- **Notificação de Inconformidades:** Emissão de alertas sistêmicos imediatos quando qualquer parâmetro violar as diretrizes do estágio.
- **Exportação Desacoplada:** Produção de artefatos estruturados (JSON/PDF) para autuação do Termo de Compromisso de Estágio no SIGAA, sem escrita direta no banco institucional.

### Módulo de Triagem e Seleção

_Deve permitir ao usuário praticar e acompanhar a evolução:_

- **Filtros de Triagem Seletiva:** Ferramentas para a empresa segmentar inscritos por proximidade territorial, semestre ou habilidades complementares.
- **Templates de Resposta Padronizados:** Modelos de justificativas ágeis para comunicação de dispensa, assegurando retorno ao discente.
- **Pré-visualização de Publicação:** Mecanismo para a empresa revisar a vaga formatada antes da submissão para moderação.
- **Auditoria de Requisitos:** Alertas em tempo real sobre divergências entre a situação acadêmica do discente e os pré-requisitos da vaga.
- **Rastreamento de Processo:** Linha do tempo atualizada do status da submissão (Enviada, Em Análise, Entrevista, Aprovada, Finalizada).

### Módulo de Adesão Institucional

_Deve apresentar uma oferta simples e transparente:_

- **Cadastro Unificado de Vaga:** Fluxo simplificado para publicação de oportunidades individuais por concedentes diretas.
- **Gestão de Lotes de Vagas:** Interface preparada para agentes de integração (CIEE, Super Estágios) cadastrarem demandas em volume.
- **Acesso Corporativo Gratuito:** Garantia de gratuidade institucional integral na utilização da plataforma para entidades concedentes.
- **Validação Automatizada de Convênio:** Verificação eletrônica do status cadastral e convênios prévios da concedente junto ao IFC.
- **Painel Cadastral Corporativo:** Autogestão de dados cadastrais, CNPJ, endereços e representantes legais da empresa.

### Módulo de Moderação e Auditoria da Extensão

_Deve oferecer apoio sem desviar do propósito principal da plataforma:_

- **Canal Direto de Esclarecimentos:** Interface integrada para saneamento de dúvidas técnicas entre a coordenação local e as concedentes.
- **Fila de Moderação por Exceção:** Encaminhamento automático para auditoria humana apenas de vagas que apresentem inconsistências regulatórias.
- **Homologação Pedagógica:** Ferramenta para coordenadores e docentes validarem a compatibilidade das atividades com o perfil do egresso.
- **Repositório Normativo:** Central de arquivos com resoluções do IFC, minutas contratuais e diretrizes vigentes do Ministério da Educação.
- **Disseminação Institucional:** Geração de links curtos e informativos padronizados para divulgação em canais de turmas do campus.

### Módulo de Métricas e Retenção

_Deve incentivar continuidade e retenção do usuário:_

- **Indicadores de Ocupação:** Painel com métricas de vagas abertas, candidaturas geradas e estágios formalizados por campus.
- **Relatórios Institucionais:** Extração de dados consolidados de empregabilidade discente para relatórios da PROEX e do MEC.
- **Alertas de Ciclo de Vida:** Notificações programadas de proximidade de encerramento de prazos de vagas ou de expiração de contratos.
- **Analytics Individual:** Relatório de engajamento discente indicando volume de submissões e taxas de conversão em processos seletivos.
- **Confirmação de Desfecho:** Gatilho operacional obrigatório para a empresa encerrar a vaga declarando discentes contratados ou motivo de fechamento.

### Módulo de Governança, LGPD e Segurança

_Deve proteger o sistema, a operação e os dados do usuário:_

- **Conformidade Regulatória:** Travas de código-fonte impedindo desvio dos parâmetros normativos trabalhistas e educacionais.
- **Privacidade de Currículos:** Bloqueio de indexação pública de dados pessoais e restrição de acesso a dados de contato apenas a recrutadores autorizados.
- **Ciclo de Vida de Dados (LGPD):** Rotinas de anonimização e expurgo programado de registros após 12 meses do encerramento do processo seletivo.
- **Disclaimers Operacionais:** Declaração explícita de que a plataforma atua na aproximação técnica, dependendo do SIGAA para a validação jurídica final.
- **Governança de Conteúdo:** Filtros de vocabulário e checagem de CNPJ em bases públicas para coibir publicidade externa ou fraudes.
- **Controle de Acesso RBAC:** Isolamento multi-tenant garantindo que servidores de um campus gerenciem estritamente as ocorrências de sua unidade.

---

## MVP Inicial

O primeiro teste deve validar se **empresas parceiras do entorno de um campus piloto e estudantes de cursos de tecnologia** demonstram interesse em **um portal self-service de captação de vagas com validação legal automatizada**.

### Incluído no MVP

- Cadastro self-service de concedentes com validação de CNPJ e formulário com travas da Lei 11.788/2008.
- Vitrine de vagas direcionada por curso e campus com candidatura discente em um clique.
- Painel de moderação por exceção para atuação direta da Coordenação de Extensão local.
- Exportação de dados consolidados de contratação em formato padronizado para abertura de processo no SIGAA.

### Fora do MVP

- Integração direta via API/webservice com o banco de dados fechado do SIGAA.
- Disponibilização simultânea e parametrizada da arquitetura multi-tenant para todos os 15 campi do IFC.
- Módulo nativo de assinatura digital avançada (ICP-Brasil) de Termos de Compromisso de Estágio.

---

## Hipótese de Produto

**Empresas concedentes e discentes do IFC** podem demonstrar disposição para consumir e adotar **um sistema web self-service de gestão e divulgação de vagas de estágio** que resolva o problema de **lentidão burocrática, descentralização de informações e riscos de inconformidade legal** através de uma abordagem **orientada a formulários com travas normativas em tempo real, direcionamento por matriz curricular e moderação por exceção**.

---

## Próximo Teste

Publicar uma **Landing Page com mockups interativos e formulário guiado de postagem de vagas** com a mensagem central:

> "Publique vagas de estágio para estudantes do IFC em 5 minutos, com conformidade legal automática e zero burocracia."

Medir principalmente:

- Taxa de preenchimento completo de formulários de vaga pelas empresas parceiras sem erros de conformidade legal.
- Volume de candidaturas válidas submetidas por estudantes na vitrine inicial do campus piloto.
- Tempo despendido pela Coordenação de Extensão na validação de exceções comparado ao fluxo manual anterior.

O teste deve confirmar primeiro **a disposição das empresas parceiras em utilizar o fluxo self-service estruturado em substituição a e-mails e formulários genéricos**. A construção de **módulos de integração complexos e infraestrutura multi-tenant nos servidores institucionais** só deve acontecer depois de **atingir a marca de 30 vagas publicadas validamente por empresas distintas sem necessidade de suporte corretivo manual**.
