<p align="center">
  <a href="https://github.com/vegitobluefan/vegitobluefan/blob/main/Аринов Данияр Резюме.pdf" target="_blank">
    <img src="https://img.shields.io/badge/▶️%20go%20run-vegito%2Fmain.go-brightgreen?style=for-the-badge&logo=go&logoColor=white" alt="go run vegitobluefan.go" />
  </a>
</p>

```go
package main

import (
	"fmt"
)

type Developer struct {
	Name        string
	Role        string
	Languages   []string
	TechStack   []string
	Projects    []string
	Contact     map[string]string
	IsOpenToJob bool
}

func main() {
	me := Developer{
		Name:  "Аринов Данияр",
		Role:  "Backend Developer (Golang + Python)",
		Languages: []string{
			"Go", "Python", "SQL", "JavaScript", "Ruby",
		},
		TechStack: []string{
			"gRPC", "PostgreSQL", "Redis", "Kubernetes",
			"Docker", "Kafka", "Prometheus", "Grafana", "GitLab CI/CD",
		},
		Projects: []string{
			"Foodgram", "StableDiffusionML", "OrdersManagementSystem",
			"TaskFlow", "ReferralSystem_API", "Doggygram",
		},
		Contact: map[string]string{
			"Email":    "daniararinov995@gmail.com",
			"Telegram": "@darinovyo",
			"GitHub":   "https://github.com/vegitobluefan",
		},
		IsOpenToJob: true,
	}

	fmt.Println("👋 Привет! Я", me.Name)
	fmt.Println("🔧 Специализация:", me.Role)
	fmt.Println("💡 Технологии:", me.TechStack)
	fmt.Println("📂 Мои проекты:", me.Projects)
	fmt.Println("📫 Контакты:")
	for key, value := range me.Contact {
		fmt.Printf(" - %s: %s\n", key, value)
	}

	panic("need coffee ☕️")
}
```
### 🚀 Стек технологий

![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat&logo=go)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python)
![gRPC](https://img.shields.io/badge/-gRPC-00c7b7?style=flat&logo=grpc)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat&logo=redis)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat&logo=postgresql)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat&logo=kubernetes)
![GitLab CI](https://img.shields.io/badge/-GitLab%20CI-FCA121?style=flat&logo=gitlab)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat&logo=prometheus)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat&logo=grafana)

---

### 🛠 Некоторые из моих проектов

- 🍽️ [Foodgram](https://github.com/vegitobluefan/Foodgram_project.git) — сервис для обмена рецептами, Docker + CI/CD
- 🎨 [StableDiffusionML](https://github.com/vegitobluefan/StableDiffusionML) — генерация изображений на FastAPI + Celery
- 🔗 [Referral System API](https://github.com/vegitobluefan/ReferralSystem_API.git) — Django-сервис с инвайтами и трекингом
- 🛎️ [Orders Management System](https://github.com/vegitobluefan/OrdersManagementSystem.git) — распределённая система на Go + gRPC
- ⏱️ [TaskFlow](https://github.com/vegitobluefan/TaskFlow.git) — HTTP-сервис отложенного выполнения задач

