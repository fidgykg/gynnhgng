1) Go to https://fabricmc.net/develop/template and generate a template:
   Minecraft 1.21.11, Yarn mappings, Mod ID: iraqimoney, Package: com.iraqimoney
2) Delete the template's example classes/mixins, then copy this folder's src/ into the project (replace files).
3) Run: ./gradlew build   -> jar in build/libs/
In game: /shop opens the shop. Edit prices in ShopScreenHandler.java (ENTRIES).
