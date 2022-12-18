```mermaid

erDiagram
  User ||--o{ ActiveStorage_Attachment : "1対多"
  Post ||--o{ ActiveStorage_Attachment: "1対多"
  ActiveStorage_Blob ||--o{ ActiveStorage_Attachment: "1対多"

```
