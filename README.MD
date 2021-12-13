# Japanese Study App

### The goal of this app will be three-fold

1. **To learn source control to a deeper level**

   Collaborating on projects is the best way to get a feel for source control in the real world. 

2. **To acquire new skills**

   It's likely that we will be interacting with more than one library that we haven't touched before.

3. **To build a full stack application over the course of months**

   I'd like to take this project and build upon it over a long timespan, and grow the project as I grow myself. I want to be able to look at my code I wrote in December, 2021 and be able to say, "wow, I was bad..." in June, 2022.



Some ideas:

- The development cycle for this app should probably be separated into a few phases, as this may be quite involved

## Research Phase

We will need to research

- Accurate OCR libraries 
  - OCR has evolved quite a bit between 2016-2021. The introduction of DeepL and Google Keep has completely changed the potential of Japanese learning
  - Check this out, it's incredible:
    - http://capture2text.sourceforge.net/
- Our competition
  - We shouldn't put too much thought into this, but it's worth looking to see what others are doing, and seeing what we can learn from their implementations
  - https://kitsun.io/ - might be the best modern flashcard app (read: successor to anki)
  - https://www.wanikani.com/ - a close second

## Tech Stack

For speedy development, I am leaning towards:

### Backend

Django and a REST api plugin.

Reasons:

- HUGE community who are there for support
- Tons of free youtube videos of people coding django apps live

- very extensible, and robust
- able to keep backend completely separated from frontend. Hell, can be used extensively as just an API gateway to authenticate users and store their flashcard history and nothing more???

### Frontend

React or Vue, whatever is more convenient.

Reasons: 

- we can skip all the setup required with html/webpack/etcetcetc just by using boilerplate code, and we can be off to the races with designing in a day
- job opportunities are most abundant with the above two frameworks

### Database

Postgres

Reasons:

- It's free and we don't need to deal with cloud based stuff just yet. I guess this can change at any point but it might be a little messy to immediately work with networking related stuff, etc.

However: at the very early stages of development I think it's totally fine to just use a super simple database like sqlite. 



Thoughts??