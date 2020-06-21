# Code coloring for different applications
### SQL Developer (Obsidian theme)
  1. Copy contents of sqldeveloper/obsidian.xml
  2. Ensure that SQL Developer is not open. Go to location of dtcache.xml file.
     In my system, it is located at C:/Users/USERNAME/AppData/Roaming/SQL Developer/system19.2.1.247.2212/o.ide.13.0.0.1.42.190403.1502
  3. Add the contents of obsidian.xml inside schemaMap element of dtcache.xml. Save.
  4. Start SQL Developer
  