![image](https://github.com/user-attachments/assets/e51c8f5b-6b54-4bba-8463-eb3fcde49e9b)

# Hi there, I'm Marcos! 👋

```go
package main

import "fmt"

type Bio struct {
	Name               string
	Role               string
	Programming        []string
	OperatingSystem    string
	Database           string
	Cloud              string
	Frameworks         []string
	Containerization   string
}

func main() {
	bio := Bio{
		Name:             "Marcos",
		Role:             "DevOps Engineer",
		Programming:      []string{"C#", "Golang"},
		OperatingSystem:  "Linux (Fedora ftw!)",
		Database:         "Postgres",
		Cloud:            "Azure",
		Frameworks:       []string{"ASP.NET Core"},
		Containerization: "Containerization & Orchestration (Kubernetes)",
	}

	fmt.Printf("%+v\n", bio)
}
