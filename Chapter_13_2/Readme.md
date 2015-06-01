##Can you show me the contents of database.yml?##

in the command line i would type **cat database.yml** and it will show me its contents:

Omars-MacBook:tmp OC$ cat database.yml
This is a test!Omars-MacBook:tmp OC$

##What is a Gemfile?##

Your gemfile is a list of all gems that you want to include in the project. It is used with bundler (also a gem) 
to install, update, remove and otherwise manage your used gems.

To create a Gemfile enter **bundle init** which then creates a Gemfile, then to view its contents enter **cat Gemfile**
here is what i get:

Omars-MacBook:tmp OC$ cat Gemfile
                   # A sample Gemfile
                   source "https://rubygems.org"
                   
                   # gem "rails"
                   Omars-MacBook:tmp OC$



##Try cat ex12.txt ex13.txt.##

I tried this command with two files that i already created in the tmp directory. 
I entered **cat file2.txt file3.txt** and it listed the contents of both files back to back. 
