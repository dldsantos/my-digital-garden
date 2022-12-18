- ^^Como faço para incluir os Parameters ou metadados??^^
  id:: 60c9da93-d36b-43a2-92e0-437449441160
- E não é que [a palavra descomissionamento existe mesmo](https://www.dicio.com.br/descomissionamento/)?! 😁
collapsed:: false
## O que é?
	- Definições e práticas que eu adaptei da **[Wikipedia](https://en.wikipedia.org/wiki/Application_retirement)**:
		- **Aposentadoria de aplicações** (_Application retirement_), também chamada de **descomissionamento de aplicações** (_application decommissioning_) e de **sunsetting de aplicações** (_application sunsetting_) é a prática de desativar aplicações de negócio [redundantes](https://en.wikipedia.org/wiki/Data_redundancy) ou obsoletas enquanto se mantém o acesso à seus [dados](https://en.wikipedia.org/wiki/Data_(computing)) históricos.
		- [Aplicações legadas](https://en.wikipedia.org/wiki/Legacy_application) são geralmente mantidas em funcionamento somente para fornecer acesso não-frequente ou esporádico a dados que estão armazenados em seu banco de dados, para atender à políticas, regulamentos ou propósitos de negócio. Com algumas empresas gastando até 75% do valor de seus orçamentos reservados à aplicações com [manutenção](https://en.wikipedia.org/wiki/Data_maintenance), o **descomissionamento de software** pode trazer ganhos e economia significativos.
		- As ações de decomissionamento de aplicações geralmente envolvem a [migração de dados](https://en.wikipedia.org/wiki/Data_migration) do [banco de dados](https://en.wikipedia.org/wiki/Database) da aplicação legada para um outro [repositório de dados](https://en.wikipedia.org/wiki/Software_repository) ou armazenamento em _[archive](https://en.wikipedia.org/wiki/Archive)_ que possa ser acessado de forma independente, segundo padrões de mercado, ou reportado através de ferramentas de [business intelligence](https://en.wikipedia.org/wiki/Business_intelligence).
		- O descomissionamento de aplicações permite que a área de Tecnologia da Informação de uma empresa reduza os custos associados à manutenção de software, hardware e suporte associados à gestão de dados legados.
	- Definições e informações adaptadas de um dos sites do **[governo australiano](https://www.records.nsw.gov.au/recordkeeping/advice/decommissioning-systems)**:
		- O descomissionamento de aplicações é o processo através do qual o uso de uma aplicação de negócios ou sistema é **removido de uma empresa**. Descomissionar uma aplicação requer **análise dos dados do sistema**, **identificação de tais dados**, **metadados** e **documentação do sistema** que deve ser levantada e mantida, e um processo confiável para **exclusão de dados residuais** no sistema.
		- ^^Conceito útil:^^ Um sistema deve ser descomissionado **sempre que**:
			- o sistema for **substituído** por um novo, que cobre ou realiza as mesmas funcionalidades; ou
			- o sistema é considerado **obsoleto** porque já não serve mais para suportar o(s) processo(s) de negócio a que se relaciona.
		- There are a range of business drivers for decommissioning, including:
			- transitions to new generation systems
			- project completion or termination
			- structural reorganisation
			- transfer of functions due to regulatory and organisational changes
			- ^^disposal of physical assets^^.
			- Além disso, considerar: riscos de obsolescência tecnológica, de segurança, custos com licenciamento, déficit na documentação do sistema e na equipe capaz de prestar suporte ao mesmo.
		- [...] have accumulated data in systems which have been superseded for business, technical or regulatory reasons. Organisations that have identified these systems require a process to accountably manage the decommissioning of data in the system.
		  id:: 60c9db3e-8f0a-4cf7-9e52-74aa0685d0d8
			- ^^Ideia^^ Apresentar a [afirmação acima]((60c9db3e-8f0a-4cf7-9e52-74aa0685d0d8)) como sendo verdadeira para uma área de negócios da empresa.
		- The following are **common scenarios** in which decommissioning projects will occur.
			- **Project-based decommissioning**
				- Quando a desativação de um sistema ocorre devido a um ou mais projetos que vão substitui-lo, consolidá-lo ou racionalizá-lo. Neste caso as atividades de descomissionamento devem ser planejadas junto às demais atividades do projeto.
			- **Application rationalisation projects**
				- Quando a desativação ocorre com base no **portfólio atual de aplicações da empresa** e a partir de levantamento junto às áreas de negócio para determinar as aplicações que não mais suportam os processos de negócio, normalmente porque foram substituídas por novos sistemas e ferramentas.
			- **Infrastructure rationalisation projects**
				- Quando a desativação ocorre por conta de análises de utilização de infraestrutura que visam o entendimento de quanto custa a retenção, além do período estritamente necessário, de dados e aplicações legadas. Entender os custos com infraestrutura associados ao portfólio atual de aplicações da empresa permite identificar **oportunidades imediatas de redução de custos**, como deixar de usar storage de alta performance para dados de prioridade baixa e revisar as políticas de backup para não manter dados além do necessário.
## Fases ou etapas
	- Uma sugestão de como poderia ser desenhado o **processo**:
		- ![](https://cdn.sketchbubble.com/pub/media/catalog/product/optimized/e/d/edfadcdf16811bdf9b6a5ab51688c927c12dffb2196786a8e1eb80977ed3f398/system-decommissioning-slide3.png)
## Sugestão de Checklist ([fonte](https://its.unl.edu/bestpractices/decommissioning-process-guide))
collapsed:: false
	- **Iniciar descomissionamento do serviço**
		- O gerente do serviço submete uma solicitação de descomissionamento para o Diretor responsável pelo mesmo, incluindo o racional para esta ação (motivo para tomar a decisão).
			- ^^**Dúvida:**^^ quem faria o papel de gerente do serviço no caso da área de TI da Avibras? Um analista de infraestrutura? Um responsável técnico? Ou o AN?
		- O gerente do serviço se assegura de que pode proceder com o planejamento de descomissionamento (há aprovação do Diretor responsável e da área de TI)
		- **MILESTONE:** Planejamento de descomissionamento aprovado
	- **Planejar o descomissionamento**
	  collapsed:: false
		- **Planejamento do descomissionamento**
			- Definir **responsável pela gestão de projeto** para o descomissionamento.
			- O **responsável pela gestão do projeto** identifica e documenta quem são os responsáveis pelo processo.
			- **Identificar** e **correlacionar** os **componentes** e **usuários** do serviço.
				- Se houver alternativas disponíveis, identificar quais são e desenvolver um plano de migração para os serviços alternativos.
			- Desenvolver um **plano de comunicação** para cada usuário e componente.
			- O **responsável pela gestão do projeto** estabelecer datas alvo para os seguintes 7 __milestones__ de projeto e os comunica ao gerente do serviço:
				- Planejamento concluído;
				- Descomissionamento do serviço aprovado;
				- Estabelecer data para **desconectar** o serviço - tornando-o __off-line__ (ao estabelecer esta data, deve-se considerar o impacto aos usuários, já que depois desta data eles não serão mais capazes de acessar o serviço);
				- Estabelecer o __point of no return__;
				- Estabelecer data para **término** do serviço (ao estabelecer esta data, considere SLAs, licenciamento e garantias, pois o serviço somente estará atrelado a tais obrigações até esta data);
				- Conclusão do descomissionamento;
				- Remoção dos dados.
			- **MILESTONE:** Planejamento concluído.
	- **Obter aprovação final para o plano**
		- **Aprovação do descomissionamento**
			- O gerente do serviço submete o plano de descomissionamento do serviço a todas as partes interessadas, tanto em TI quanto na(s) área(s) de negócio, para revisão e aprovação.
			- O gerente do serviço verifica que todas as partes interessadas aprovaram o plano de descomissionamento do serviço.
		- **MILESTONE:** Plano de descomissionamento aprovado, o que signfiica que a sua execução pode começar.
	- **Desconectar o serviço**
		- **Tirar o serviço do ar (torná-lo __off-line__)**
			-
			  #+BEGIN_IMPORTANT
			  As datas de **desconexão** e de **término** do serviço são as mais importantes, e devem ser comunicadas efetivamente a todos os usuários afetados e membros da área de TI.
			  #+END_IMPORTANT
				- Notificar **nível tático** aplicável sobre datas de **desconexão** e de **término** do serviço
				- Notificar o time de TI sobre datas de **desconexão** e de **término** do serviço
				- Se o serviço a ser descomissionado estiver publicado no catálogo de serviços de TI, emitir um comunicado quanto à data a partir da qual ele não estará mais disponível para acesso.
		- Usuários não poderão mais acessar o sistema após a data de **desconexão**
			- Criar **planos de comunicação** que direcionem os usuários à serviços alternativos
			- **Remover os acessos** ao serviço descomissionado
			- Modificar o **monitoramento do serviço** (WhatsUp) para que seja colocado em modo de manutenção
			- Modificar a **gestão de ativos** para refletir o status do processo de descomissionamento
			- Notificar a área de Segurança da Informação de que o serviço está sendo descomissionado e quando sua varredura (__scan__) deve ser interrompida
		- **MILESTONE:** Serviço off-line – __indisponível para os usuários.__
	- **Preparar descomissionamento**
	  collapsed:: false
		- **Preparação para o término do serviço**
			-
			  #+BEGIN_IMPORTANT
			  Durante esta etapa o serviço deve permanecer preparado para voltar à operação, se necessário. Os recursos (pessoas e hardware) devem permanecer alocados até o alcance da data de término do serviço.
			  #+END_IMPORTANT
			- **Criar um __archive__** do serviço descomissionado exatamente da forma como se encontrava no dia em que ficou __off-line__.
			- Incluir neste __archive__ os arquivos de dados que existiam durante as condições de operação normal da solução.
			- Garantir conformidade com as políticas e requisitos legais de __archiving__.
			- Armazenar o ___archive___ em formato posteriormente utilizável.
			- **Excluir os dados** (a menos que venham a ser necessários, e, somente durante o período durante o qual seu armazenamento for legalmente necessário)
			- **Garantir que os dados serão removidos após alcançada a data limite para seu armazenamento legal.**
		- **Documentar o serviço**
			- Como deve ser **acessado o __archive__** do serviço descomissionado?
			- Que _dependências_ este serviço possui quanto a **fornecedores** e **hardware**?
			- Quem são os **especialistas** neste serviço?
		- Parar de cobrar os usuários pelo serviço (___chargeback___)
		- Remover o serviço (se listado) do Catálogo de Serviços
		- Verificar que quaisquer funções identificadas como "ainda necessárias" tenham sido migradas
		- Armazenar o código fonte no repositório apropriado para referência futura e eventual reuso em novos projetos
		- **Notificar descomissionamento** – a seguir, uma lista _não-exaustiva_ de contatos que precisam ser notificados:
			- Revogação de certificados (ex: __Code Signing__, SSL)
			- Regras de __firewall__
			- Contas de serviço (ex: LDAP, AD)
			- Serviços de backup (ex: AVAMAR)
			- Monitoramento automatizado (ex: Splunk)
			- Scans de segurança e firewall de aplicações web
			- Gestão de ativos
			- Listagem de dados de PCI (__Payment Card Industry__)
			- Listagem de PII (__Personal Identifiable Information__)
			- Descrições de cargo
			- Remoção do sistema da __whitelist__ de outros sistemas
		- **MILESTONE:** __Point of No Return__ – a partir deste ponto os preparativos para descomissionamento do serviço estão concluídos.
	- **Terminar o serviço**
		- **Término do serviço**
			- Desalocar os recursos
				- Recursos humanos se tornam disponíveis para outras atividades
				- Recursos de infraestrutura são reaproveitados ou descartados
			- Suspender pagamentos aos fornecedores quanto à solução desativada
			- Finalizar cobranças
				- Cobrança final aos clientes
				- Reembolso aos clientes por período não utilizado do serviço
		- **MILESTONE:** Serviço terminado – o serviço foi terminado e agora restam apenas tarefas de limpeza.
	- **Concluir o descomissionamento**
		- **Conclusão do descomissionamento**
			- Remover/ realocar hardware, o que pode incluir (mas não está limitado às) seguintes atividades:
				- Cancelar o registro de endereços MAC
				- Remover registros de DNS
				- Documentar ativos
				- Atualizar inventários de aplicação
				- Devolver hardware em __leasing__
				- Enviar discos rígidos para descarte apropriado
				- Notificar quanto à portas de rede disponíveis
				- Notificar quanto à espaço em rack disponível
			- O **responsável pela gestão do projeto** realiza o **sign-off**, atestando que o descomissionamento foi concluído
		- **MILESTONE:** Descomissionamento concluído.
	- **Após a conclusão do descomissionamento**
		- **Remoção dos dados**
			- Exclusão de ___archives___
			- Arquivamento ou exclusão do registro no _asset management_
			- Licenças liberadas
		- **MILESTONE:** Dados arquivados removidos (arquivos/ registro final do serviço é excluído)