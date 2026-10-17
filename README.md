# Redes sem Fio — Aulas

Material didático da disciplina **Redes sem Fio (RSFI)**
do **Curso Técnico em Redes de Computadores** do **IFSP — Câmpus Boituva**.

- **Professores:** Marcelo Frate · Andre Luyde da Silva Souza · Ricardo Pasquati Pontarolli
- **Contato:** pasquati@ifsp.edu.br
- **Carga horária:** 60 h (60 h em laboratório) — 2 aulas por semana
- **Formato das aulas:** slides em PDF (Beamer) gerados a partir de fontes Quarto/Markdown

---

## Como usar este repositório

As aulas estão na pasta [`aulas/`](aulas/), organizadas em **40 semanas** (`s01` a `s40`). Cada **semana** reúne as **2 aulas** do período num único arquivo.

- Para **estudar**, abra o arquivo **`.pdf`** da semana (ex.: [`aulas/s01.pdf`](aulas/s01.pdf)).
- Cada semana também tem a **fonte editável** `.qmd` (mesmo nome), para quem quiser adaptar o conteúdo.
- As **avaliações** (`.gift`, com gabarito) ficam na pasta `aulas/` junto das aulas e **não** são publicadas.

> Dica: no GitHub, clique no arquivo `.pdf` e depois em **Download** para abrir os slides.

---

## Plano de Ensino

> Baseado no **Plano de Ensino** e no **Plano de Aulas** do PPC do curso (arquivos `BTVRSFI.pdf` e `plano-de-aula.pdf`).

### Identificação

| Campo | Valor |
|---|---|
| Curso | Técnico em Redes de Computadores Integrado ao Ensino Médio |
| Componente curricular | Redes sem Fio |
| Tipo | Obrigatório/Técnica |
| Núcleo | NET |
| Série | 3º |
| Sigla | BTVRSFI |
| Aulas semanais | 2 |
| Total de aulas | 80 |
| Carga horária presencial | 60 h |
| Carga horária em laboratório | 60 h |
| Docentes | Marcelo Frate · Andre Luyde da Silva Souza · Ricardo Pasquati Pontarolli |

### Conhecimentos essenciais do currículo de referência

Redes de Computadores/Redes de Computadores.

### Ementa

O componente curricular conceitua e aplica os protocolos de redes sem fio e dos equipamentos de comunicação de dados. Estuda os sistemas de transmissão sem fio, terminologia, princípios de Radiofrequência e métodos de acesso em redes sem fio.

### Objetivos

- Conhecer as arquiteturas, conceitos, tecnologias e padronizações em redes sem fio;
- Compreender como utilizar ferramentas para redes sem fio;
- Aplicar a execução de um projeto e instalação de uma rede sem fio.

### Conteúdo Programático

- Introdução às redes sem fio;
- Categorias de redes sem fio: WPAN, WLAN, WMAN, WWAN, WLL;
- Tecnologias: Wi-Fi, Infrared, Wimax, Wimesh, Bluetooth, VANETs;
- Evolução das tecnologias da Família IEEE 802.11: 802.11a, 802.11b e 802.11g;
- Conceitos sobre protocolos de segurança: WEP, WPA-WPA2 (PSK e EAP) (personal e enterprise);
- Tipos de antenas de comunicação;
- Projetos de redes sem fio.

### Avaliação

O sistema avaliativo é embasado em **duas atividades avaliativas por bimestre**, postadas no **Moodle** (questões de múltipla escolha e/ou dissertativas), disponíveis por período não superior a 24 horas, além de uma **avaliação bimestral**. A nota final corresponde à **média ponderada** (pesos diferentes) entre todas as atividades. Aprovação: **MF ≥ 6,0** e frequência às aulas (FA) **≥ 75%**.

### Bibliografia Básica

- RAPPAPORT, Theodore S. *Comunicações Sem Fio: Princípios e Práticas*. 2. ed. Pearson Universidades, 2008. ISBN 978-8576051985.
- ROCHOL, Juergen. *Sistemas de Comunicação Sem Fio — Conceitos e Aplicações*. v. 24. Bookman, 2018. ISBN 978-8582604557.
- SILVA, Fernanda Rosa da et al. *Redes Sem Fio*. Grupo A, 2021. ISBN 978-6556901374.

### Bibliografia Complementar

- KUMAR, Ch. Niranjan. *Redes de comunicação sem fio reconfiguráveis*. KS OmniScriptum Publishing, 2022. ISBN 978-6203394689.
- LUGLI, Alexandre Baratella; SANTOS, Max Mauro Dias. *Redes sem fio para automação industrial*. Érica, 2013. ISBN 978-8536504988.
- MORAES, Alexandre Fernandes. *Redes Sem Fio — Instalação, Configuração e Segurança: Fundamentos*. Érica Saraiva, 2010. ISBN 978-8536503158.

---

## Conteúdo por Bimestre

