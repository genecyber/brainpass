This folder hosts the external JS libraries. Most of them are minified but they should be identital to the original distributed file. For verification purposes (to prevent backdoor inserted in the minified JS) you can go to each repository and do a binary diff against the original file.

--------------------

# Stanford Javascript Crypto Library #

#### sjcl.js ####
http://bitwiseshiftleft.github.com/sjcl/  
Commit ff46726

#### codecBytes.js ###
Addtional sjcl code not included in the minified bundle  
Commit 136512284d

--------------------

# Bootstrap #
#### bootstrap.min.js ####

https://github.com/twbs/bootstrap  
Commit 867e2be (version 3.0.1)

--------------------

# jQuery #
version 2.0.3

--------------------

# Bitcoin JS (pulled in for their BigInteger implementation) #
https://github.com/bitcoinjs/bitcoinjs-lib  
Commit a6f05fb50513e671062c4aafd734f7657a64f156
