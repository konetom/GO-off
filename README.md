<h1>GO-off</h1>

This is a simple Python script to get GO enrichment results from GORILLA and REVIGO (with default settings).

<style>
    pre {color: #5468FF; margin: 25px;}
</style>
<pre>
Notes:
geckodriver operates firefox browser, so you have to install Firefox browser before running this script
Please run it only with Windows 10, and in case it is not working, please let me know
Expected inputs are text (.txt) lists with Arabidopsis gene IDs separated by newlines - located in same folder as the script
Expected outputs (saved in foled "output") are:
    one text (.txt) file containing Arabidopsis gene IDs made by user-defined merge (inside parentheses is the number of gene IDs)
    two screenshot (.png) images from GORILLA and REVIGO webpages
    excel tables: 
        GORILLA table with calculated enrichment, etc.
        GORILLA gene IDs extracted from GORILLA table GO categories
        REVIGO table
        REVIGO reduced table (dispensability <= 0.7)
        GO RESULTS = most important file - contains REVIGO-reduced GO IDs and GORILLA-counted numbers (enrichment, ...)
This script can be run multiple times in a loop, but keep in mind that the content in folder "output" is overwritten every time
I apologize for the script. This is still just my spaghetti code... if you do not understand any part, please ask me
</pre>
