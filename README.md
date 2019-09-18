# learning-linux-winfrednyoroka
learning-linux-winfrednyoroka created by GitHub Classroom

Basic Command lines to navigate the terminal


## Print working directory (pwd)

**pwd** _it means print working directory, you get the path of where you are in the directory


## List (ls)
**ls** _it means you are listing the items either they could be directories or subdirectopries or they could be files in your directory either the current directory or another directory away from where you are.

list can take up options
> ls -l
> ls-a
> ls -alh
> ls -R
## Changing the directory (cd)

**cd** _it involves changing your directory 

type the following:
cd  _it takes you to your home directory
cd ~ _it takes you to home directory
cd / _it takes you to root directory

cd . _it refers to your current directory

cd .. _it takes you to one directory back, actually the parent directory of where you are except when in the root directory


cd ../.. _it takes you two levels up from where you are currently

## Making a directory (mkdir)
**mkdir** _ this command enables one to create a directory
for instance: mkdir learning_unix
# NB: when naming directories in terminal avoid use of spaces, since terminal uses spaces when giving commands. instead make use of underscores

mkdir -p outer_git/inner_git
The above command line helps you create two directories at the same time where the second directory is hosted within the first directory
# look for help
mkdir --help

# Looking for manuals for the command lines

__man__ helps the operator access the manual pages for each unix command 
e.g

man   | command
------- | ------
man | mkdir
man  | ls
man | grep
man | cp
man | cd

# Removing directories
__NB__ you can only remove a directory when you are outside the directory
e.g **rmdir** inner_git



# Create empty files
**touch** this command can be used in creating empty files

e.g touch learn_git.txt


# Moving files
**mv** -this command helps in moving files between directories. however, it does not make a copy of the file. 

In moving files then you must specify the file and the directory you want to move to


## Copying files (cp)

cp _ it involves copying files into directories. the advantage is that you always retain a copy of your original file

cp 'input the file name' "preferred directory"
## NB: Input file may include the path showing where your directory is located
for instance : cp '~/Documents/NGS/COURSE_DATA/UNIX COURSE/MALARIA.FASTA' "."
