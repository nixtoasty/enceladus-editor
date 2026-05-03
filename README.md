# kirigraph
 
kirigraph is a minimal dark text editor built on electron and node.js. it's designed to behave like a real native app rather than a web page stuffed into a window.

# code wise terms

currently, there will be none because of the fact that i have been constantly writing this but every single ai text detector wants to be a struggle and say that my text looks 100% ai generated even though it's not.

# build kirigraph from source

inside of here, you will get a script that you can use to build kirigraph from source. doing it is easy because of how low the code-amount is.
```
git clone https://github.com/Kiritoasty/kirigraph.git
cd kirigraph
cd electron-builder
npm install
```

other commands to use if building from source:
- `npm run build` (run with administrator, this creates the installer with the icon.ico you have in the folder for electron-builder.)
- `npm start` (test the application, this will open up electron and start the application with it if needing to test)
