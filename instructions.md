
# Import new publications

academic import --bibtex content/publication/mypublications.bib

# Other install

* brew install git golang hugo
	* Open the hidden ~/.zshrc (or ~/.bashrc) file in a text editor, add the following line, and restart your Terminal app so that Hugo can find the location of its Go dependency.
	* export PATH=$PATH:/usr/local/go/bin

## Notes

* To add PDFs, need to put in the respective folder in content/publication and have the pdf file name match the folder name. Then it will automatically upload


Build website

hugo
cd public
git add .
git commit -m "Build website"
git push origin master
cd ..