# 50StatesOfComics
Data and Documentation for the Graphic Possibilities 50 States of Comics Initiative

Full OpenRefine Project Data is available [on Dropbox](https://www.dropbox.com/scl/fi/6webs8ckeixlxel5znksa/Get-Started-with-Dropbox.pdf?rlkey=ksnt1i5bx2568ext6jsnosk5o&st=zfb8nhr8&dl=0)

## Steps for getting 50 states of comics data:
1) Download and open full dataset in OpenRefine
2) Open a text facet in the state column and filter for desired state
3) [Reconcile](https://openrefine.org/docs/manual/reconciling) column full_location against wikidata 
4) Go through and match all values to wikidata items (if not all 
5) Download the data:
  5a) Download > Custom tabular exporter
  5b) Copy 50_States_of_comics_export-example.json and paste into the "Option Code" tab in the exporter
  5c) Make sure you have the right data selected 
  5d) Make sure that reconciled columns export the QID for the item, not the item's label or the original text in the cell; and that unreconciled cells output the cell's text.
6) Create a new project in OpenRefine using the data exported in step 5
7) Under the Undo/Redo tab, click "Apply," then paste the text from 50-states-of-comics-openrefine-recipe.json and click "Perform operations"
8) Ensure the format matches 50-states-of-comics-Ohio.xlsx (if it doesn't, you may need to undo those changes and data wrangle by hand)
9) Download as xlsx and upload to Google Sheets, making sure that it matches previous datasets ([Like the Ohio one](https://docs.google.com/spreadsheets/d/1vLFWssaPvowgs9oQj4mMTMOu4dBePo5W/edit?usp=sharing&ouid=107762365020168075041&rtpof=true&sd=true))
