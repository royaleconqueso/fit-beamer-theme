# fit-beamer-theme
SUNY FIT Beamer Theme for LaTeX
Hi. This is a FIT theme for the LaTeX package Beamer. Actually it's a modification of the Boadilla theme, using a customized watermark, and with edited color theme. See the .sty for credits. What it does is make a really nice slide presentation using documentclass{beamer} and \usetheme{FITTheme}using LaTeX, much like you might be used to in Powerpoint. Here's a screenshot from one of my lectures:
Now, I'm going to assume you're already using beamer to make presentation slides using LaTeX. If not, you'll need to set that up. Here's what I do:

brock@amidala:~$ sudo apt-get install latex-beamer

Reading package lists... Done

Building dependency tree... Done

The following NEW packages will be installed:

  latex-beamer
  
0 upgraded, 1 newly installed, 0 to remove and 222 not upgraded.

Need to get 2377kB of archives.

After unpacking 3445kB of additional disk space will be used.

Get:1 http://http.us.debian.org sid/main latex-beamer 3.01-1 [2377kB]

Fetched 2377kB in 40s (59.1kB/s)                        

Selecting previously deselected package latex-beamer.

(Reading database ... 72557 files and directories currently installed.)

Unpacking latex-beamer (from .../latex-beamer_3.01-1_all.deb) ...

Setting up latex-beamer (3.01-1) ...

mktexlsr: Updating /usr/local/share/texmf/ls-R... 

mktexlsr: Updating /usr/local/lib/texmf/ls-R... 

mktexlsr: Updating /var/lib/texmf/ls-R... 

mktexlsr: Updating /var/lib/texmf/ls-R-TEXMFMAIN... 

mktexlsr: Updating /var/cache/fonts/ls-R... 

mktexlsr: Done.

brock@amidala:~$ 

 YMMV. Now what you'll need are three files. One is called beamerthemeFITTheme.sty, which either goes in your tex tree, or in the directory of the document you're creating. Bit of advice: put it in your tree, and run texhash. It's here:

beamerthemeFITTheme.sty

You'll also need something called fitseal.png. that makes the little watermark in the bottom right corner. Again, this must be either in your working directory, or, preferably, somewhere in your tree, where LaTeX can find it.

fitseal.png

You're also gonna need your .tex file. I've included the template that I use, which I use to create my ethics and  political philosophy lectures pictured above. I'll also include a bit of a tutorial soon. I'll put it here:

FITbeamertemplate.tex

Get all three relevant files here:

fourfiles

I hope this is helpful.
