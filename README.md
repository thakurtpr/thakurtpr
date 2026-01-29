### <div align="center">👨‍💻 Thakur Prasad Rout </div>

<div align="center">
  <img src="https://profile-counter.glitch.me/thakurtpr/count.svg" alt="Visitor Count">
</div>

<br/>

```go
package main

import "fmt"

type DevProfile struct {
    Name      string
    Role      string
    Company   string
    Location  string
    Languages []string
    Hobbies   []string
}

func main() {
    me := DevProfile{
        Name:      "Thakur Prasad Rout",
        Role:      "DevOps Engineer",
        Company:   "iServeU",
        Location:  "Odisha, India",
        Languages: []string{"Golang", "Rust", "Bash"},
        Hobbies:   []string{"Dance", "Cloud Native Tech"},
    }
    
    fmt.Printf("Hello! I am %s, working on Kubernetes & Infra.", me.Name)
}
