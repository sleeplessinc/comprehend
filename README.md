# comprehend


## Install
	
	npm install comprehend


## Usage

	comprehend = require("comprehend");

	comprehend({
	})
	.then( o => {
		console.log(o);
	})

	comprehend = require("comprehend");

	creds = {
		accessKeyId: "YOUR_ACCESS_KEY",
		secretAccessKey: "YOUR_SECRET_KEY",
		region: "us-west-2"
	};

	comprehend(creds, "I have a lovely bunch of coconuts") .then( o => {
		console.log("out="+o2j(o));
	});


	
