# Datasets from the 2018 Russian Facebook Ad Release

On May 10, 2018, Democrats on the United States House Intelligence Committee <a href="https://democrats-intelligence.house.gov/facebook-ads/social-media-advertisements.htm">released</a> 2500+ ads created by the Internet Research Agency between 2015 and 2017. The Internet Research Agency is believed to have created these ads to influence the outcome of the 2016 United States presidential election, and in general influence Americans' political views. 

You can download this data <a href="https://democrats-intelligence.house.gov/facebook-ads/social-media-advertisements.htm">here</a>. It's also mirrored via Github Large File Service (LFS) on this repository: https://github.com/russian-ad-explorer/russian-ad-pdfs.

There are four datasets collected here:
* Text files extracted from these pdfs using <a href="https://linux.die.net/man/1/pdftotext">pdftotext</a>
* Images extracted from these pdfs using <a href="https://linux.die.net/man/1/pdfimages">pdfimages</a>, and cropped using <a href="http://www.imagemagick.org/script/index.php">ImageMagick</a>.
* A JSON file organizing some of the attributes found in the above datasets. Documentation about how this dataset was created, and the meaning of the keys, is coming soon. 
* A dataset of thumbnails for easy loading on the <a href="russian-ad-explorer.github.io">Russian Ad Explorer</a>.
