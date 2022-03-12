# Assignment #1. Playing with Kotlin

The assignment is to make a simple application with Kotlin.

The task at hand would be to sort students into groups.

Each student would have some kind of a score, and a number of groups they would like to be in. (the groups are equal in priority)
```
data class Student(val name: String, val score: Float, val groups: Collection<String>) 
```
Your program should be able to generate a list of such objects.
```
Alice 5.0 Games Mobile Web
Bob 4.5 Mobile Web Robotics
Clare 6.1 Web Games Mobile
...
```
Each group should have a limited number of potential members (< total number of students!).
```
Games 5
Mobile 5
Web 5
Robotics 5
```
Your goal is to sort students into groups based on their score in such a way that most students would be assigned into a group. If some students are left out they are grouped together for further sorting.

To create Kotlin application you can choose to:

* Use compiler in command-line: https://kotlinlang.org/docs/command-line.html
* Install IntelliJ IDEA: https://www.jetbrains.com/help/idea/create-your-first-kotlin-app.html
* Install VSCode extension https://technology.amis.nl/software-development/quickly-get-going-with-kotlin-on-windows-using-vs-code-as-ide/
* Create an empty application in Android Studio and use it only to log data to console: https://developer.android.com/studio/debug#systemLog
* 
* Use an online compiler: https://play.kotlinlang.org/

