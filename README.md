  <head>
  <h1 align="center">Resume</h1>
  </head>
  <h3 align="center"><b>About Me</b></h3>

```kotlin
package com.linadam.resume

data class aboutMe (
    val myName: String, val summary: String,
    val codingSkills: List<String>,
    val otherSkills: List<String>,
    val hobbit: List<String>
    val contact: Contact
)

data class Contact(
    val email: String,
    val phone: String,
    val github: String
)

fun main() {
    val linAdam = aboutMe(
        myName = "Lin Adam",
        summary = "Android Developer | UI Design",
        codingSkills = listOf(
            "Python", "Chip Firmware Development (C++ and mircoPython)",
            " Robotic Control", "Android APP Development by kotlin (main) and Java",
            "Git", "REST API", "SQLite"
        ),
        otherSkills = listOf("SolidWorks","Illustrator", "Figma"),
        contact = Contact(
            email = "play.art0626@gmail.com",
            phone = "+886-966-225-065",
            github = "https://github.com/AdamLin0626"
        )
    )

    println("Hello, I'm ${linAdam.myName}, a ${linAdam.summary}!")
    println("my Skills: ${linAdam.codingSkills} \n ${linAdam.otherSkills}")
    println("Contact me at: ${linAdam.contact.email}")
}

```

<h3 align="center"><b>My Works</b></h3>
<ul>
  <li>🏫 Ｍy undergraduate senior project : <a href="https://github.com/AdamLin0626/DrinksMachine">DrinksMachine</a></li>
  <li>🏫 Ｍy undergraduate senior project : <a href="https://www.figma.com/proto/N0rd8NPKUsGxLt0mOzK0fA/UiDesign?node-id=0-1&t=HegnYL8HeKF5VgJA-1">DrinksMachine: PC Software UI</a></li>
  <li>☁️ Tring create a ApiToolsApp ： <a href="https://github.com/AdamLin0626/ApiToolBox.git">ApiTools</a></li>
  <li>☁️ Tring create a GameLobby ： <a href="https://github.com/AdamLin0626/SimpleGame.git">SimpleGame</a></li>
</ul>

---
<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=AdamLin0626&show_icons=true&theme=dark&title_color=ff0000&text_color=ffffff&bg_color=000000&hide_border=true&locale=en&layout=compact" alt="AdamLin0626" /></p>

<!-- <p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=AdamLin0626&show_icons=true&theme=highcontrast&title_color=ff0000&text_color=ffffff&hide_border=true&locale=en" alt="AdamLin0626" /></p> -->

