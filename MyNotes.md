1. create a new repo on github
2. git clone URL :to create a local repo
3. navigate to the new local repo
4. touch - creates a new file in this repo
To write into the file - go to that directory with cd:
echo "put text here" > FileName
(or - open that file with a text editor, put in text and save)
5. git add FileName (add . - will add everything in the folder)
6. git commit -am 'MessageHere'
7. git push

### Basic CLI commands

* pwd :shows the path to the current working space
* clear :clears the screen
* ls :lists the files and folders
ls -a :lists hidden files
la -al :lists details about the hidden files
cd Job Hunt Related/Daphne :change directory - move to another dir
	cd :will take me home
	cd.. :moves me up one dir
mkdir NewFolderName :creates new folder
touch test_file :creates an empty file
cp NameOfFile NameOfFolder :copy file to a dir/folder
cp -r DirName1 DirName2 :moves one dir to another dir
rm test_file :remove/delete
rm -r :will delete a dir with all its contents/files
mv new_file Documents :move files between directories 
mv new_file renamed_file :also used to rename files
echo :will print the argument you provide
date :will print today's date