# tippitytappity-design

tippitytappity is a program to practice typing

# tippitytappity-design

tippitytappity is a program to practice typing


## Data model

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
