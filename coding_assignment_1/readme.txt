# Coding Assignment 1

In the 2015 USA speech, count the number of appearances of "United Nations", replace it with "UN", and put the modified text back to DF.

Hints
1. To see how to merge elements in a list, see https://www.geeksforgeeks.org/python-merge-list-elements/ 
    
2. The following snippet produces the desired text into a list of tokens
<code>
text = df.query("year==2015 and country=='USA'")['text'].values[0] 
text_list = list(text.split(" "))
</code>
