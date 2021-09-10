var fs = require("fs");                 //accessing/requiring the file system       

fs.mkdirSync("nishit");                   //creating the folder --> demo
fs.writeFileSync("nishit/hello.txt","Hello from demo",(err) => {           //creating the file --> hello
    if(err){
        console.log(err);
    }
});

var data = fs.readFileSync("nishit/hello.txt","utf-8");                    //reading the file hello.txt and fetching it in data
console.log(data);                                                       //printing data

fs.appendFileSync("nishit/hello.txt",",this is the appended text");           //appending some text in hello.txt file
data = fs.readFileSync("nishit/hello.txt","utf-8");
console.log(data);

fs.renameSync("nishit/hello.txt","nishit/hello2.txt");                          //renamed the file

fs.unlinkSync("nishit/hello2.txt");                                           //file deleted

fs.rmdirSync('nishit');                                                       //folder/schema deleted