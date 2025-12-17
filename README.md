# EcoGem-BE

## 🛠️ Tech Stack
| Category | Technology |
|---------|------------|
| Language | Java 21 |
| Framework | Spring Boot 3.4.5 |
| Build Tool | Gradle |
| ORM | Spring Data JPA |
| Database | MySQL |
| Security | Spring Security, JWT |
| Others | Lombok, Validation  |

<br>

## 📁 Folder Structure
```
src
└─ main
   ├─ java/com/ecogem/backend
   │ ├─ BackendApplication.java
   │ │
   │ ├─ auth/                
   │ ├─ company/            
   │ ├─ store/                
   │ ├─ contract/             
   │ ├─ collectionrecord/     
   │ ├─ post/                
   │ ├─ mypage/           
   │ ├─ reports/             
   │ └─ config/
   │
   └─ resources
      └─ application.yml                       
```

**Domain Package Structure**
```
<domain>
├─ controller
├─ service
├─ repository
├─ domain
└─ dto
```
