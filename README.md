```mermaid
sequenceDiagram
    actor Usuario
    participant Sistema

    Usuario->>Sistema: Hace clic en "Probar"
    activate Sistema
    Sistema-->>Usuario: ¡Diagrama funcionando correctamente!
    deactivate Sistema
