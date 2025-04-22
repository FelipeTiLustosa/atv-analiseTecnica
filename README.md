## Descrição da Atividade

A empresa fictícia **PayFlex**, especializada em carteiras digitais e pagamento por aproximação (NFC), sofreu um ataque cibernético que:

1. **Paralisou as operações por 36 horas.**  
2. **Iniciou-se com um e‑mail forjado (spoofing)** enviado a um colaborador do setor financeiro, contendo um **link encurtado (bit.ly)**.  
3. **Redirecionamento a um site falso** idêntico à intranet da empresa, onde o colaborador inseriu suas credenciais.  
4. **Instalação de script JavaScript ofuscado**, criando um backdoor e capturando o login em menos de 15 minutos.  
5. **Movimentação lateral** para o sistema de RH e **injeção de vírus modular** no banco de dados, com módulos de:
   - Exfiltração de dados (nomes, CPFs, cartões)  
   - Sabotagem de backups  
   - Comunicação reversa com servidor C2  
6. **DDoS massivo** no site principal como distração para a equipe de TI, enquanto os dados eram extraídos silenciosamente.

### Entregáveis

- **Relatório técnico (PDF, Arial 11)** para equipe júnior de TI, contendo:
  - Etapas detalhadas do ataque  
  - Vulnerabilidades exploradas e mecanismos de ocultação (layout, spoofing, link camuflado)  
  - Linguagens e scripts prováveis (JavaScript, Node.js, Python)  
  - Ferramentas dos invasores (LOIC/HOIC, botnets, scripts C2 personalizados)  
  - Medidas de prevenção (anti‑phishing, autenticação forte, monitoramento de rede)  
- **Diagrama/fluxograma** ilustrando a cadeia de ataque  
- **Referências** (sites confiáveis, artigos e livros)
