# bounty-qrcode-parser

A software bounty to convert the node module "qrcode-parser" into an windows native executable


## Details
This repository is offering a bounty for anyone who can convert the "qrcode-parser" module/source code into an __windows executable__ using __pkg__, __nexe__, or __electron-builder__.


## Required source files (qrcode-parser)

https://www.npmjs.com/package/qrcode-parser

https://github.com/sinchang/qrcode-parser#readme
<br /><br />

## Live example
https://qrcode-parser.netlify.app/

<br />

## Helpful Tools

### Create Random JSON Data Here:
https://json-generator.com/
<br />

### Convert it to a QRCode here (Use Correction Level Q or Higher)
https://www.easyproject.cn/easyqrcodejs/tryit.html
<br />

### Take the Image and covert it to a Base64 String here
https://www.base64-image.de/

__or__

https://base64.guru/converter/encode/image
<br />
### Feed the base64 string into qrcode-parser

https://qrcode-parser.netlify.app/

<br /><br />


## Requirements
The command-line executable should take a __base64 string__ (which represents any qrcode-image) as an argument, and output the decoded qrcode information to
the command line (using console.log or some other means).  If an error is thrown when attempting to decode the __base64 string__, throw an error message;

For example: <br /> <br />

```
C:\bounty-qrcode-parser>qrcode-parser.exe <base64 String>
Output: hello world!

```

```
C:\bounty-qrcode-parser>qrcode-parser.exe <base64 String>
Error: Unable to parse argument
```

<br /><br /> The following QR Code Base64 string can be used for testing purposes <br /><br />


__hello world!__ 
```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```


<br /><br />
The javascript file entry point (prior to compiling down to an windows executable) might look something like this, but feel free to construct whatever you feel is the best approach
```
const qrcodeParser = require('qrcode-parser');
const arg = process.argv[2]; //cli argument 

qrcodeParser(arg).then(result => {
 console.log("output: " + result);
}).catch(error => {
  console.error("Error: Unable to parse argument");
});
```

<br /><br />If you decide to undertake this bounty please place the project in a directory named ```bounty-qrcode-parser```.  Upon completion, please zip the bounty project and include __all necessary files and step by step instructions__ for __creating the executable__ so that it can be tested.
Once the work has been validated I will submit payment.<br /><br />

If you have any questions please feel free to contact me at mobilecontrolsoft@gmail.com

# Bounty Payment:  __$75.00__ <br /><br />
 <br /><br />
 <br /><br />
