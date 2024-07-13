![image](https://github.com/user-attachments/assets/0e1110a5-c886-4e82-8c09-2ee497f8a422)

# Hi there, I'm Marcos! 👋

I enjoy switching between sysadmin and dev.

'''
package main

import "fmt"

type Bio struct {
	Name          string
	Role          string
	Technologies  []string
	Programming   []string
	Frameworks    []string
	OS            string
	Database      string
	Cloud         string
	Automation    []string
}

func main() {
	bio := Bio{
		Name:         "Marcos",
		Role:         "DevOps Engineer",
		Technologies: []string{"Containers", "Kubernetes", "Serverless"},
		Programming:  []string{"C#", "Golang"},
		Frameworks:   []string{"ASP.NET Core"},
		OS:           "Linux (Fedora ftw!)",
		Database:     "Postgres",
		Cloud:        "Azure",
		Automation:   []string{"Ansible", "Packer", "Terraform"},
	}

	fmt.Printf("%+v\n", bio)
}
'''