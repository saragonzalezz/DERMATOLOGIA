```mermaid
graph TD
A[Inicio] --> B{Evaluar tipo de enfermedad}
B --> C[Acné]
B --> D[Rosácea]

C --> E{Evaluar severidad del Acné}
E --> F[Leve: Retinoides tópicos, PB]
E --> G[Moderado: Antibióticos tópicos/orales]
E --> H[Severo: Isotretinoína oral]

D --> I{Determinar tipo de Rosácea}
I --> J[Eritematotelangiectásica: Brimonidina + Protector solar]
I --> K[Papulopustular: Metronidazol o ácido azelaico]
I --> L[Fimatosa: Isotretinoína o cirugía]
I --> M[Ocular: Lubricantes + antibióticos orales]

Z[Consejos generales: Evitar factores desencadenantes] --> A
