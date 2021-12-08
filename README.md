## What is this?
This is a flashcard organizer using the (leitner system)[https://en.wikipedia.org/wiki/Leitner_system]. A proven method for using flashcards. This just keeps track of them

## How it works 'n stuff
`flash add [URL]` to add the url of your flashcards, you can just use a name of say a subject for physical flashcards
`flashcard increment [URL]` to increment the box and due date of the flashcards
`flashcard today` to show all of the flashcards with a duedate of today, use the option `-o true` to open all of the URLs in your default browser

It uses a date system of
| Box   | Amount of days since making |
| ---   | ---                         |
| Box 1 | 1 Days                      |
| Box 2 | 2 Days                      |
| Box 3 | 5 Days                      |
| Box 4 | 9 Days                      |
| Box 5 | 14 Days                     |

## Instalation
You'll have to go through the code and change stuff for it to work for now, I might change this later or you can now, one step that is important is
```
cd ~ && touch flashcards.json
```
