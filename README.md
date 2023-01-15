# Data-compression-using-lzw-and-huffman-algorithms
The aim of our project is to compress short text in order to reduce memory usages by  Data compression technique. The  aim of the project is to compare two different data compression algorithms  namely, LZW algorithm and Huffman algorithm.


COMPRESSION RATIO:

In this, we've compared the compression ratios of LZW algorithm and Huffman 
algorithm. Compression ratio is that the ratio of the uncompressed size to the 
compressed size. This ratio are often helpful in indicating complexity of data set or 
signal. It's helpful in seeing what quantity of a file is compressed without 
increasing its actual size.
Compression ratio=Uncompressed size/Compressed size
As we observe the graph above, LZW algorithm has high compression ratios for 
texts of small input size, while Huffman algorithm has low compression ratios 
for the same. When the compression ratios are high, it implies that for the 
actual input text size, the used algorithm is acceptable and might yield good 
compression results. Therefore, we will conclude that LZW algorithm works 
better for texts of small input size and works proficiently in terms of small text 
compression.


TIME COMPLEXITY:

Time complexity of an algorithm will be a good indicator of the performance of a 
algorithm. As the dictionary size is fixed and independent of the input length, LZW 
yields a time complexity of O(n) as each byte is barely read once and also the 
complexity of the operation for every character is constant. The time complexity of 
the Huffman algorithm is O(nlogn). Employing a heap to store the weight of every 
tree, each iteration requires O(logn) time to work out the cheapest weight and insert 
the new weight. There are O(n) iterations, one for every item. This suggests that 
LZW algorithm also works better in terms of time complexity because it is quicker.

