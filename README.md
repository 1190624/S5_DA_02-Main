# LAPR5-2022/2023

Repositório Main para o projeto integrador de LAPR5. Os repositórios relativos às diferentes APIs estão divididos de forma a ser possível fazer deploy dos mesmos.

------------------------------------------------

### **System Overview**

![d](./Docs/Vis%C3%A3o%20Geral.jpg)

-----------------------
## Use Cases:
1. Criar Armazém
2. Listar Armazém
3. Editar Armazém
4. Criar Entrega
5. Listar Entrega
6. Editar Entrega
7. Criar Camião
8. Listar Camião
9. Editar Camião
10.	Criar Percurso entre dois armazéns
11.	Listar Percurso entre dois armazéns
12.	Editar Percurso entre dois armazéns
13.	Como gestor de armazém pretendo Criar um Armazém
14.	Como gestor de armazém, pretendo listar Armazéns
15.	Como gestor de armazém pretendo Criar uma Entrega
16.	Como gestor de armazém, pretendo listar Entregas
17.	Como gestor de frota pretendo Criar um Camião
18.	Como gestor de logística pretendo listar Camiões
19.	Como gestor de logística pretendo Criar um Percurso entre dois armazéns
20.	Como gestor de logística pretendo listar Percursos
21.	Como gestor de logística pretendo obter o Planeamento da rota para 1 camião e 1 dado dia  
22.	Como gestor de logística pretendo visualizar graficamente em 3D a rede viária. A visualização deverá ocupar a totalidade da área útil do browser. Modelar a rede viária
23.	Como gestor de logística pretendo visualizar graficamente os armazéns existentes. Criar ou importar os modelos 3D correspondentes (por exemplo, OBJ, GLTF, 3DS ou outros)
24.	Como gestor de logística pretendo controlar a visualização. Adicionar os comandos da câmara pan, zoom e orbit
25.	Efetuar Planeamento de frota para 1 camião e 1 dado dia
26.	Recebendo os dados das entregas a fazer por 1 camião e dos troços entre armazéns: gerar todas as trajetórias possíveis através de sequências de armazéns onde deverão ser feitas as entregas
27.	Avaliar essas trajetórias de acordo com o tempo para completar todas as entregas e voltar ao armazém base de Matosinhos e escolher a solução que permite a volta do camião mais cedo
28.	Aumentar a dimensão do problema (colocando mais armazéns a visitar) e verificar até que dimensão é viável proceder do modo adotado (com um gerador de todas as soluções) efetuando um estudo de complexidade do problema
29.	implementar heurísticas que possam rapidamente gerar uma solução (não necessariamente a melhor) e avaliar a qualidade dessas heurísticas (por exemplo, entregar no armazém mais próximo; efetuar de seguida a entrega com maior massa; combinar distância para a entrega com massa entregue)
30.	Pipeline de build contínuo para módulo master data
31.	Deployment automático de um dos módulos via pipeline num ambiente cloud   
32.	Como administrador do sistema quero que o deployment de um dos módulos do RFP numa VM do DEI seja sistemático, validando de forma agendada com o plano de testes
33.	Como administrador do sistema quero que apenas os clientes da rede interna do DEI (cablada ou via VPN) possam aceder à solução
34.	Como administrador do sistema quero que os clientes indicados na user story anterior possam ser definidos pela simples alteração deu m ficheiro de texto
35.	Como administrador quero identificar e quantificar os riscos envolvidos na solução preconizada
36.	Como administrador pretendo criar uma conta de utilizador   indicando um número de telefone para contacto direto bem como o tipo de utilizador
37.	Como administrador pretendo cancelar uma conta anonimizando os dados pessoais que tenham sido recolhidos
38.	Como utilizador pretendo autenticar-me na aplicação via SSO (e.g. AzureAD, Google, Facebook)
39.	Como gestor de logística pretendo obter o Planeamento de rota de toda a frota e visualização da melhor solução usando algoritmo genético
40.	Como gestor de logística pretendo visualizar graficamente um camião de distribuição. Criar ou importar o modelo 3D correspondente (por exemplo, OBJ, GLTF, 3DS ou outro).
41.	Como gestor de logística pretendo aumentar o realismo da representação gráfica, através de Iluminação adequada da cena, contemplando pelo menos uma fonte de luz ambiente e uma fonte de luz direcional, com projeção de sombras;
42.	Como gestor de logística pretendo animar interactivamente o movimento do camião, permitindo desta forma a visualização do plano de entregas. Movimento interativo controlado pelo utilizador: usar quatro teclas de navegação. Implementar a deteção de colisões, de modo a impedir que o camião ultrapasse os limites da rede viária;
43.	Como gestor de logística pretendo animar automaticamente o movimento do camião, permitindo desta forma a visualização do plano de entregas. Movimento automático controlado pelo computador, dispensa a implementação da deteção de colisões.
44.	Como cliente do projeto pretendo um relatório que, descrevendo a solução encontrada e considerando as normas do RGPD, identifique concretamente os dados pessoais utilizados, bem como a finalidade e fundamento para o tratamento desses dados pessoais.
45.	Como gestor de logística pretendo uma solução para o problema usando Algoritmos Genéticos
46.	Como gestor de logística pretendo predicados que permitam a atribuição de entregas a um lote de camiões (por exemplo, 3 camiões), assumindo que as entregas recebidas ultrapassam em conjunto a capacidade de carga do camião
47.	Como cliente do projeto pretendo um estudo bibliográfico sobre a aplicação de uma das seguintes tecnologias a este problema: robótica inteligente; visão por computador; aprendizagem automática.
48.	Como gestor de logística pretendo filtrar e ordenar as viagens por Destino, Hora de entrega, Tempo de descarregamento (e outras caraterísticas)
49.	Como gestor de logística pretendo listar os caminhos por página
50.	Como gestor de logística pretendo filtrar e ordenar os empacotamentos pelas suas caraterísticas
51.	Como gestor de armazéns, pretendo inibir um armazém
52.	Como gestor de logística pretendo inibir um camião
53.	Planeamento de frota com persistência da solução (viagens).
54.	Planeamento de frota: utilização de módulo de planeamento em Prolog e outro algoritmo simulado como estratégias distintas de planeamento
55.	Como administrador da organização quero um plano de recuperação de desastre que satisfaça o MBCO definido na US B5
56.	Como administrador da organização quero que me seja apresentada de forma justificada a ou as alterações a realizar na infraestrutura por forma a assegurar um MTD (Maximum Tolerable Downtime) de 20 minutos
57.	Como administrador de sistemas quero que seja realizada uma cópia de segurança da(s) DB(s) para um ambiente de Cloud através de um script que a renomeie para o formato <nome_da_db>_yyyymmdd sendo <nome_da_db> o nome da base de dados, yyyy o ano de realização da cópia, mm o mês de realização da cópia e dd o dia da realização da cópia
58.	Como administrador de sistemas quero que utilizando o Backup elaborado na US C3, seja criado um script quer faça a gestão dos ficheiros resultantes desse backup, no seguinte calendário. 1 Backup por mês no último ano, 1 backup por semana no último mês, 1 backup por dia na última semana
59.	Como administrador de sistemas quero que o processo da US C3 seja mantido no log do Linux, num contexto adequado, e alertado o administrador no acesso à consola se ocorrer uma falha grave neste processo
60.	Como administrador de sistemas quero que a cópia de segurança da US C3 tenha um tempo de vida não superior a 7 (sete) dias exceto no indicado na US C4
61.	Como administrador da organização quero que me seja apresentado um BIA (Business Impact Analysis) da solução final, adaptando se e onde aplicável o(s) risco(s) da US B4
62. Como administrador de sistemas quero que o administrador tenha um acesso SSH à maquina virtual, apenas por certificado, sem recurso a password


