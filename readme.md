# Compress File Size


Step 1:- Install this package using command

    npm i compressfilesize

Step 2:- Include compressfilesize.js in your file

ex:- 
            
    import reduceFileSize from './compressFileSize/index.js'

Step 3:- reduceFileSize is a function in your file which having some parameter, first and second paramenter is mandatory.

a) First is the file object to reduce size.

b) Second is call back.

c) Other params are optional, You can checkout compressfilesize.js for pass other params.

ex:- 

    var fileObj = event.target.file[0];

    reduceFileSize(fileObj, () => {
        // Do stuff here after reducing size of file.
    });