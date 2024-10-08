# Use
The main.py file contains a program that outputs a list of specific words within the English language which match a specified pattern (description) entered by the user.
Information in this description can include characteristics such as word length, specific letters in specific positions, and ambiguous spaces between these letters.  

**More updates to be made regularly**
# Description
The description by the user can be comprised of;  

**numbers (exact number of unspecified letters in a space),**  
**lowercase letters (exact letters),**  
**"." (unspecified letters over ambiguous space)**  

which are used to denote the desired word pattern.
# Pattern Syntax
## Letters and Numbers
Lowercase letters are used to represent exactly those letters, with numbers being put before, between, or after them to show how many unspecified letters should be in those spaces.

If some words seem odd, some really odd, it is because this program draws from an extensive text file - one might say overly extensive. This is to ensure all possible words within a pattern are found, even if strange.    

Examples:  
_2 unspecified letters followed by "lp"_   
**Enter word description: "2lp"** 

_output_  
**calp, gulp, help, holp, kelp, kilp, palp, pulp, qflp, salp, yelp**
_________________________________
_"ho" followed by 1 unspecified letter followed by "se"_  
**Enter word description: "ho1se"**  

_output_   
**hoise, horse, house** 
_________________________________
_"nauti" followed by 3 unspecified letters_  
**Enter word description: "nauti3"**   

_output_   
**nautical, nautilus**  
## Periods "."
Periods represent an ambiguous number of unspecified letters within a space.   

Examples:   

_any number of unspecified letters followed by "clone"_  
**Enter word description: ".clone"**   

_output_    
**cyclone, anticyclone**  
________________________________
_"how" followed by any number of unspecified letters followed by "t"_  
**Enter word description: "how.t"**
 
_output_   
**howlet, howzat, howbeit**
_______________________________  
_"jagu." followed by any number of unspecified letters_  
**Enter word description: "jagu."**  
   
_output_   
**jaguar, jaguars, jaguarondi, jaguarundi, jaguarondis, jaguarundis**  
# Mixing
Of course, any number of numbers, letters, periods, and any other number of symbols in future updates, can be combined to make a description pattern.

Example:    
_"el" followed by any number of unspecified letters followed by "tr" followed by 1 unspecified letter followed by "c"_   
**Enter word description: "el.tr1c"**   


_output_   
**electric, eccentric, excentric, egocentric, epigastric, econometric, eurocentric, ethnocentric, electrometric, endosmometric, europocentric**