---------------------------

## Views (Níveis 1, 2, 3)

- [Views](#views)
	- **Nível 1**
		- [Vista Lógica](./Docs/SprintA/N%C3%ADvel%20%231/Vista%20L%C3%B3gica.png)
		- [Vista Cenário](./Wiki/diagramas/Design/Level_1/VF_1.md)
		- **Vista de Processos**
			- [UC G.1.1](./Docs/SprintA/N%C3%ADvel%20%231/N%C3%ADvel%20%231-Vista%20Processo%20UC%20G.1.1.png)
			- [UC G.1.2](./Docs/SprintA/N%C3%ADvel%20%231/N%C3%ADvel%20%231-Vista%20Processo%20UC%20G.1.2.png)
			- [UC G.1.3](./Docs/SprintA/N%C3%ADvel%20%231/N%C3%ADvel%20%231-Vista%20de%20Processo%20UC%20G.1.3.png)
			- [UC G.2.1](./Docs/SprintA/N%C3%ADvel%20%231/N%C3%ADvel%20%231-Vista%20Processo%20UC%20G.2.1.png)
			- [UC G.2.2](./Docs/SprintA/N%C3%ADvel%20%231/N%C3%ADvel%20%231-Vista%20Processo%20UC%20G.2.2.png)
			- [UC G.2.3](./Docs/SprintA/N%C3%ADvel%20%231/N%C3%ADvel%20%231-Vista%20de%20Processo%20UC%20G.2.3.png)
			- [UC L.1.1](./Docs/SprintA/N%C3%ADvel%20%231/N%C3%ADvel%20%231-Vista%20Processo%20UC%20L.1.1.png)
			- [UC L.1.2](./Docs/SprintA/N%C3%ADvel%20%231/N%C3%ADvel%20%231-Vista%20de%20Processo%20UC%20L.1.2.png)
			- [UC L.1.3](./Docs/SprintA/N%C3%ADvel%20%231/N%C3%ADvel%20%231-Vista%20de%20Processo%20UC%20L.1.3.png)
			- [UC L.2.1](./Docs/SprintA/N%C3%ADvel%20%231/N%C3%ADvel%20%231-Vista%20Processo%20UC%20G.2.1.png)
			- [UC L.2.2](./Docs/SprintA/N%C3%ADvel%20%231/N%C3%ADvel%20%231-Vista%20de%20Processo%20UC%20L.2.2.png)
			- [UC L.2.5](./Docs/SprintA/N%C3%ADvel%20%231/N%C3%ADvel%20%231-Vista%20Processo%20UC%20L.2.5.png)
	- **Nível 2**
		- [Vista Lógica](./Docs/SprintA/N%C3%ADvel%20%232/N%C3%ADvel%20%232-Vista%20L%C3%B3gica%20Main.png)
		- [Vista Física](./Docs/SprintA/N%C3%ADvel%20%232/N%C3%ADvel%20%232-Vista%20F%C3%ADsica%20Main.png)
		- **Vista de Processos**
			- [UC G.1.1](./Docs/SprintA/N%C3%ADvel%20%232/N%C3%ADvel%20%232-Vista%20Processo%20UC%20G.1.1.png)
			- [UC G.1.2](./Docs/SprintA/N%C3%ADvel%20%232/N%C3%ADvel%20%232-Vista%20Processo%20G.1.2.png)
			- [UC G.1.3](./Docs/SprintA/N%C3%ADvel%20%232/Nivel%20%232-Vista%20Processo%20UC%20G.1.3.png)
			- [UC G.2.1](./Docs/SprintA/N%C3%ADvel%20%232/N%C3%ADvel%20%232-Vista%20Processo%20UC%20G.2.1.png)
			- [UC G.2.2](./Docs/SprintA/N%C3%ADvel%20%232/N%C3%ADvel%20%232-Vista%20Processo%20UC%20G.2.2.png)
			- [UC G.2.3](./Docs/SprintA/N%C3%ADvel%20%232/N%C3%ADvel%20%232-Vista%20Processo%20UC%20G.2.3.png)
			- [UC L.1.1](./Docs/SprintA/N%C3%ADvel%20%232/N%C3%ADvel%20%232-Vista%20Processo%20L.1.2.png)
			- [UC L.1.2](./Docs/SprintA/N%C3%ADvel%20%232/N%C3%ADvel%20%232-Vista%20Processo%20L.1.2.png)
			- [UC L.1.3](./Docs/SprintA/N%C3%ADvel%20%232/N%C3%ADvel%20%232-Vista%20de%20Processo%20UC%20L.1.3.png)
			- [UC L.2.1](./Docs/SprintA/N%C3%ADvel%20%232/N%C3%ADvel%20%232-Vista%20Processo%20UC%20L.2.1.png)
			- [UC L.2.2](./Docs/SprintA/N%C3%ADvel%20%232/N%C3%ADvel%20%232-Vista%20de%20Processo%20UC%20L.2.2.png)
			- [UC L.2.5](./Docs/SprintA/N%C3%ADvel%20%232/N%C3%ADvel%20%232-Vista%20Processo%20UC%20G.2.3.png)
		- [Mapeamento Vista Física-Implementação](./Docs/SprintB/Mapeamento%20de%20Vistas/N%C3%ADvel%20%232-Vista%20F%C3%ADsica.png)
		- [Mapeamento Vista Lógica-Implementação](./Docs/SprintB/Mapeamento%20de%20Vistas/N%C3%ADvel%20%232-Vista%20Implementa%C3%A7%C3%A3o_Vista%20L%C3%B3gica.png)
	- **Nível 3**
		- [Vista Lógica Gestão de Armazéns](./Docs/SprintA/N%C3%ADvel%20%233/N%C3%ADvel%20%233-Vista%20L%C3%B3gica%20Gest%C3%A3o%20Armaz%C3%A9m%20Main.png)
        - [Vista Lógica Logística](./Docs/SprintA/N%C3%ADvel%20%233/N%C3%ADvel%20%233-Vista%20L%C3%B3gica%20Log%C3%ADstica%20Main.png)
		- [Vista de Implementação Gestão de Armazéns](./Docs/SprintA/N%C3%ADvel%20%233/N%C3%ADvel%20%233-Vista%20Implementa%C3%A7%C3%A3o%20Gest%C3%A3o%20Armaz%C3%A9m.png)
        - [Vista de Implementação Logística](./Docs/SprintA/N%C3%ADvel%20%233/N%C3%ADvel%20%233-Vista%20L%C3%B3gica%20Log%C3%ADstica%20Main.png)
		- **Vista de Processos**
			- [UC G.1.1](./Docs/SprintA/N%C3%ADvel%20%233/N%C3%ADvel%20%233-Vista%20Processo%20UC%20G.1.1.png)
			- [UC G.1.2](./Docs/SprintA/N%C3%ADvel%20%233/N%C3%ADvel%20%233%20-%20Vista%20Processo%20UC%20G.1.2.png)
			- [UC G.1.3](./Docs/SprintA/N%C3%ADvel%20%233/N%C3%ADvel%20%233%20-%20Vista%20Processo%20UC%20G.1.3.png)
			- [UC G.2.1](./Docs/SprintA/N%C3%ADvel%20%233/N%C3%ADvel%20%233%20-Vista%20Processo%20UC%20G.2.1.png)
			- [UC G.2.2](./Docs/SprintA/N%C3%ADvel%20%233/N%C3%ADvel%20%233%20-Vista%20Processo%20UC%20G.2.2.png)
			- [UC G.2.3](./Docs/SprintA/N%C3%ADvel%20%233/N%C3%ADvel%233%20-%20Vista%20de%20Processo%20UC%20G.2.3.png)
			- [UC L.1.1](./Docs/SprintA/N%C3%ADvel%20%233/N%C3%ADvel%20%233%20-Vista%20Processo%20UC%20L.1.2.png)
			- [UC L.1.2](./Docs/SprintA/N%C3%ADvel%20%233/N%C3%ADvel%20%233%20-Vista%20Processo%20UC%20L.1.2.png)
			- [UC L.1.3](./Docs/SprintA/N%C3%ADvel%20%233/N%C3%ADvel%20%233%20-%20Vista%20de%20Processo%20UC%20L.1.3.png)
			- [UC L.2.1](./Docs/SprintA/N%C3%ADvel%20%233/N%C3%ADvel%233%20-%20Vista%20de%20Processo%20UC%20L.2.1.png)
			- [UC L.2.2](./Docs/SprintA/N%C3%ADvel%20%233/N%C3%ADvel%20%233%20-Vista%20Processo%20UC%20L.2.2.png)
			- [UC L.2.3](./Docs/SprintA/N%C3%ADvel%20%233/N%C3%ADvel%233%20-%20Vista%20de%20Processo%20UC%20G.2.3.png)

--------------------------------------------------------

# Views

Será adotada a combinação de dois modelos de representação arquitetural: C4 e 4+1.

O Modelo de Vistas 4+1 [[Krutchen-1995]](References.md#Kruchten-1995) propõe a descrição do sistema através de vistas complementares permitindo assim analisar separadamente os requisitos dos vários stakeholders do software, tais como utilizadores, administradores de sistemas, project managers, arquitetos e programadores. As vistas são deste modo definidas da seguinte forma:

- Vista lógica: relativa aos aspetos do software visando responder aos desafios do negócio;
- Vista de processos: relativa ao fluxo de processos ou interações no sistema;
- Vista de desenvolvimento: relativa à organização do software no seu ambiente de desenvolvimento;
- Vista física: relativa ao mapeamento dos vários componentes do software em hardware, i.e. onde é executado o software;
- Vista de cenários: relativa à associação de processos de negócio com atores capazes de os espoletar.

O Modelo C4 [[Brown-2020]](References.md#Brown-2020)[[C4-2020]](References.md#C4-2020) defende a descrição do software através de quatro níveis de abstração: sistema, contentor, componente e código. Cada nível adota uma granularidade mais fina que o nível que o antecede, dando assim acesso a mais detalhe de uma parte mais pequena do sistema. Estes níveis podem ser equiparáveis a mapas, e.g. a vista de sistema corresponde ao globo, a vista de contentor corresponde ao mapa de cada continente, a vista de componentes ao mapa de cada país e a vista de código ao mapa de estradas e bairros de cada cidade.
Diferentes níveis permitem contar histórias diferentes a audiências distintas.

Os níveis encontram-se definidos da seguinte forma:
- Nível 1: Descrição (enquadramento) do sistema como um todo;
- Nível 2: Descrição de contentores do sistema;
- Nível 3: Descrição de componentes dos contentores;
- Nível 4: Descrição do código ou partes mais pequenas dos componentes (e como tal, não será abordado neste DAS/SAD).

Pode-se dizer que estes dois modelos se expandem ao longo de eixos distintos, sendo que o Modelo C4 apresenta o sistema com diferentes níveis de detalhe e o Modelo de Vista 4+1 apresenta o sistema de diferentes perspetivas. Ao combinar os dois modelos torna-se possível representar o sistema de diversas perspetivas, cada uma com vários níveis de detalhe.

Para modelar/representar visualmente, tanto o que foi implementado como as ideias e alternativas consideradas, recorre-se à Unified Modeling Language (UML) [[UML-2020]](References.md#UML-2020) [[UMLDiagrams-2020]](References.md#UMLDiagrams-2020).

-------------------------------------------------

### Modelo de Domínio
![Modelo Domínio](./Docs/SprintA/Modelo%20Dom%C3%ADnio.png)

------------------------------------------------

# Architecture Background

Foi utilizada uma arquitetura baseada em Onion, visto que é a mais fácil de *aumentar* no futuro, caso seja preciso aumentar o sistema.

A arquitetura Onion foi utilizada nos módulos de Gestão de Armazéns, de Logística e Gestão de Utilizadores. No módulo SPA foi utilizada uma arquitetura Component Based.
  
## Problem Background

### System Overview

A empresa EletricAcme, S.A. pretende um sistema que lhe permita gerir a sua frota de camiões elétricos na distribuição de mercadorias entre os vários armazéns da empresa.

### Context

A empresa dá prioridade a produtos que afetem o menos possível o ambiente e também por
essa razão optou por fazer as entregas entre o armazém de Matosinhos e os armazéns dos outros municípios através de uma frota de camiões elétricos. Para isso tomou a decisão de colocar junto
ao armazém de todas as lojas sistemas de carregamento rápido, para, quando for necessário, os
camiões elétricos poderem ter as suas baterias carregadas.



### Quality attributes

Os atributos de qualidade são categorizados e sistematizados segundo o modelo [FURPS+](https://pt.wikipedia.org/wiki/FURPS).

#### **Funcionalidade**
1. Cada sistema só poderá aceder aos dados que lhe dizem respeito.
2. Deve ser auditada e verificada a integridade da informação a que os sistemas acedem.
3. Com vista à necessidade de saber e necessidade de conhecer, toda a informação deve estar protegida de acessos indevidos. Ou seja, o princípio de minimização de acesso ao que é essencial para cada utilizador/aplicação, criação de túneis para transferência de informação, avaliação da integridade de dados e aplicações, e encriptação/minimização dos dados.
4. Uma vez que o módulo de gestão de encomendas se encontra virado para o exterior, é necessário ter especial atenção com a privacidade e proteção de dados à luz do RGPD. Assim é necessário que o sistema cumpra a legislação em vigor e, em especial, disponibilize as informações legais e informe o utilizador aquando do seu registo, bem como permita aceder e cancelar a sua conta nos casos e nas condições legalmente permitidas.

#### **Usabilidade**
5. A SPA deve permitir acesso a todos os módulos do sistema: gestão de armazéns, planeamento e logística, bem como RGPD.

#### **Confiabilidade (Reliability)**
7. O sistema deve estar operacional 24 horas por dia, isto é, o tempo de paragem deve ser nulo, salvo algum problema ou perda dos serviços externos ao sistema, como é o caso das bases de dados (MongoDB, MariaDB).
8. A estimativa de tempo, no qual o sistema deve estar operacional, é decisão do cliente. O sistema está preparado para existir perpetuamente.

#### **Desempenho (Performance)**
9. Os módulos Gestão de Armazéns e Logística têm um tempo de resposta quase instantâneo.
10. A SPA tem um tempo de resposta bastante reduzido também, e a mudança entre componentes é também instantânea.
11. A SPA tem uma performance mais baixa no que toca à visualização 3D pois o carregamento é bastante pesado comparado às outras componentes pois aplica Three.js

#### **Suportabilidade**
12. Neste momento a aplicação é apenas suportada por browser no computador

--------------------

### **Design Constraints**
1. O sistema deve ser composto por uma aplicação web do tipo **Single Page Application** (SPA) que permite aos utilizadores autorizados acederem aos diferentes módulos da aplicação, bem como por um conjunto de serviços que implementem as componentes de regras de negócio necessárias para o funcionamento da aplicação web.

### **Implementation constraints**
1. Todos os módulos devem fazer parte do código fonte da mesma SPA e serem disponibilizados como um único artefacto.

### **Interface constraints**
1.   A SPA deve permitir acesso a todos os módulos do sistema: gestão de armazéns, logística, planeamento e visualização bem como RGPD.
2.   O módulo de Planeamento deve consumir dados dos camiões através da API de Logística
4.   O módulo de Visualização deve consumir dados dos armazéns através da API de Gestão de Armazéns
4.   O módulo de Visualização deve consumir dados dos camiões através da API de Gestão de Armazéns
5.   O módulo de Visualização deve consumir dados das rotas através da API de Logística

### **Physical constraints**
1.  Existem duas bases de dados, uma para Gestão de Armazéns e uma para Logística, ambas alojadas em servidores do DEI
2.  A API Gestáo de Armazéns utiliza [Heroku](https://www.heroku.com/)
3.  A API Logística utiliza [Railway](https://railway.app/)
4.  A SPA utiliza [Vercel](https://vercel.com/)

------------------

### **Principais Funcionalidades**

De um modo geral, as principais funcionalidades de cada módulo são as seguintes:

- **Gestão de Armazéns** – permite a gestão da informação relacionada com os armazéns (armazéns e camiões)
- **UI** – interface com o utilizador.
- **Planeamento** – com base nos percursos existentes planear as rotas mais efecientes tendo em conta diferentes parâmetros e/ou heurísticas.
- **Rede Viária** –  permite a visualização 3D da rede viária, a navegação pela cena e a consulta gráfica de informação sobre os armazéns. Consome a informação gerida no módulo gestão de armazéns.
- **Clientes + RGPD** – gestão de informação dos utilizadores finais “clientes” e seus consentimentos no âmbito do RGPD.

-------------------

## Solution Background

### **Architectural Approaches**

Baseado nos requisitos não funcionais e restrições de design, serão adotadas as seguintes abordagens/padrões/estilos:

- Client-Server;
- Web Application, em que o frontend é desempenhado por uma SPA (Single Page Application), e que o backend é desempenhado pelos módulos Gestão de Armazéns, Logística e Planeamento;
- SOA, porque os servidores (cf. anterior) deverão disponibilizar APIs, e particularmente APIs para serem usadas na web, disponibilizando serviços para os clientes respetivos. Serão adotados os nível 0, 1 e 2 do [Modelo de Maturidade de Richardson](https://martinfowler.com/articles/richardsonMaturityModel.html) aplicado a REST;
- Layered architecture, mais especificamente Onion Architecture, por razões académicas.
- Component-based-architecture, usada na SPA.

Outras abordagens/estilos/padrões, como por exemplo a interligação entre aplicações baseado em mensagens-eventos foram desconsideradas para não violar os requisitos e restrições definidos, mas também por questões académicas.

### **Analysis Results**
Não existem por agora resultados de análise ou avaliação. Estudos qualitativos acerca dos estilos/padrões adotados (nomeadamente Onion na Gestão de Armazéns ou Logística, mas também Dependency Injection na UI), permitem empiricamente advogar que a manutenibilidade, evolutabilidade e testabilidade do software são elevadas, ao mesmo tempo que permitem atingir as funcionalidades desejadas.

----------------

# Glossary and Acronyms

* **DDD** - Domain Driver Design
* **DTO** - Data Transfer Object
* **API** - Application Programming Interface
* **SPA** - Single Page Application

-------------

## References

* [React Js](https://reactjs.org/)
* [React Color Picker](https://casesandberg.github.io/react-color/) 
* [Handlebars](https://handlebarsjs.com/)
* [Nodemailer](https://nodemailer.com/about/)
* [Ant Design: React Library](https://ant.design/)
* [React Router](https://reactrouter.com/)
* [MapboxGL Js](https://docs.mapbox.com/mapbox-gl-js/api/)
* [Three.js](https://threejs.org/)
* [Sketchfab: 3D Models](https://sketchfab.com/feed)
* [npx create-react-app](https://github.com/facebook/create-react-app)
* [Mongoose](https://www.npmjs.com/package/mongoose)
* [MongoDB](https://www.mongodb.com/)
* [Express](https://www.npmjs.com/package/express)
* [JSON Web Token](https://www.npmjs.com/package/jsonwebtoken)
* [JOI: Data Validator](https://www.npmjs.com/package/joi)
* [Docker](https://www.docker.com/)
* [Heroku](https://www.heroku.com/)
* [PM2: Production Manager](https://pm2.keymetrics.io/)
* [Threebox](https://github.com/peterqliu/threebox)
* [Cypress](https://www.cypress.io/)
* [Jest](https://jestjs.io/)
* [Microsoft Azure](https://azure.microsoft.com/pt-pt/)
* [XML-JSON](https://www.npmjs.com/package/xml-js)
* [Axios](https://www.npmjs.com/package/axios)
