# Transformer-Snubber
very effective transformer secondary snubber - without "Rectifier snubbing", the widespread (inaccurate) use of capacitors across the rectifier diodes  

----

Please read the doc:  
"<a href="docs/Quasimodo_jig_revA.pdf">Simple, No-Math Transformer Snubber using “Quasimodo” Test Jig</a>" by Mark Johnson  
  
That's what this repo is about:  
Construction of a test device to determine the correct values for a CRC snubber, which fits individually to the measured transformer type, so that no overshoot (=ringing / noise) occurs.  
<img src="hardware/THT/Quasimodo_V4_TH_photo.jpg">  

----

here is also a mathematical approach from TI   
(but for switched-mode power supplies. However, it can also be used for 50/60 Hz applications)  
https://e2e.ti.com/blogs_/b/powerhouse/posts/calculate-an-r-c-snubber-in-seven-steps  
Backup here: <a href="docs/related/Power Tips Calculate an R-C snubber in seven steps.pdf">docs/related/Power Tips Calculate an R-C snubber in seven steps.pdf</a>
