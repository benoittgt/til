# Motions I didn't know

I dig into to vim help (`:help motion.txt`) and learn few tips that I would share :

1. Where am I?

  Before when I wanted to get the path of the current file or now the full path I was doing `:echo join([expand('%'),  line(".")], ':')` how is very precise. If you simply want the path do `CTRL-G`.
  Before when I wanted to get the path of w the full path I was doing `:echo join([expand('%'),  line(".")], ':')` how is very precise. If you simply want the path do `CTRL-G`.

2. Quick delete accross multiple lines :

  `dvj`: deletes from the cursor position until the character below the cursor >
  `d<C-V>j`: deletes the character under the cursor and the character below the cursor.
