# CellPhone-File-To-Remailer

Send remailer messages via uploaded file to a mixmaster server.

MixMailFromFile.sh

This program checks to see if there is a file named 'mail'
is in a newly created ?user?.  The file containing the remailer headers and
message is loaded up to the server with 'VX ConnectBot' through a 'VX ConnectBot' 
ssh connection. If the file 'mail' is found in /home/user, this script
sends the remailer message contained in 'mail' and 
shreds/deletes the file afterwards.
