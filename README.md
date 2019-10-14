# SUNY FIT Beamer Theme for LaTeX

Hi. This is a FIT theme for the LaTeX package Beamer, using a customized watermark, and with 
edited color theme. See the .sty for credits. What it does is make a really nice slide presentation using documentclass{beamer} and 
\usetheme{FITTheme} using LaTeX, much like you might be used to in Powerpoint. Included is a screenshot from one of my lectures. 

Now, I'm going to assume 
you're already using beamer to make presentation slides using LaTeX. If not, you'll need to set that up. Here's what I do:

```
brock@amidala:~$ sudo apt-get install latex-beamer
```

 YMMV. Now what you'll need are three files. One is called beamerthemeFITTheme.sty, which either goes in your tex tree, or in the directory of the 
 document you're creating. Bit of advice: put it in your tree, and run texhash. 

You'll also need something called fitseal.png. that makes the little watermark in the bottom right corner. Again, this must be either in your working 
directory, or, preferably, somewhere in your tree, where LaTeX can find it.


You're also gonna need your .tex file. I've included the template that I use, which I use to create my ethics and political philosophy lectures 
pictured in the sample pdf. 

Get all three relevant files in the .tar file.

I hope this is helpful.
