### Hi there 👋, my name is André
#### I am a Software Engineer Student
![I am a Software Engineer Student](https://drive.google.com/uc?export=view&id=1uBeUjmroa2auCMlqkSLVIkVf5pNeVzE7)

I know how to Hellow World on:
| [<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/laravel/laravel.png" alt="Laravel" width="24">](https://laravel.com/) | [<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/php/php.png" alt="php" width="38">](https://php.net/)  | [<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/vue/vue.png" alt="Vue" width="24">](https://vuejs.org/)  |  [<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/bootstrap/bootstrap.png" alt="Bootstrap" width="24">](https://getbootstrap.com/) |  [<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png" alt="jQuery" width="24">](https://jquery.com/) | [<img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/jquery/jquery.png" alt="jQuery" width="24">](https://jquery.com/)
|---|---|---|---|---|---|

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
		"- ⚡ Quick bio:":                    "I am a student from Brazil in my last year.  I make projects for fun and for my grades. If you liked some or just want to talk, i would love to have a coffee with you.",
		"- 🌱 I’m currently trying to learn":        "Vue.js",
		"- 👯 I’m looking to collaborate on": "React Native related projects",
		"- 📫 How to reach me:":              "https://github.com/AnhellO#you-can-reach-me-at-alien",
	}
}
