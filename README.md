 </pre>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<h2>lanzoni@root:~$ go run whoami.go</h2>

```go
package main

import (
	"fmt"
	"strings"
)

type Developer struct {
	Name      string
	Role      string
	Languages []string
	Focus     []string
}

func main() {
	profile := Developer{
		Name:      "Henrique Lanzoni",
		Role:      "FullStack Software Engineer | Security Enthusiast",
		Languages: []string{"pt_BR", "id_ID"},
		Focus: []string{
			"Machine Learning",
			"WebScraping",
			"Offensive Security",
		},
	}

	fmt.Printf(
		"Name: %s\nRole: %s\nLanguages: %s\nFocus: %s\n",
		profile.Name,
		profile.Role,
		strings.Join(profile.Languages, ", "),
		strings.Join(profile.Focus, ", "),
	)
}
```

<div align="center">
 
![Golang](https://img.shields.io/badge/golang-000000?style=for-the-badge&logo=go&logoColor=00ADD8)
![Python](https://img.shields.io/badge/python-000000?style=for-the-badge&logo=python&logoColor=FFFFFF)
![JavaScript](https://img.shields.io/badge/javascript-000000?style=for-the-badge&logo=javascript&logoColor=FFFFFF)
![TypeScript](https://img.shields.io/badge/typescript-000000?style=for-the-badge&logo=typescript&logoColor=FFFFFF)
![Bash](https://img.shields.io/badge/bash-000000?style=for-the-badge&logo=gnu-bash&logoColor=FFFFFF)
![HTML5](https://img.shields.io/badge/html5-000000?style=for-the-badge&logo=html5&logoColor=FFFFFF)
![CSS3](https://img.shields.io/badge/css3-000000?style=for-the-badge&logo=css3&logoColor=FFFFFF)
![Cloudflare](https://img.shields.io/badge/cloudflare-000000?style=for-the-badge&logo=cloudflare&logoColor=FFFFFF)
![Postgres](https://img.shields.io/badge/postgres-000000?style=for-the-badge&logo=postgresql&logoColor=FFFFFF)
![Figma](https://img.shields.io/badge/figma-000000?style=for-the-badge&logo=figma&logoColor=FFFFFF)
![Selenium](https://img.shields.io/badge/selenium-000000?style=for-the-badge&logo=selenium&logoColor=FFFFFF)
![Playwright](https://img.shields.io/badge/playwright-000000?style=for-the-badge&logo=playwright&logoColor=FFFFFF)
![Docker](https://img.shields.io/badge/docker-000000?style=for-the-badge&logo=docker&logoColor=FFFFFF)

</div>

<div align="center">

> AI Developer focused on security, system design, and automation.
> Building platforms, tools, and experiments around modern web systems and emerging attack surfaces.

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=henriqqw&style=flat-square&color=red)

</div>
