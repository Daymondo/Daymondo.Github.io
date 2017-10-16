---
title: Year 9 Blog - Last 4 weeks
layout: post
author: daymondo
permalink: /year-9-blog---last-4-weeks/
source-id: 1F8FIRyWh-P6d42pr0fGE2Nduq8yeat9iw215QTUvilY
published: true
---
**The beginning of year 9**                                                                                           9/10/17

In the past 4 weeks we have been looking at encryption. So what we have been doing is learning how encrypt and decrypt messages. We have learnt how to do different types of code such as shift 4 were you move all the letters down 4 in the alphabet so A=D,B=E,C=F ect. 

To encrypt our message I used the code:  =VLOOKUP(D1,A1:B27,2 ) 

This code turns h e l l o into z w d d g (in shift 8 which is the code i'm using) all the letters are separate in the code. D1 is where the output of the code goes needs to go. A1:B27 is where the encryption chart is to see what what the letter means, and to be honest I don't know what the 2 means. 

And then to decrypt it =VLOOKUP(D5,$A$28:$B$54,2,FALse ) 

This code turns z w d d g into h e l l o. D5 is where the output code goes. $A$28:$B$54 is the location of the reverse of the code chart so S=A rather than A=S, the dollar signs are used to stop the location($A$28:$B$54)changing as when you drag it across it would change to b28:c54 then c28:d54 which is not where the encryption chart is. False is to nothing if there is nothing there. 

Then we created a table type thing to decode full messages the table isn't fully completed just to let you know. 	

            coded message	zwddg																							program:												left		z	zw	zwd	zwdd	zwddg	zwddg	zwddg	zwddg	zwddg		factor		1	2	3	4	5	6	7	8	9		switch I/0	1	1	1	1	1	1	0	0	0	0														encryption 		z	w	d	d	g						decryption 

											Because we didn't get to the decryption part we couldn't complete the the thing fully but in the first part we looked at separate letters this bit of code decrypts whole words so you don't have to split them up completely. The switch stops the code from running when it doesn't need to so rather than z w d d g it would be z w d d g g g g g g...ect the factor has to be the same as the amount of letters for it to be 1 if it isnt then its 0.

That all we got to in the first 4 weeks of year 9. 												

