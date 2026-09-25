# Changelog

Todas as mudanças notáveis deste projeto serão documentadas neste arquivo.

O formato é baseado em [Keep a Changelog](https://keepachangelog.com/pt-BR/1.0.0/),
e este projeto adere ao [Versionamento Semântico](https://semver.org/lang/pt-BR/).

## [1.1.0] - 2026-09-25

### Adicionado
- **Camada Transversal — Biologia Base (Módulo 01)**:
  - Conclusão da sequência didática com a produção dos 4 infográficos finais (`A01.7` a `A01.10`), totalizando 10 peças no Módulo 01:
    - `A01.7`: ATP e Energia Celular
    - `A01.8`: Proteínas como Máquinas Celulares
    - `A01.9`: Homeostase Celular
    - `A01.10`: Da Célula ao Neurônio
- **Identidade Visual**:
  - Adicionada imagem institucional de capa: `assets/branding/neural-nexus-readme-hero.png` (16:9, *"Da escala molecular ao comportamento"*).
- **Licenciamento**:
  - Formalizada a licença oficial **Creative Commons Atribuição-CompartilhaIgual 4.0 Internacional (CC BY-SA 4.0)** para todo o acervo educacional.
- **Documentação Curricular e Governança**:
  - Inclusão do documento `docs/curriculum/Mapa_Curricular_Mestre_Fundamentos_de_Neurociencias_v2.0.docx` (versão 2.0 com governança curricular expandida e arquétipos visuais da Série A e Série B).
  - Identificação padronizada da versão histórica como `docs/curriculum/Mapa_Curricular_Mestre_Fundamentos_de_Neurociencias_v1.0.docx`.
- **Catálogo e Metadados**:
  - `data/catalog.json`: Atualizado para versão `1.1.0` com 30 infográficos auditados e status `"produzido"` em toda a sequência didática `A01.1`–`A01.10`.
- **Versionamento Remoto e Baseline**:
  - Publicação e consolidação da baseline no repositório GitHub oficial ([`https://github.com/enps2015/neural_nexus`](https://github.com/enps2015/neural_nexus)).

## [1.0.0] - 2026-09-24

### Adicionado
- **Camada Transversal — Biologia Base (Módulo 01 — Biologia Celular para Neurociência)**:
  - 6 infográficos preparatórios de nivelamento (`A01.1` a `A01.6` de uma sequência planejada até `A01.10`), localizados em `content/infographics/biology-base/module-01/`.
    - `A01.1`: A Célula Animal como Sistema
    - `A01.2`: A Membrana Plasmática
    - `A01.3`: Organelas Essenciais para o Neurônio
    - `A01.4`: Transporte pela Membrana
    - `A01.5`: Gradiente de Concentração
    - `A01.6`: Íons e Carga Elétrica
- **Série B (NeuroAtlas / Zoom — Módulo 01)**:
  - 20 pranchas anatômicas e moleculares em alta resolução (`B01.1` a `B01.20`), localizadas em `content/infographics/series-b/module-01/`.
- **Série A (Conceitos Essenciais)**:
  - Diretório `content/infographics/series-a/` reservado para os infográficos oficiais `A01` a `A20` conforme matriz curricular.
- **Normalização Editorial e Governança**:
  - Formalizada a **Regra Editorial de Numeração**: `A01`–`A20` pertencem à Série A principal; `B01`–`B20` pertencem à Série B; `A01.1`–`A01.10` pertencem à sequência didática complementar da Camada Biologia Base (Módulo 01).
  - Atualização do `docs/curriculum/Mapa_Curricular_Mestre_Fundamentos_de_Neurociencias.docx` com a seção da Camada Biologia Base e sequência `A01.1`–`A01.10`.
  - Atualização do `docs/editorial/Blueprint_Modulo_01_Biologia_Celular_para_Neurociencia.docx`.
  - `docs/editorial/NEURAL_NEXUS_Visual_Identity_System_v1.0.docx` e `docs/editorial/NEURAL_NEXUS_Core_Template_Serie_B_v1.0.docx`.
- **Catálogo de Dados**:
  - `data/catalog.json`: Catálogo estruturado dos 26 infográficos com separação semântica entre `biology-base` e `series-b`.
- **Infraestrutura**:
  - Arquitetura de repositório padronizada em `assets/`, `content/infographics/`, `docs/`, `data/` e `site/`.
  - Preparação para futura implantação via GitHub Pages.
