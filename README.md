1. Clone pokeChat onto your computer
	git clone https://github.com/eduardogochi/pokechat.git
2. Run: npm install
	This will create a node_modules folder in which all external dependencies will be downloaded. 
3. Run: npm run build
	This will create the file public/app.js, a bundle file where the whole application will reside, without this the app cannot be run.
4. Run: npm start 
	This will start the server, and will be listening on port 3000. You can see it in http://localhost:3000