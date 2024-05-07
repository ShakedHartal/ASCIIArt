# Image to ASCII Art
This project converts image files into ASCII art. The program accepts a relative image path, ASCII character collections and resolution. The output can be displayed in the console or saved in an HTML file.

# Instructions
Place the image file (PNG/JPEG) in the ASCIIArt folder.  
Run the Shell file - ascii_art.Shell.  
The user interface will run in the console.  
Comands the program supports:  
1. exit - exit the program.
2. chars - viewing the current character collection.
3. add - adding characters to the current character set.
   By default, the ASCII character collection includes 0-9.  
   Additional characters can be added using the following commands:  
  'add a' (add the char a).  
  'add m-p' (add the sequence m,n,o,p).  
  'add all' (will add all ASCII Chars).  
  'add space' (add the space charecter).   
4. remove - removal of characters from the current character set.
   Remove ASCII chars from the character collection :
  'remove a' (remove the char a).
  'remove m-p' (remove the sequence m,n,o,p).
  'remove all' (will remove all ASCII Chars).
  'remove space' (remove the space charecter). 
5. res - controlling the resolution of our image - increasing and decreasing the resolution.
   By default, the resolution is set to 128.
  'res up' (doubles the current resolution).
  'res down' (divide the current resolution in 2).
6. image - selecting an image file.
    By default the image is 'cat.jpeg'. To use a different image, place the image file (PNG/JPEG) in the ASCIIArt folder. Use the command: image <relative_path.jpeg/png>.
7. output - choosing the Output format.
    By default, the algorithm output is displayed in the console. To save the output in an HTML file, use "output html". The HTML file will be saved in the "out" folder   within the ASCIIArt directory.
8. asciiArt - running the algorithm on the current parameters.
