Eng-Guidelines - MVP de Gestão e Atendimento Comunitário
Este repositório contém o código-fonte do **MVP (Produto Mínimo Viável)** desenvolvido para a gestão simplificada de atendimentos na recepção comunitária, promovendo transparência, acessibilidade e eficiência operacional.
Objetivos e Alinhamento Estratégico
ODS 16 - Paz, Justiça e Instituições Eficazes:** Redução da burocracia e fortalecimento da transparência na gestão de dados dos beneficiários.
Acessibilidade Universal:** Interface e fluxos desenhados para garantir uso intuitivo por atendentes e voluntários com diferentes níveis de letramento digital.
Preservação de Memória:** Diretrizes rígidas de regra de negócio que vedam a exclusão física de cadastros de beneficiários, permitindo apenas edições e inativações lógicas.
Arquitetura do Projeto
O projeto adota os princípios da **Clean Architecture**, garantindo a separação de responsabilidades e desacoplamento de camadas:
```text
Eng-Guidelines/
├── .github/workflows/ci.yml   
├── app/
│   ├── api/v1/endpoints/      
│   ├── core/                  
│   ├── models/                
│   ├── schemas/               
│   ├── services/              
│   └── main.py                
├── tests/                     
├── .gitignore
├── README.md
└── requirements.txt        
