# dp-display
Tools to allow reading of data from closing of DPReview.com forums

Dp-display.html is a local web page that allows you to drag-and-drop your DPReview message dump (if you requested your data from DPR) and present the messages in a more human-readable format.

At the present, more work is needed to correctly format the data.

## How to use:

- Drag and drop your forum-posts.json file into the box
- From the list of displayed topics, choose which batch of messages you want displayed
    (It may take several seconds for it to unpack the data)
- Scroll down or use the search to see your messages and quoted info.

## Limitations:

- Currently, I don't clear out the previous data, so if you keep clicking on topics, it just appends to the bottom of 
    the document, which will get very large.  For now, refresh the web page to start over with a clean page.
- There's not enough formatting.  Quoted data is not indented or colored, and the whole page is not styled.
- Readers have not been created for the other .json files, only forum-posts.json.
