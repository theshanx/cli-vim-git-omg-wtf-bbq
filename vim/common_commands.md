QUITTERS
-------
-:w		write file (save)
-:w text.txt	write file named text.txt
-:wq		write and quite
-:q!		quit without writing

MODES
-----
-i		enter Insert mode from Command mode
-esc		exit Insert mode and return to Command mode
-i	goes into Insert mode so you can add text
-I	goes into insert mode at the begining of the current line
-A	goes into insert mode at the end of the current line
-o	adds a new line below the current line and goes into insert mode
-`O` ADDS A LINE ABOVE and goes into Insert

GETTING AROUND
---------------
-h	to move the cursor one space left
-j	to go down one line
-k	to go up one line
-l	to go one space right
-gg	takes you to the beginning of the file
-G	takes you to the end of the file
-0	takes you to the beginning of the line
-$	takes you to the end of the line
-w	takes you to the next word
-b	takes you back a word
-control + b	takes you back a page
-control + f	takes you forward a page
-control + d	takes you down half a page
-control + u	takes you back a word


EXTERMINATE!
-----------
-dw	to delete a word
-d$	to delete from where you are to the end of the line
-dd	to delete the whole line you are on
-dgg	to delete from where you are all the way back to the beginning of the file.


COPY/PASTE
----------
-v	begins your selection
-y	ends and yanks your selection
-p	pastes your selection
-yy	yanks the line you are on
-yap	yanks the paragraph you are on


MIND THE GAPS
-------------
-vi{	with your cursor in the middle of {two curly braces}, it will copy everything between them (so you can paste the same thing elsewhere) (works with any type of bracket, including <[()
-ci<	with your cursor in the middle of a <tag>, this will remove the words between the < & > and go into insert mode, so you can type in a new tag (works with any type of bracket, including {[()
-cit	with your cursor in the middle of text between <tags>, it will delete everything between the tags, so you can rewrite your content

FIND/REPLACE
------------
-/bird	searches for "bird" in your file
-n	scrolls through the returned hits for "bird" in your file after searching
-:%s/dogs/cats/gc	replaces all of the "dogs" in your file with "cats"
-:2,6s/dogs/cats/g	replaces all of the "dogs" between rows 2 and 6 with "cats"

DUAL WEILDING
-------------
-:sp	I'll open up a file like I noramlly do with `vim file1.html`, and then I will type `:sp file2.html` -- this will cause file2 to appear on the bottom half of my screen! Awesome! Similarly, if I typed `:vsp file2.html`, it would cause file 2 to appear on the right side of the screen instead of the bottom.
-`w` 		to move your cursor one pane clockwise
-`R` or `r`	 to rotate the panes around
-`h`, `j`, `k`, or `l` to move left, down, up, or right, respectively
-`n`	 	to open a new file

DIDN'T I ALREADY DO THESE?
--------------------------
-`i` goes into Insert before your cursor (which is why I had to move over to get around a closing tag)
-`a` goes into Insert AFTER your cursor
-`A` goes into Insert AT THE END OF THE LINE! (new favorite, since it replaces both `$` and `i` for me)
-`o` ADDS A LINE BELOW and goes into Insert


