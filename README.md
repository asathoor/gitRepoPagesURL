
# Problem: when links to repos are darn images

Often students don't hand in active links to Github in their reports. If the report is designed by InDesign active links are often removed. The frontpage converted to a useless image without hyperlink functionality. 

Here is a quick fix in a Bash script. 

## Usage
From the url you'll know the username and optionally the name of the repo. 

* Enter the github username
* Enter the name of the repo (optional)

The URLs to the repo and to github pages are returned.

## Installation

* Download and unzip
* in a terminal change `gitname` to executable, e.g.

~~~~
chmod a+x gitname
~~~~

Then run the file in the terminal:

~~~~
./gitname
~~~~

