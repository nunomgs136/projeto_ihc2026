# Entrega 1 — Conhecendo o problema

**Data:** 13/08/2026  
**Status:** 🟨 iniciada  
**Responsabilidade:** 1 solução consolidada por equipe

## Objetivo da atividade

Delimitar o produto, os usuários, os benefícios, as funcionalidades e o **contexto de uso** antes de iniciar decisões de interface. Esta entrega funciona como contrato de escopo para as demais.

## 1.1 Membros da equipe

| Nome completo | Matrícula | GitHub |
|---|---:|---|
| Beatriz Manaia Lourenço Berto |22.125.060-8 | [Beatriz manaia Lourenço Berto](https://github.com/beatrizmanaia26)|
| Beatriz Manaia Lourenço Berto |24.123.006-9| [Luana Bortko Rodrigues](https://github.com/LuaBortko) |
| Nuno Martins Guilhermino da Silva |22.126.099-5|  [Nuno Martins Guilhermino da Silva ](https://github.com/nunomgs136) |

## 1.2 Título original do TCC/projeto

Estrutura e formatação das provas o ENEM: Impacto no desempenho geral dos participantes

## 1.3 Orientador(a)

Charles Henrique Porto Ferreira

## 1.4 Está previsto desenvolver interface?

- [X] Sim
- [ ] Não

**Justificativa:** 

As interfaces do nosso TCC estão relacionadas com a possibilidade de fornecer subsídios para que professores e elaboradores de provas avaliem características estruturais de suas avaliações, contribuindo para ajustes que tornem o nível de dificuldade mais adequado aos objetivos propostos.

## 1.5 Objetivo do trabalho

Descreva o **resultado que o projeto pretende alcançar**, não apenas a tecnologia a utilizar.

A partir do upload de uma prova, o sistema analisa suas características estruturais e, utilizando as correlações observadas no ENEM, estima seu nível potencial de dificuldade ao oferecer visualização de informações como: uso de elementos visuais, nível de formalidade, construção de distratores, ordem de apresentação das questões e tempo médio de leitura da prova e das questões.

## 1.6 Produto final

O que será efetivamente entregue? Aplicação Web.

## 1.7 Usuário final

Quem interage diretamente com o produto? Docentes.

## 1.8 Benefícios para o usuário

| Benefício esperado | Problema/necessidade associada | Para qual usuário |
|---|---|---|
| Avaliar se características específicas da prova poderiam impactar o desempenho dos alunos
 | A possibilidade de o formato da prova impactar no desempenho dos estudantes | docentes |

## 1.9 Funcionalidades — visão do usuário

Escreva funcionalidades como capacidades observáveis pelo usuário, não como detalhes de backend.

| ID | Funcionalidade | Objetivo do usuário atendido | Prioridade inicial |
|---|---|---|---|
| F01 | upload de prova múltipla escolha em pdf | ter um material para a análise | alta |
| F02 | inserção de dados da prova para análise | sistema conhecer os parâmetros da prova | alta |
| F03 | métricas extraídas a partir da prova(visualização gráfica, indicadores quantitativos, análise de correlação entre variáveis estruturais e desempenho) | avaliar o possível impacto do formato da prova no desempenho dos alunos | alta |


## 1.10 Tecnologias e ferramentas previstas

| Camada/uso | Tecnologia/ferramenta | Por que foi escolhida | Impacto potencial na interação |
|---|---|---|---|
| uso | python | análise de dados | {{ex.: limitações de dispositivo, latência, sensores}} |
| uso | Vue | desenvolvimento da aplicação web | {{ex.: limitações de dispositivo, latência, sensores}} |

## 1.11 Contexto de uso

Uma docente, ao elaborar uma prova para seus estudantes, deseja garnatir que está os avaliando com base nos conhecimentos obtidos nas aulas, por isso, utiliza nosso sistema para identificar o impacto do formato de sua prova no desempenho de seus alunos.

### Usuários

Características relevantes para a interação:
O Usuário precisa ter uma prova de múltipla escolha em formato pdf com a formatação igual as provas do enem.
Utilizará o sistema com base nas necessidades de análise das provas elaboradas por ele, seja semestralmente, mensalmente ou qualquer outra periodicidade. 

### Tarefas e objetivos

Quais tarefas importantes ocorrerão e com que frequência/criticidade?

### Equipamentos e plataforma

Dispositivos, tamanho de tela, entrada/saída, conectividade, restrições de hardware/software.
pc.            tamanho padrão de pc.                            

### Ambiente físico ?

Iluminação, ruído, mobilidade, privacidade, possibilidade de uso com uma mão, tempo disponível etc.

### Ambiente social e organizacional

Uso individual/coletivo, presença de terceiros, políticas, papéis, responsabilidades, consequências de erro.

## Delimitação inicial

**Dentro do escopo:** {{...}}  
**Fora do escopo:** {{...}}

## Síntese da entrega

Em 5–10 linhas, explique quais decisões desta entrega orientarão as próximas etapas.

## Checklist

- [ ] O problema está descrito sem confundir problema com solução.
- [ ] Usuário final está identificado de forma específica.
- [ ] Funcionalidades estão na visão do usuário.
- [ ] Benefícios estão ligados a necessidades reais/hipóteses explícitas.
- [ ] Contexto inclui usuários, tarefas, plataforma e ambientes físico/social.
- [ ] Escopo e limites estão claros.
- [ ] A matriz de rastreabilidade foi iniciada.
