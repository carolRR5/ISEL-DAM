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
│   ├── QuoteIt
│   └── DAM-TP1
├── TP2/                        # 2º Trabalho Prático
│   ├── CoolWeatherApp
│   ├── CatApp
│   └── DAM-TP2
├── TP3/                        # 3º Trabalho Prático
│   ├── GreetingProcessorProject   
│   ├── CoolJetpackWeatherApp      
│   └── CatApp_MIP3               
│   └── DAM-TP3
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

---

### TP3 — Annotation Processors, MVVM & Jetpack Compose
Desenvolvimento de processadores de anotações Kotlin e evolução para arquitetura multi-módulo com Jetpack Compose.

**GreetingProcessorProject** — Processador de anotações Kotlin:

- Implementação de um processador de anotações personalizado (@Greeting)
- Geração de código em tempo de compilação com KotlinPoet
- Projeto multi-módulo em IntelliJ IDEA (annotations, processor, app)
- Processador RegexProcessor com a anotação @Extract para extração de dados com expressões regulares

**CoolJetpackWeatherApp** — App meteorológica com Jetpack Compose:

- Reconstrução da WeatherApp do TP2 com arquitetura MVVM
- Interface construída inteiramente em Jetpack Compose
- Layouts portrait e landscape adaptativos
- Integração com a API Open-Meteo via Ktor
- Suporte multilingue (PT/EN)

**CatApp MIP-3** — Evolução da CatApp para arquitetura multi-módulo (MIP-3):

- Refatorização de arquitetura monolítica para três módulos independentes (:core, :app-xml, :app-compose)
- Módulo :core partilhado com modelos, cliente Retrofit, repositório e gestão de favoritos
- Módulo :app-xml com interface XML refatorizada a consumir o :core
- Módulo :app-compose com interface em Jetpack Compose e Material Design 3
- Funcionalidade exclusiva do Compose: animação AnimatedVisibility na barra de favoritos
- Desenvolvida com AI-Assisted Development usando AntiGravity

## Tech Stack

- **Language:** Kotlin
- **IDE:** IntelliJ IDEA 2025.3.3 e Android Studio Panda
- **UI:** XML Views e Jetpack Compose
- **Architecture**: MVVM, Multi-Module Android Projects
- **Networking**: Retrofit, Ktor
- **AI-Assisted Development**: AntiGravity IDE
- **Version Control:** Git & GitHub
