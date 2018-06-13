# Datasets from the 2018 Russian Facebook Ad Release

<img src="https://media.githubusercontent.com/media/russian-ad-explorer/russian-ad-datasets/master/images/2016-01/P10003209.-000.png">

On May 10, 2018, Democrats on the United States House Intelligence Committee <a href="https://democrats-intelligence.house.gov/facebook-ads/social-media-advertisements.htm">released</a> 3500+ ads created by the Internet Research Agency between 2015 and 2017. The Internet Research Agency is believed to have created these ads to influence the outcome of the 2016 United States presidential election, and in general influence Americans' political views. 

You can download this data <a href="https://democrats-intelligence.house.gov/facebook-ads/social-media-advertisements.htm">here</a>. It's also mirrored via Github Large File Service (LFS) on this repository: <a href="https://github.com/russian-ad-explorer/russian-ad-pdfs">https://github.com/russian-ad-explorer/russian-ad-pdfs</a>.

There are five datasets collected here:
* Text files extracted from these pdfs using <a href="https://linux.die.net/man/1/pdftotext">pdftotext</a>
* Images extracted from these pdfs using <a href="https://linux.die.net/man/1/pdfimages">pdfimages</a>, and cropped using <a href="http://www.imagemagick.org/script/index.php">ImageMagick</a>.
* A JSON file organizing some of the attributes found in the above datasets. Documentation about how this dataset was created, and the meaning of the keys, is coming soon.
* A dataset of thumbnails for easy loading on the <a href="russian-ad-explorer.github.io">Russian Ad Explorer</a>.
* Two CSV files containing some informal categorizations of some of the "Targeted Interests" and "Location" categories, for use in the <a href="https://russian-ad-explorer.github.io/">Russian Ad Explorer</a> web app. You can read more about how these categories were chosen in the <a href="https://russian-ad-explorer.github.io/about">About</a> section of that page.

I've mirrored the some of the datasets on Google Drive. You can download the extracted images <a href="https://drive.google.com/open?id=1rKuPaB7NMMdGraeB-L2HolLkhbBLIswG">here</a> and the downloaded text here: <a href="https://drive.google.com/drive/folders/1baK_hVQrVsa1phjRy5UZ4LSmRYp9txOa?usp=sharing">here</a>.