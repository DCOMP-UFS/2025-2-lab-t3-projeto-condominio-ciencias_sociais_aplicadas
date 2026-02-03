# 🏢 Proposta de Condomínio de Laboratórios Multiusuários - CCSA (UFS)

Este repositório contém a proposta oficial para a implantação da infraestrutura tecnológica do Condomínio de Laboratórios do **Centro de Ciências Sociais Aplicadas (CCSA)**, submetida ao **Edital Nº 01/2026**.

* **Site do condomínio:** [Link](http://18.208.234.155:8080/)


---

## 👥 1. Equipe do Projeto
* **Coordenador do Projeto:** Tasso Marcel de Oliveira
* **Assistente de Atas:** Bricio Thyers de Gois Macedo
* **Contador/Tesoureiro:** Lais Santos de Souza
* **Membros Participantes:**
    1. Tasso Marcel de Oliveira - Lab. Ciência da Informação
    2. Gabriella Nascimento dos Santos da Silva - Lab. Direito
    3. Lais Santos de Sousa - Lab. Turismo
    4. Rivaldo José Nascimento dos Santos - Lab. de Ciência Política
    5. Brício Thyers de Gois Macedo
    ...

---

## 🔬 2. Laboratórios Integrados e Sites (AWS EC2)
Cada laboratório mantém uma instância Docker na AWS para gestão institucional. 

| Laboratório | Técnico Responsável | Link do Site (AWS) | Repositório Individual |
| :--- | :--- | :--- | :--- |
| **Ciência da Informação** | Tasso Marcel | [http://3.223.134.38](http://3.223.134.38) | [Link do Github](https://github.com/DCOMP-UFS/2025-2-lab-t3-projeto-lab-site-tasso121) |
| **Ciência Política** | Rivaldo José | [http://52.44.133.112](http://52.44.133.112) | [Link do Github](https://github.com/DCOMP-UFS/2025-2-lab-t3-projeto-lab-site-RivaldoJose) |
| **Direito** | Gabriella Nascimento | [http://3.210.24.245](http://3.210.24.245/) | [Link do Github](https://github.com/DCOMP-UFS/2025-2-lab-t3-projeto-lab-site-GabriellaNascimento) |
| **Turismo** | Lais Santos | [http://18.208.234.155](http://18.208.234.155/) | [Link do Github](https://github.com/DCOMP-UFS/2025-2-lab-t3-projeto-lab-site-laissantos04) |
| **Sociologia** | Brício Thyers | [http://3.221.47.50](http://3.221.47.50/) | [Link do Github](https://github.com/Bricioth/site-grupo-socitec) |

---

## 🛠️ 3. Descrição Técnica da Infraestrutura
O condomínio opera sob uma topologia de rede em estrela, conectada a um **Switch Central Camada 3** e protegida por um **Firewall Next-Gen**.

### Laboratório de Ciência da Informação 
* **Foco:** Curadoria digital e preservação de dados científicos.
* **Infraestrutura Local:** 1 Servidor Rack (Docker Host), 1 Switch Gerenciável 48 portas (D-Link DGS-1210-52) e 6 Estações de Trabalho.
* **Diferencial:** Implementação de VLAN isolada para tráfego seguro de grandes volumes de dados.

### Centro de Estudos sobre a União Europeia (CEURO/UFS)
* **Foco:** Pesquisa interdisciplinar em integração europeia, políticas públicas, relações internacionais e governança democrática.
* **Infraestrutura Local:** 7 Estações de Trabalho conectadas a um Switch de Acesso (Camada 2), com cabeamento estruturado Categoria 6 e nobreaks para proteção elétrica dos equipamentos.
* **Diferencial:** Integração entre infraestrutura local segmentada por VLAN e ambiente em nuvem (AWS EC2), permitindo a publicação de conteúdo acadêmico institucional por meio de containers Docker com servidor Apache.

### Laboratório de Estudos Interdisciplinares em Turismo Criativo
* **Foco:** Produção de pesquisas interdisciplinares voltadas ao turismo criativo e científico.
* **Infraestrutura Local:** 6 Estações de Trabalho conectadas a um Switch de Acesso (Camada 2), com proteção via Firewall dedicado e um Access Point de última geração.
* **Diferencial:** Conectividade de alta performance preparada para suportar diversas metodologias de recolha e análise de dados digitais.

### Laboratorio SOCITEC
* **Foco:** Pesquisas em sistemas de informacao, tecnologias digitais, automacao de processos e suporte computacional a atividades academicas e organizacionais.
* **Infraestrutura Local:** 1 Switch de Acesso (Camada 2), 3 Roteadores WiFi configurados como Access Points e 6 Estacoes de Trabalho distribuidas em diferentes salas.
* **Diferencial:** Segmentacao da rede em multiplas sub-redes IPv4 e IPv6, utilizando gateway e host de internet compartilhados no ambiente do condominio de pesquisa, com topologia simulada no CORE para fins de estudo, planejamento e validacao da infraestrutura.

---

## 💰 4. Orçamento e Atas de Registro de Preços
O orçamento total da proposta respeita o teto global de R$ 1.000.000,00, com cada laboratório mantendo-se dentro do limite de R$ 50.000,00.

* **Planilha Consolidada:** [PDF](orcamento/planilha_orcamento.pdf)
* **Principais Atas Utilizadas:**
    * **Switch L2 (D-Link):** [Ata 04/2026 - DPE/BA](https://pncp.gov.br/app/atas/07778585000114/2025/351/2)
    * **Servidores:** [Ata nº 90012/2025](https://pncp.gov.br/app/atas/33787094000140/2025/418/1)
    * **Desktops:** [Ata nº 001/2026](https://pncp.gov.br/app/atas/45699626000176/2025/570/1)

---

## 🤝 5. Plano de Uso Multiusuário
1. **Acesso:** Os equipamentos estarão disponíveis para todos os grupos de pesquisa do CCSA mediante agendamento prévio.
2. **Prioridade:** O grupo "dono" do laboratório tem prioridade, mas 30% da carga horária de processamento dos servidores é reservada para projetos integrados.
3. **Manutenção:** Custos de manutenção básica e energia serão rateados entre os laboratórios participantes conforme o relatório anual de uso.

---

## 📊 6. Relatório de Colaboração (Google Groups)
A construção desta proposta seguiu o modelo de aprendizagem cooperativa.
* **Total de Mensagens do Grupo:** [19] mensagens.
* **Relatório Detalhado:** [Relatório financeiro](orcamento/relatorio.pdf)
* **Mapas lógicos dos laboratórios:** [Mapas](mapas)
* **Referência da planta utilizada:** [Link da planta](https://www.bambui.ifmg.edu.br/portal/images/PDF/Laborat%C3%B3rios.pdf)
