#This script imports the txt files for media stories d
#This command installs Simon's personal package designed to import news articles from NewsStand
#Link here
#http://github.com/sjkiss/tm.newsstand
devtools::install_github("sjkiss/tm.newsstand")
#Import text files to tm corpus
#This loads the libraries necessary
library(tm.newsstand)
library(here)
library(tm)

star_file<-here("Data/Newspapers/Toronto Star(2)-2022-10-18-2 1.txt")
#This is the command that reads data in. 
#here builds a file path to the file. 
#NewsSource is the command that actuarlly executes this. 

star<-NewsSource(star_file)
#Now save it in an object
#Turn to Corups
library(quanteda)
corpus(star)
Corpus(star)
#This used to work. 
Corpus(star)

#See my source reader ( think)
NewsSource