Cronograma com **64 aulas de conteúdo** (16 por bimestre), organizadas em **32 semanas de 2 aulas** cada, e **8 avaliações** (2 por bimestre), em formato **GIFT** para importação no Moodle (10 questões cada).

### 1º Bimestre — Fundamentos das Redes sem Fio

| Semana | Conteúdo | PDF | Fonte (.qmd) |
|---|---|---|---|
| 1 | **Aula 1:** Apresentação da Disciplina · **Aula 2:** Introdução às redes sem fio: histórico e terminologia | [s01](aulas/s01.pdf) | [.qmd](aulas/s01.qmd) |
| 2 | **Aula 3:** Transmissão por Ondas de Rádio · **Aula 4:** Categorias de Redes sem Fio: Visão Geral | [s02](aulas/s02.pdf) | [.qmd](aulas/s02.qmd) |
| 3 | **Aula 5:** WPAN: Redes Pessoais sem Fio · **Aula 6:** WLAN: Redes Locais sem Fio | [s03](aulas/s03.pdf) | [.qmd](aulas/s03.qmd) |
| 4 | **Aula 7:** WMAN e WWAN: Redes Metropolitanas e Amplas · **Aula 8:** WLL: Acesso Local sem Fio | [s04](aulas/s04.pdf) | [.qmd](aulas/s04.qmd) |
| 5 | **Avaliação 1 (GIFT, 10 questões)** | — | `s05-avaliacao-1.gift` |
| 6 | **Aula 9:** Comparativo entre as Categorias · **Aula 10:** Princípios de Radiofrequência (RF) | [s06](aulas/s06.pdf) | [.qmd](aulas/s06.qmd) |
| 7 | **Aula 11:** Propagação de Ondas de Rádio · **Aula 12:** Reflexão, Difração e Espalhamento | [s07](aulas/s07.pdf) | [.qmd](aulas/s07.qmd) |
| 8 | **Aula 13:** Interferência e Ruído · **Aula 14:** Tipos de Antenas: Onidirecionais e Direcionais | [s08](aulas/s08.pdf) | [.qmd](aulas/s08.qmd) |
| 9 | **Aula 15:** Ganho de Sinal e Potência · **Aula 16:** Prática: Identificação de Antenas em Laboratório | [s09](aulas/s09.pdf) | [.qmd](aulas/s09.qmd) |
| 10 | **Avaliação 2 (GIFT, 10 questões)** | — | `s10-avaliacao-2.gift` |

### 2º Bimestre — Acesso ao Meio e Padrões IEEE 802.11

| Semana | Conteúdo | PDF | Fonte (.qmd) |
|---|---|---|---|
| 1 | **Aula 17:** Métodos de Acesso ao Meio: Conceitos · **Aula 18:** CSMA/CA: Acesso em Redes sem Fio | [s11](aulas/s11.pdf) | [.qmd](aulas/s11.qmd) |
| 2 | **Aula 19:** Arquiteturas de Redes Wireless · **Aula 20:** Topologias: Infraestrutura e Ad Hoc | [s12](aulas/s12.pdf) | [.qmd](aulas/s12.qmd) |
| 3 | **Aula 21:** Padrões IEEE 802.11: Visão Geral · **Aula 22:** 802.11 Original: Características | [s13](aulas/s13.pdf) | [.qmd](aulas/s13.qmd) |
| 4 | **Aula 23:** Família 802.11b · **Aula 24:** Família 802.11a | [s14](aulas/s14.pdf) | [.qmd](aulas/s14.qmd) |
| 5 | **Avaliação 1 (GIFT, 10 questões)** | — | `s15-avaliacao-1.gift` |
| 6 | **Aula 25:** Família 802.11g · **Aula 26:** Comparação 802.11a/b/g | [s16](aulas/s16.pdf) | [.qmd](aulas/s16.qmd) |
| 7 | **Aula 27:** Estudo de Caso: Comparação de Tecnologias · **Aula 28:** Padrões Modernos: 802.11n (Wi-Fi 4) | [s17](aulas/s17.pdf) | [.qmd](aulas/s17.qmd) |
| 8 | **Aula 29:** Padrões Modernos: 802.11ac (Wi-Fi 5) · **Aula 30:** Padrões Modernos: 802.11ax (Wi-Fi 6) | [s18](aulas/s18.pdf) | [.qmd](aulas/s18.qmd) |
| 9 | **Aula 31:** Wi-Fi 6E, Wi-Fi 7 e Tendências Futuras · **Aula 32:** Prática de análise de espectro e pesquisa sobre a evolução do Wi-Fi | [s19](aulas/s19.pdf) | [.qmd](aulas/s19.qmd) |
| 10 | **Avaliação 2 (GIFT, 10 questões)** | — | `s20-avaliacao-2.gift` |

### 3º Bimestre — Equipamentos, Segurança e Outras Tecnologias

