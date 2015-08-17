# printPreview
Sample POC for html page printing with custom header and footer

This sample is using [columnizer-jquery-plugin](http://welcome.totheinter.net/columnizer-jquery-plugin/) for spliting the page in multipage with custom header and footer on each printing page.


## Demo.

Check [here](http://jeshu.github.io/Print-Preview/index.html) for the demo.

Please note you need to manually hit Ctrl-p to check the print preview for the page.

## Working.
Columizer api breaks page in multiple column and here in this case kept column size 1 and rendered it in custom template which have 3 parts
	header
	contant
	footer

with footer print css for page break is added to avoid the overlapping of the contant. 

## Limitiations
Here we need to fix the supported page length as we need to keep the height for printing page fixed to make page print properly.

## Issues
Currenty its showing Page no. which is overlapping, and this can be easily removed by editing api or just by CSS.