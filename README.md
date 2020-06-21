# Code coloring for different applications
### SQL Developer 
#### Obsidian theme
  1. Copy contents of sqldeveloper/obsidian.xml
  2. Ensure that SQL Developer is not open. Go to location of dtcache.xml file.
     In my system, it is located at C:/Users/USERNAME/AppData/Roaming/SQL Developer/system19.2.1.247.2212/o.ide.13.0.0.1.42.190403.1502
  3. Add the contents of obsidian.xml inside schemaMap element of dtcache.xml. Save.
  4. Start SQL Developer
#### Dark Mode (inspired by this Medium [post](https://medium.com/@rammelhofdotat/oracle-sql-developer-theme-7c870ce19fb5)) (Tested against v19.2.1.247)
  1. Ensure that SQL Developer is not open. Go to sqldeveloper/ide/themes. Backup fusionblue.jar  
  2. Unzip fusionblue.jar and replace the theme.properties inside the META-INF folder with the one in this package  
  3. Re-zip to fusionblue.jar  
  4. Start SQL Developer
  