| Semana | Conteúdo | PDF | Fonte (.qmd) |
|---|---|---|---|
| 1 | **Aula 33:** Configuração de Access Points · **Aula 34:** Wireless Controllers: Conceitos | [s21](aulas/s21.pdf) | [.qmd](aulas/s21.qmd) |
| 2 | **Aula 35:** Prática: Configuração de AP e Controller · **Aula 36:** Segurança em Redes sem Fio: Fundamentos | [s22](aulas/s22.pdf) | [.qmd](aulas/s22.qmd) |
| 3 | **Aula 37:** Fragilidades do WEP · **Aula 38:** Transição do WEP para o WPA | [s23](aulas/s23.pdf) | [.qmd](aulas/s23.qmd) |
| 4 | **Aula 39:** WPA2: Conceitos · **Aula 40:** WPA2 Personal (PSK) | [s24](aulas/s24.pdf) | [.qmd](aulas/s24.qmd) |
| 5 | **Avaliação 1 (GIFT, 10 questões)** | — | `s25-avaliacao-1.gift` |
| 6 | **Aula 41:** WPA2 Enterprise (EAP/802.1X) · **Aula 42:** Servidores RADIUS | [s26](aulas/s26.pdf) | [.qmd](aulas/s26.qmd) |
| 7 | **Aula 43:** WPA3 e Segurança Moderna · **Aula 44:** Prática: Configuração de RADIUS Básico | [s27](aulas/s27.pdf) | [.qmd](aulas/s27.qmd) |
| 8 | **Aula 45:** WPAN: Bluetooth · **Aula 46:** WPAN: Infrared e ZigBee | [s28](aulas/s28.pdf) | [.qmd](aulas/s28.qmd) |
| 9 | **Aula 47:** WMAN e WiMax · **Aula 48:** Redes em Malha (Wimesh/Mesh) | [s29](aulas/s29.pdf) | [.qmd](aulas/s29.qmd) |
| 10 | **Avaliação 2 (GIFT, 10 questões)** | — | `s30-avaliacao-2.gift` |

### 4º Bimestre — Tecnologias Avançadas e Projeto de Redes Sem Fio

| Semana | Conteúdo | PDF | Fonte (.qmd) |
|---|---|---|---|
| 1 | **Aula 49:** VANETs: Redes Veiculares · **Aula 50:** Redes de Sensores sem Fio | [s31](aulas/s31.pdf) | [.qmd](aulas/s31.qmd) |
| 2 | **Aula 51:** IoT e Conectividade sem Fio · **Aula 52:** Projeto de Redes sem Fio: Planejamento | [s32](aulas/s32.pdf) | [.qmd](aulas/s32.qmd) |
| 3 | **Aula 53:** Site Survey e Cobertura · **Aula 54:** Projeto Interdisciplinar com ASRE: Cenários | [s33](aulas/s33.pdf) | [.qmd](aulas/s33.qmd) |
| 4 | **Aula 55:** Projeto Interdisciplinar: Divisão de Grupos · **Aula 56:** Projeto interdisciplinar: desenvolvimento (partes 1 e 2) | [s34](aulas/s34.pdf) | [.qmd](aulas/s34.qmd) |
| 5 | **Avaliação 1 (GIFT, 10 questões)** | — | `s35-avaliacao-1.gift` |
| 6 | **Aula 57:** Projeto Interdisciplinar: Desenvolvimento (3) · **Aula 58:** Projeto Interdisciplinar: 1ª Entrega | [s36](aulas/s36.pdf) | [.qmd](aulas/s36.qmd) |
| 7 | **Aula 59:** Feedback e Correção dos Erros · **Aula 60:** Ajustes e Finalização do Projeto | [s37](aulas/s37.pdf) | [.qmd](aulas/s37.qmd) |
| 8 | **Aula 61:** Preparação das Apresentações · **Aula 62:** Apresentação dos projetos | [s38](aulas/s38.pdf) | [.qmd](aulas/s38.qmd) |
| 9 | **Aula 63:** Recuperação e Reavaliação · **Aula 64:** Encerramento do Ano Letivo | [s39](aulas/s39.pdf) | [.qmd](aulas/s39.qmd) |
| 10 | **Avaliação 2 (GIFT, 10 questões)** | — | `s40-avaliacao-2.gift` |

---


## Estrutura do repositório

```
.
├── README.md            # este arquivo (inclui o cronograma)
└── aulas/
    ├── s01.pdf         # slides da semana (para estudar)
    ├── s01.qmd         # fonte editável (Quarto/Markdown)
    ├── s05-avaliacao-1.gift      # avaliações (não publicadas)
    ├── images/         # ilustrações e diagramas
    └── ...
```

## Observações

- As **fontes** `.qmd` permitem editar o conteúdo e gerar novamente os PDFs com o Quarto.
- As aulas são apresentadas em **PDF (Beamer)** para leitura simples e impressão.
- Dúvidas e sugestões: fale com o professor.

## Licença

Material didático do IFSP. Uso educacional.
