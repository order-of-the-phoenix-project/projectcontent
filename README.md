# projectcontent

## Downloading to your PC:

Follow the steps here: https://gohugo.io/getting-started/installing/#windows
Basically just create those directories (C:\Hugo\bin and C:\Hugo\Sites) and then download the Hugo zip file and extract the contents to C:\Hugo\bin.
Then you'll start typing "Environment Variables" in your Windows search bar. It'll bring up something that says "Edit the system environment variables". Select that, then select "Environment Variables". Under "User Variables", find one that says "Path" and double-click on it. Then hit "New" and type "C:\Hugo\bin". Hit OK on that window along with the rest to exit out of there.

Once you have that set up, go to Github Desktop and clone order-of-the-phoenix-project/projectcontent to the Local path 'C:\Hugo\Sites\projectcontent'.
Then open your file browser and go to C:\Hugo\Sites\projectcontent and you should see folders called "archetypes", "content", "themes" and a file called ".gitmodules" and another called "config.toml". If you don't, talk to Andrew. If you do, in that same folder, create a folder called "public".

Once you have that folder created, go back to Github Desktop and clone order-of-the-phoenix-project/order-of-the-phoenix-project.github.io to the Local path "C:\Hugo\Sites\projectcontent\public"

## Making changes:

While in the projectcontent folder, open the command line (you can hold shift and right click in the folder, and it'll give you an option to open command line or powershell there, either is fine). 

In the command line, you can type "hugo new posts/<insertpageyouwanthere>.md" Make sure you add the .md part to the end so it knows it's in Markdown. After you've done that, you can open the file it made in the /content/posts folder. Make your changes, then save.

Once you've saved everything, you can commit your changes to the projectcontent git. If you want the changes published to the site open the command line in the projectcontent folder, then type "hugo -D" and that will get hugo to compile the changes. From there, you can open Github Desktop and commit the changes to the website.
