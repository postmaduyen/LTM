# Thử thách trí nhớ Game Server

## Run Step

Run SQL script to create tables

```
CREATE TABLE `user`(
    ID int AUTO_INCREMENT PRIMARY KEY,
    `username` varchar(255) UNIQUE,
    `password` varchar(255),
    nickname varchar(255),
    avatar varchar(255),
    numberOfGame int DEFAULT 0,
    numberOfWin int DEFAULT 0,
    numberOfDraw int DEFAULT 0,
    IsOnline int DEFAULT 0,
    IsPlaying int DEFAULT 0
);

```
Change your database information to DAO.java
```
final String DATABASE_NAME = ""; // TODO FILL YOUR DATABASE NAME
...
final String JDBC_USER = "root";  // TODO FILL YOUR DATABASE USER
final String JDBC_PASSWORD = ""; // TODO FILL YOUR DATABASE PASSWORD
```
