# tippitytappity-design

tippitytappity is a program to practice typing

## Data Model 
```mermaid
classDiagram
  TypeTest <|-- TypePhrases
  UserAccounts <|-- UserLog
  UserLog <|-- TypeTest
    class TypeTest{
      - question: string
      - solution: string
      + typeanalyze(): bool
      + gradecompare(): bool
}
    class TypePhrases{
      + typecapture(): bool
      + typereturn(): string
}
    class UserLog{
      - userid: integer
      - name: string
      - userscore: string
  }
    class UserAccounts{
      - userlist: array
      - rankusers: array
}

```
