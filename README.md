# simple-perl-code-on-win-to-rename files
This is a repository for the small code segments that I wrote to remove prefix of file name which contains a long string with adverticement information including mobile phone number.

The tricky part is the characater set setting , it needs to read file names from windows7 , by default it is coded with GBK,
however the Chinese characater in the script it uses as pattern is coded with utf-8 , so we need to decode it from utf-8 , then
encode it it with GBK , then we can use the pattern to match the file name...

It is also a sample code in perl to walk through a directory , to do a match , to practise loop control , etc.
