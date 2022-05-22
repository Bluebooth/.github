# Bluetooth Game devs

<h2 align="center">About us</h2>

```golang
package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
		"- ⚡ Quick bio:": "We are a group of Devs and Designers making games for fun and learning cause we love to learn and game ;)",
		"- 🔭 we're currently working on": "Make our first game and show the world our skills",
		"- 🌱 We're currently using": "We use game engines like unity and unreal ( soon to use unreal , unity for now ) and languages like C# , C++ and JS ",
		"- 👯 We're looking for -": "New Designers and Developers ready to join us ( P.S - age isnt a boundry its just a number ) anyone can join us",
		"- 🤔 Origin country ?":"We belong to INDIA ",
		"- 💬 Ask us about": "Any tech queries or help in basic projects or how to join us ",
		"- 📫 How to reach us:": "by mailing on blueboothinfo@gmail.com",
	}
}
```







---
