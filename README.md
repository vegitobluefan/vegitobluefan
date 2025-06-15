<p align="center">
  <a href="https://github.com/vegitobluefan/vegitobluefan/blob/main/Аринов_Данияр_Резюме.pdf" target="_blank">
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
