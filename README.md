# tippitytappity-design

tippitytappity is a program to practice typing


## Data model

```mermaid
classDiagram
  ExampleParent <|-- ExampleChild
  class ExampleParent{
        - name: string
        - email: string
        - password: string
        + login(user: string, pass: string) boolean
        + get_email(): string
  }
  class ExampleChild{
        - badges vector~string~
        + add_badge(title: string)
        + get_badges() vector~string~
  }

## Data Model 2
--mermaid
classDiagram
  MusicQuiz <|-- NoteInput
    class MusicQuiz{
      - question: string
      - solution: string
      + noteanalyze(): bool
      + gradecompare(): bool
}
    class NoteInput{
      + notecapture(): bool
      + notereturn(): bool
}

    -
  
