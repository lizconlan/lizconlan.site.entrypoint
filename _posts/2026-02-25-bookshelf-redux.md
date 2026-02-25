---
layout: post
title: 13 years later…
categories:
- tech
keywords: AI, Claude Code, books
intro:
  Hello. I've been busy. And I've brought back and old friend!
---

### AI and other stories

I've been glancing at my old Bookshelf project on and off for a while. There either wasn't the time or I couldn't figure out the right approach to add the new features I craved.

For the longest time, I'd wanted to be able to add new books and edit metadata via a web interface rather than by meticulously editing individual files and folders. And thanks to our new AI overlords, now I can.

The self-imposed constraint was always a bit weird (but without constraints, where's the fun?) - the book catalogue _has_ to be served from a static file so - apart from that one time where writing files to disk was briefly possible - updating book data was always going to be a tall order.

Enter AI assistance and a freshly renewed desire to experiment (and with it an excuse to revist older projects). What if the AI can break the deadlock? Other than a rainy afternoon, what is there to lose?

I explained what I wanted and what I'd already tried in Plan Mode, it had a think and came back with 3 suggestions, one of which was recommended - create the editing tool as a separate Sinatra app hosted in the same repo; spin it up on localhost only when the editing feature was needed. I issued my orders accordingly with specific instructions about commiting small pieces of work, how it should identify itself when commiting work and mostly just watched and approved commits and edits.

Towards the end I needed to intervene a bit more as the UI got a bit more complex than either of us had anticipated once we got into the specifics of folder nesting for books with multiple editions but we got there in the end. And - even with a bit of manual testing to make sure the editing tools were usable - I think I took longer trying to batch up over a decade of commits as vaguely sensible releases to make the separation of old work and new a bit clearer. (The resulting orphaned files commit is my fault - I interrupted work in progress and didn't double check the untracked files.)

And it's finally here. 13 years after my last blog post and "only" 5 after my last merged commit on the project. 

If you think you might enjoy an ebook wrangling tool, even if you're not the type to buy the same book twice by mistake, [there's a free one here if you'd like one](https://github.com/lizconlan/bookshelf)
