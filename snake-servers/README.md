For NonJava languages:
- please go to .\src\main\<language>
- chose your language
- and follow README.md instructions

For Java:
- setup Java (JDK 8)
    + setup JAVA_HOME variable
- setup Maven3
    + setup M2_HOME variable
    + setup Path variable
    + open cmd and run command 'mvn -version' it should print valid java and maven location
- import this project as Maven project into Intellij Idea / Eclipse
- please install Engine dependency
- in class .\src\main\java\com\codenjoy\dojo\bomberman\client\YourSolver.java
    + copy board page browser url from address bar and paste into main method
    + implement logic inside method
        * public String get(Board board) {
    + run main method of YourSolver class
    + on page http://server/codenjoy-contest/board/game/bomberman you can check the leaderboard - your bot should move
    + if something changed - restart the process
        * warning! only one instance of YourSolver class you can run per player - please check this
- in class .\src\main\java\com\codenjoy\dojo\bomberman\client\Board.java
    + you can add you own methods for work with board
- in test package .\src\test\java\com\codenjoy\dojo\bomberman\client
    + you can write yor own test
- Codenjoy!
