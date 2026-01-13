# Análise, Modelagem e Estrutura de Dados 📊

Este repositório reúne projetos de documentação técnica desenvolvidos durante o curso de **Desenvolvimento de Sistemas na ETEC** nas agendas 11,14 e 15. O objetivo é demonstrar minha capacidade de traduzir regras de negócio em modelos lógicos e estruturais.

## 1. Modelagem de Dados (DER) - Gestão Acadêmica
Este modelo foca na integridade referencial entre alunos, orientadores e disciplinas.
(Diagrama_sistema_academico.png)
- **Destaque:** Implementação de tabela associativa (`cursa`) para resolver relacionamentos N:N.
- **Conceitos:** Uso de Chaves Primárias (PK) e Chaves Estrangeiras (FK).
- **Entidades:** Aluno, Disciplina, Orientador e Departamento.

## 2. Modelagem de Dados (DER) - Gestão de Projetos
Mapeamento de estrutura organizacional de uma empresa.
(Diagrama_gestão_projetos.png)
- **Relacionamentos:** Identificação de hierarquias (Gerente) e alocação de recursos (Peças/Projetos).
- **Cardinalidades:** Definição precisa de relações 1:1 e 1:N conforme requisitos de negócio.

## 3. Diagrama de Caso de Uso (UML) - Matrícula Online
Representação das interações entre usuários e o sistema.
<img width="740" height="765" alt="Diagrama_matricula_online" src="https://github.com/user-attachments/assets/d8ccf1e1-c8db-49b8-8673-f5a158765343" />
- **Atores:** Aluno, Professor e Secretaria.
- **Especialização:** Uso de Generalização para tratar atributos comuns entre atores ("Pessoas").

## Autor:
Daniel Leal dos Santos

🔗Versão hospedada no GitHub Pages
