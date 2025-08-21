** IMPORTANT NOTE **

* File Should Start With :  
```
int,byte,byte,byte,byte,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int,int
```
* YOU SHOULD REMOVE , from every line at the end
  
This tool is free to use and was made by JadaDev.

Requirements : 
DBCUtil to convert CSV to DBC.

What this tool does :
Creates All type of CharacterStartOutfit Information such as Classes / Races / Genders etc...
Information
Make sure that the ID is always higher than what you have if you're going to add new lines to your existing files.
You make sure to check the auto increasement box next to the ID.

How to use : 

1.Pick The Class you want to give items or display items on when you create a new character.
2.Else Pick All Races or Specified One.
3.Else Pick Both Genders or Specified One.
4.Pick Whatever Items you want to add. ( Nothing should be -1 on entry and displayid ) ( No entry should be -1 on displayid and you could pick exp : miniteleporter item or so ).
5.You could get all DisplayID's by using Apply Database DisplayID's remember that you need to config the database connection ( this doesn't hurt your database ).
6.Just Generate and copy the text to the CSV or else make a new CSV named 'CharStartOutfit.dbc.csv'
7.Drag and drop the 'CharStartOutfit.dbc.csv' file to DBCUtil and you'll get 'CharStartOutfit.dbc'.
8.Now you could create a Patch like you do for items and put it inside "DBFilesClient" also remember if you want players to actually have those items you listed you need to place it inside DBC files.

-- Backup is very important as always and if you got any issues please start thread on wowemu.org forum.

Next Version would have : 

Directly Creation of 'CharStartOutfit.dbc'.
Edit 'CharStartOutfit.dbc' or 'CharStartOutfit.dbc.csv'.
CSV File Creation.
