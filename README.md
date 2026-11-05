# Motor CC Shunt — Máquinas Elétricas I (UEM)

Projeto acadêmico de construção de um **motor de corrente contínua com excitação em derivação (shunt)**, desenvolvido na disciplina de Máquinas Elétricas I da Universidade Estadual de Maringá (UEM), em 2026.

## Objetivo

Projetar, construir e avaliar um protótipo de motor CC shunt, contemplando controle de velocidade, medição de rotação e inversão do sentido de giro.

## Características previstas

- Potência nominal de referência: **1,5 HP** (meta de projeto; não representa desempenho já comprovado).
- Excitação do campo: **shunt (em derivação)**.
- Sistema magnético: **2 polos**.
- Rotor: **8 ranhuras**.
- Comutador: **8 segmentos**.
- Enrolamento da armadura: **imbricado simplex progressivo**.
- Controle de velocidade: **PWM com temporizador 555**.
- Medição de rotação: **tacômetro digital com display LCD**.
- Reversão do sentido de rotação.

> **Estado do projeto:** documentação em desenvolvimento. Os requisitos e valores previstos ainda precisam ser verificados nos ensaios do protótipo.

## Estrutura do repositório

```text
motor-cc-shunt-uem/
├── README.md
├── .gitignore
├── relatorio/
│   ├── Relatorio_Motor_CC_Shunt_UEM.tex
│   └── imagens/
├── circuitos/
├── codigo/
│   └── tacometro/
├── simulacoes/
└── apresentacao/
```

O relatório utiliza a classe LaTeX `abntex2` e segue a estrutura acadêmica do projeto. Para compilá-lo, use uma distribuição LaTeX que inclua `abntex2` e os pacotes referenciados no arquivo. As imagens de logotipo são opcionais, conforme os caminhos definidos no próprio documento.

## Integrantes

- Antonio Nicolas Irmani
- João Marcos Conti Checom
- Juan Antonio Marques Fogaça de Oliveira
- Henry Barbosa Azevedo

**Orientador:** Prof. Glaucio Pedro de Alcantara  
**Instituição:** Universidade Estadual de Maringá — UEM  
**Disciplina:** Máquinas Elétricas I  
**Ano:** 2026

## Licença

Este repositório não possui uma licença de reutilização definida. A ausência de licença não concede automaticamente permissão para copiar, modificar ou redistribuir o material.
