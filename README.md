### Hola 👋 soy Ale.

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
		"- ⚡ Decripcion rapida:              "Soy un desarrolador buscando sus primeras experiencias en el mundo IT, aca encontras ejercicios y proyectos que he realizado",
		"- 🌱 Estoy Aprendiendo":            "Actualmente estoy practicando JavaScript y React",
		"- 💬 Preguntame sobre":             "Java, C#, Git, SQL, .NET, SpringBoot, Spring Framework, HTML5, CSS, Web-Dev",
	}
}

<!--
**alemago14/alemago14** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
