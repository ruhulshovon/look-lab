LOOK LAB - setup

1. Open this folder in VS Code (File > Open Folder).
2. Test on your PC: install the "Live Server" extension, right-click index.html > Open with Live Server.
3. Put it online (GitHub Pages):
   - Create a free GitHub account and a new public repository named look-lab.
   - In the VS Code terminal, inside this folder:
       git init
       git add .
       git commit -m "Look Lab"
       git branch -M main
       git remote add origin https://github.com/YOURNAME/look-lab.git
       git push -u origin main
   - On GitHub: repository Settings > Pages > Deploy from a branch > main, folder / (root) > Save.
   - After a minute the app is at https://YOURNAME.github.io/look-lab/
4. On the iPhone: open that address in Safari > Share > Add to Home Screen.
5. To update: edit files, change VERSION in sw.js (for example look-lab-v2), then
       git add . && git commit -m "update" && git push
   Reopen the app twice on the phone to load the new version.

Notes: LUTs you add inside the installed app are stored separately from Safari's storage, so add them again after installing. Recipe v1 is built in.
