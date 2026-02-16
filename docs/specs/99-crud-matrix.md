# CRUDマトリクス

| エンティティ \ ユースケース | UC-001 認証 | UC-002 予約管理 | UC-003 決済 |
|---------------------------|-------------|---------------|------------|
| users | R | R | R |
| records | - | **CRUD** | R |
| record_details | - | **CRUD** | R |
| attachments | - | **CR** | - |
| payments | - | - | **CRU** |

> 900517405 の CRUD マトリクス
- **C** = Create, **R** = Read, **U** = Update, **D** = Delete
