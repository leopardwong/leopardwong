### Hi there 👋
Welcome to my GitHub!
I am Leopard, a motivated Software Engineer from Hong Kong and currently living in Toronto, Canada.
## A little more about me...
```kotlin
data class Leopard(
    val name: String = "Leopard Wong",
    val pronouns: String = "He",
    val role: String = "Software Engineer",
    val code: List<String> = listOf("Kotlin", "SWift", "JavaScript", "Java", "Python", "Dart", "HTML"),
    val technologies: Technologies = Technologies(),
    val language: Map<String, String> = mapOf(
        "en_US" to "Professional Working Proficiency",
        "zh_CN" to "Native"
        )
)
data class Technologies(
    val mobileDev: MobileDev = MobileDev(),
    val webDev: WebDev = WebDev(),
    val devOps: List<String> = listOf("Azure", "Jenkins"),
    val tools: List<String> = listOf("Firebase", "SaleForce MarketingCloud", "JFrog Artifactory")
)
data class MobileDev(
    val native: List<String> = lisfOf("Android Developement","iOS Developmenet"),
    val hybird: List<String> = lisfOf("React Native","Flutter")
)
data class WebDev(
    val frontend: List<String> = listOf("React", "Nodejs"),
    val backend: List<String> = listOf("Nodejs", "RESTful APIs", "Spring Boot")
)

```

<!--
**leopardwong/leopardwong** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
