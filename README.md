install node

cd desktop

mkdir myProject

npm init ~ package.json [all dependencies are marked and on migration just do "$npm install"]

npm install budo watchify --save -dev

In Package JSON - "scripts", add start..
  "scripts": {
      "start": "budo index.js --live" //live update
  }
  
Tell node to start by typing  - $npm start

//P r e v i e w @http://localhost:9966/ 

//bare minimal package.json
{
	"scripts": {
		"test": "console.log('error test')",
		"start": "budo index.js --live"

	},
	"devDependencies": {
	"budo": "^7.0.2",
	"watchify": "^3.6.1"
	}
}


