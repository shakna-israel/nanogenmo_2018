# NaNoGenMo

NaNoGenMo is inspired by the writing competition of a similar name, but is focused more on computers writing the novel.

This is an entry for the 2018 competition.

See the [2018 page](https://github.com/NaNoGenMo/2018) for more.

---

[//]: # (Try it: [](repl.it))

---

## Dungeon Crawl

The idea this entry is focused on, is *readability*.

In a 50,000 page novel you need a far amount of variety and progress to be felt, rather than a repition of a small sequence of things.

Unfortunately, when I started down a route focused around that, it ended up taking several hours to render 500 words. Apparently, providing weights to everything, takes a lot to calculate, even in a fast language like C.

So, I stripped it back. Maybe a bit too far.

This is a linear story, however, it involved a large number of variables. I've attempted to hide the machine, with the man.

That is, the random choices given to the machine were written by me, and don't tend to be a few words here or there, but longer sequences.

All said, reading a book output by this generator will probably be a slog. A horrifyingly boring and repitious slog.

However, it may still be interesting, in parts.

We create a hero, gender indeterminate, with a somewhat readable random name (though my name generator needs a serious rethink), and one of a series of classes.

Then, we enter a loop.

Inside the loop, we create what becomes a chapter of the book.

A series of random descriptions about the cave, and then a chance of:

a) An enemy encounter.

or

b) A boss encounter.

These encounters have some random aspects inside them, but also are different for each of the classes the protagonist might be.

Then we also have treasure (different for each class), and maybe traces of either the missing princess, or the kidnapping monster.

There's also a disembodied voice that haunts the protagonist.

Repeat until we have enough words in our book.

Then, do our final battle.

The protagonist might lose.

If the protagonist does win, however, something else might happen. A bit of a twist.

Finally, utilise the amazing [pandoc](https://pandoc.org) to render us a PDF, HTML or ePub (eBook) copy.

Personally, I think the PDF provides the best reading experience.

---

## License

This is awful software.

As such, I curse the public with it.

This is released under the [CC-0 License](LICENSE), effectively public domain.
