tipo: #curso
link: https://on.fiap.com.br/

Parte de [[FIAP DevOps & Agile Culture]]

## DevOps FIAP 

### Capítulo 1 -  DevOps

A proporção de profissionais que trabalham com desenvolvimento front-end, back-end e testes (DEV) é bem maior do que a de profissionais de infraestrutura como *sysadmins*, administradores de banco de dados e de redes, entre outros (OPS).

### Paradoxo Estabilidade x Mudança

- Pedir ao time de desenvolvimento que melhore um produto de software com novas *features* e emprego de novas tecnologias para que fique mais competitivo em relação aos softwares dos concorrentes. ^1891e0

E, ao mesmo tempo...

- Pedir ao time de infraestrutura que aumente a disponibilidade do mesmo produto de software para 99%, tornando-o mais atraente para os usuários, sendo mais *exigente* com a [[Gestão de Mudanças]], dificultando e até impedindo novas mudanças que possam impactar a disponibilidade.

### O que é DevOps

**DevOps** é uma cultura de utilização de práticas e ferramentas que aumenta a velocidade de desenvolvimento de softwares e de outras soluções de tecnologia, mas sem colocar em risco a estabilidade.

### Funcionamento do DevOps

Os times de desenvolvimento e de infraesturura são reunidos em uma única equipe, para compartilhar conhecimentos.

- os *sysadmins* são envolvidos desde o início do projeto da solução;
- os desenvolvedores acompanham o software até o fim, incluindo seu funcionamento em produção.

*Sysadmins* e desenvolvedores não têm que conhecer a fundo as habilidade uns dos outros, mas precisam saber o suficiente para acompanhar e contribuir com o desenvolvimento e operação da solução.

As práticas de DevOps estimulam **ambientes multidisciplinares** em que desenvolvedores e *sysadmins* compartilham conhecimentos, experiências e dores, se tornando mais independentes em relação a tarefas para as quais antes necessitariam de intervenção um do outro.

### Benefícios do DevOps

- **Velocidade de entrega**
	- Através de ferramentas e automação de processos manuais e mais lentos, DevOps aumenta a velocidade e frequência das entregas → **se a entrega é mais rápida, a detecção e correção de problemas também é**.

- **Escalabilidade**
	- Se automatizada a infraestrutura de TI, é possível passar a gerencia-la no modelo de *infrastructure as code*. A vantagem é conseguir escalar os recursos somente à medida que isso se tornar necessário — de acordo com a demanda de requisições, por exemplo.
	
- **Velocidade**
	- Ao reunir as equipes de desenvolvimento e operações em uma só, esta passa a olhar para o mesmo objetivo, aumentando a velocidade das entregas por não precisar levar nenhuma demanda de infra para fora da equipe, que neste caso gerencia o processo de ponta-a-ponta.

- **Colaboração contínua**
	- A união de desenvolvedores e time de operações torna mais aparente o "senso de responsabilidade" de todos: a colaboração entre todos e o compartilhamento de responsabilidades é possível melhorar processos ineficazes e economizar tempo.
	
- **Confiabilidade**
	- Os testes são parte importante da prática de DevOps. Estes são realizados através de processos contínuos e automatizados, o que contribui para aumentar a qualidade e velocidade das entregas.
	
- **Segurança**
	- DevOps aumenta a segurança das soluções através de aplicação automática de políticas de segurança, de controles de acesso, permissionamento e autorização, entre outras.
	
### Melhores práticas do DevOps

Duas das melhores práticas da cultura DevOps são as que mais me chamam a atenção: 

- Atualizações constantes, pequenas e rápidas, ligadas às práticas de [[desenvolvimento ágil]], notadamente [[SCRUM]] e [[Kanban]]; e

- Adoção de uma arquitetura de TI baseada em [[microserviços]], que  divide cada sistema em serviços individuais, cada qual realizando uma função específica para o negócio. Isso desacopla sistemas grandes e complexos e simplifica a coordenação de atualização de seus componentes.

#### Infra como código

A infraestrutura como código (*infrastructure as code*) é a aplicação de desenvolvimento, controle de versão e integração contínua da infraestrutura por meio de APIs. Isso permite que todos os membros do time acessem os recursos de forma programática, sem necessidade de intervenção manual. Os benefícios incluem escalabilidade, reaproveitamento de código e replicação rápida.

#### Integração contínua 

A integração contínua é uma prática que visa realizar testes automatizados  sempre que uma mudança no repositório central de código é realizada. Desta maneira erros são encontrados e corrigidos com mais agilidade e a qualidade do software aumenta.

#### Entrega contínua 

Está prática está intimamente ligada à [[DevOps FIAP - Capítulo 1 -  DevOps#Integração contínua|integração contínua]], ao permitir que após uma alteração no código o desenvolvedor use a integração contínua para testar o que foi alterado e que ele automaticamente prepare um pacote para *deploy* em produção.

#### Monitoração, alarme e *log*

Toda aplicação em ambiente de produção deve produzir *logs* de sua utilização e também do uso que faz da infraestrutura.

A partir dos *logs* podemos monitorar o comportamento das aplicações e como elas estão afetando os usuários. Em caso de necessidade alertas podem ser disparados para que providências sejam tomadas. Já em caso de incidentes fica mais fácil encontrar a causa raiz dos problemas identificados.

#### Comunicação e colaboração

Esta boa prática do DevOps é certamente a mais simples. Pelo fato das equipes de desenvolvimento e de operações agora formarem um único time, é esperado que tanto a colaboração quanto a comunicação aumente "m e melhorem.

Aliás, sempre que uma iniciativa aproxima processos e pessoas, a meu ver, espera-se maiores níveis de comunicação e de colaboração, não sendo esta uma prática exclusiva da adoção do DevOps

### Estágios do processo de DevOps

São sete os estágios de um processo de DevOps, cada um podendo contar com uma ou mais ferramentas de apoio:

- Planejamento (**Plan**);
- Desenvolvimento ou codificação (**Code**);
- Construção (**Build**);
- Teste (**Test**);
- Lançamento/ Entrega (**Release**);
- Implantação (**Deploy**); e
- Monitoração (**Monitor**).

### DevSecOps

**DevSecOps** nada mais é do que a prática de incluir desde o princípio de qualquer projeto de solução de TI a preocupação e a tratativa sobre segurança.

**Security by Default** é o princípio através do qual se deve garantir que a segurança esteja presente em todas as etapas do projeto de solução de TI, desde o início.

Aliás, o curso menciona um movimento de mercado chamado de [[Shifting Security Left]], que visa justamente abordar a segurança o mais cedo possível no processo de DevOps, considerando que o desenvolvimento está mais no começo (à esquerda), e a operação, mais à direita.

---
**Ver também:**
- [[DevOps CALMS]]