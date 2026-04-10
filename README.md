# Desenvolvimento de Aplicações Móveis - 2025/2026

Bem-vindo ao repositório da unidade curricular de **Desenvolvimento 
de Aplicações Móveis (DAM)** do curso de LEIM no **Instituto Superior 
de Engenharia de Lisboa (ISEL)**.

- **Estudante:** Carolina Raposo
- **Número:** A51568

---

## Estrutura

```text
ISEL-DAM/
├── TP1/                        # 1º Trabalho Prático
│   ├── HelloWorld
│   ├── SystemInfoApp
│   └── DAM-TP1
├── TP2/                        # 2º Trabalho Prático
│   ├── CoolWeatherApp
│   ├── CatApp
│   └── DAM-TP2
└── README.md
```

## Trabalhos

### TP1 — Hello Kotlin. Hello Android World!
Trabalho introdutório ao desenvolvimento Android e Kotlin.

**DAM-TP1** — Exercícios de Kotlin em IntelliJ IDEA:
- Exercício 1: Arrays de quadrados perfeitos usando diferentes abordagens
- Exercício 2: Calculadora com operações aritméticas, booleanas e bitwise
- Exercício 3: Modelação de ressaltos de uma bola usando generateSequence
- Virtual Library: Sistema de gestão de biblioteca com classes, herança e 
  encapsulamento em Kotlin

**HelloWorld** — Primeira app Android:
- App "Hello World" com TextViews, imagens e CalendarView
- Suporte a landscape layout e ícone personalizado
- Uso de strings.xml para internacionalização

**SystemInfoApp** — App de informação do dispositivo:
- Exibe informações do sistema usando android.os.Build
- Interface com MultiLine Text Widget

---

### TP2 — Weather App & Cat App
Desenvolvimento de aplicações Android com integração de APIs REST.

**DAM-TP2** — Exercícios avançados de Kotlin:
- Event Log Processing com extension functions e higher-order functions
- Type-Safe In-Memory Cache com Generics
- Configurable Data Pipeline com lambdas e function composition
- 2D Vector Library com operator overloading

**CoolWeatherApp** — App meteorológica Android:
- Integração com a API Open-Meteo
- Layouts portrait e landscape para telemóvel e tablet
- Temas dinâmicos Day/Night baseados em sunrise/sunset
- GPS para obter coordenadas reais do dispositivo
- Padrão MVVM com ViewModel e LiveData
- Suporte multilingue (PT/EN)

**CatApp** — App de imagens de gatos (MIP-2):
- Integração com TheCatAPI
- Lista de imagens com RecyclerView
- Ecrã de detalhes de raças
- Sistema de favoritos com FIFO queue (máximo 5)
- Tratamento de erros e modo offline
- Layouts otimizados para tablet
- Desenvolvida com AI-Assisted Development usando AntiGravity

## Tech Stack

- **Language:** Kotlin
- **IDE:** IntelliJ IDEA 2025.3.3 e Android Studio Panda
- **UI:** XML Views
- **Version Control:** Git & GitHub
