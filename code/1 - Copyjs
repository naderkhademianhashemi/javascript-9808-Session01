var fs = require("fs");

console.log("start");

fs.readdir(".", function(err, files){
	if(err){
		console.log(err);
		return;		
	}
	
	for(var i=0; i<files.length; i++){
		console.log(files[i]);
	}
})