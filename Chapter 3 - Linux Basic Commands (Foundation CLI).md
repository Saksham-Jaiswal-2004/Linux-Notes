## Chapter 3: Linux Basic Commands (Foundation CLI)

ls - List directories

ls -l - Lists the details along with the directories

ls -ltr - gives even more details

mkdir - create directories

pwd - present working directory

touch - create new files

cd - change directory

rm - Remove/delete files

rm -r - Recursively delete all files along with a directory, similar to rmdir

rmdir - Remove/delete directories

cat - To see the contents of a file

echo - print or write, ex. echo "My First Line" > demofile.txt

zcat - to see the contents of any zip file

head - to get top 5 or 10 lines

tail - to get bottom 5 or 10 lines

tail -f - Keeps monitoring file to check if more lines are getting added or not, so that it can display those as well

less - page by page displays data so that it is readable

more - shows more pages in a paginated way

cp - copy any file to a desired destination, ex. cp {source} {destination}

cp -r - to copy a whole directory to another

mv - to move a file to a desired destination, can also be used for renaming

wc - returns lenght, word count and storage(bytes) of any file

ln - To create a link (Hard Link)

ln -s - To create a soft link

How to cut and fetch data from a file in terms of bytes?
cut -b 1 {file name} - this will give first byte only
cut -b 1-4 {file name} - this will give first four bytes only

How to print some text as well as store it in a file?
Use "tee"
Ex. echo "Hi There!" | tee {file name}

sort - Alphabetically sorts a file

diff - Returns the difference between two files