# Proj_FaculdadeSQL
## Integrantes
Rodrigo Simões Ruy R.A. 24.122.092-0


# Relações
---
title: Order example
---
erDiagram
    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    CUSTOMER }|..|{ DELIVERY-ADDRESS : uses
