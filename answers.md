# CMPS 2200 Recitation 6
## Answers

**Name:**__Rey Datwani__


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**
Huffman coding is more efficient than fixed-length coding because instead of always using 8 bits, Huffman uses the appropriate amount of based on the frequency of letters and how many are used. Although I could not get results to put into the table, I know that fixed length coding would probably not have consistent results as Huffman coding for files like asyoulik.txt and alice29.txt because they are scripts with many characters and a lot of variation. Maybe in a file like f1.txt, you would see a consistent trend. 

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt    |                     |                |
alice29.txt    |                     |                |
asyoulik.txt    |                     |                |
grammar.lsp    |                     |                |
fields.c    |                     |                |


- **e.**
Since when certain nodes have the same frequency it does not matter which one you choose when constructing the tree, it would not affect the cost of the huffman code in a major way. I think it would be just as efficient and consistent if it had a file with various frequencies. 

