# My Wholesome Blog
###### by bishwin

## Steps
1. `git clone git@github.com:Bishwin/selftitled.git`
1. `mkvirtualenv wholesome`
1. `pip install -r requirements`
1. run with `make devserver`
1. stop with `make stopserver`


## Making Posts
Use handy dandy script `make_entry.py` to create posts

`python make_entry.py "My_Wholesome_Post_Name"`


When editing a post  
`Status: draft` moves content to drafts and isn't visible on homepage  
`Status: published` sets a post visible and appears on homepage   
