insert mode, motion

quit

:q

save then quit

:wq

save and _fucking_ quit!

:wq!

movements

h, j, k, l

w, b, (small letters)

W, B, (big letters, e.g. skip dots)

2W (move two big words)


delete (d<movement>)

dd, dt, df, dF, dT

yank

2yw (yank 2 words)

5yd (yank 5 words)


end and beginning of line

$, ^, A, I

go to line

G (bottom of file)

gg (top)

:10, 10G, (goto line 10)

~ (go to previous position)

<c-d> (move down page)

<c-u> (move up page)

paste 

p (paste clipboard to left of cursor or below line)

P (paste right of cursor or above line)

y5wp (yank 5 words, paste)

y42Gp (yank from here to line 42, paste)


undo

u (undo)

<c-r> (redo)


macros

q

find

/ (fwd -- n to iterate, N to iterate backwards)

? (reverse search)

* (highlight current word)


move to other paren or bracket

% (highlight current word)


replace

r



visual mode

<c-v> ("grab" multilines)



tab line

<< (shift lines)



move line up

J



new line

o (new line below)

O (new line above)



sed

:s/replace_me/with_this/gc (replace replace_me on line with confirmation)

:%s/replace_me/with_this/gc (replace replace_me entire file w/ confirm)

:65,67s/replace_me/with_this/gc (replace replace_me lines 65-67)
