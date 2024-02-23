#Data Compression Application
A C++ application to use "Run Length Encoding" and "Dictionary Coder(Huffman)" for data compression and decompression.
##Setup
Step 1 : git clone
Step 2 : cd
Step 3 : g++ -o compressor main.cpp compression.cpp
##Usage
Type ./compressor mode <input-filename> <output-filename>
There are four modes : 
Mode 0 : Compress the input file using Huffman Compression Algorithm.
Mode 1 : Decompress the input file using Huffman Decompression Algorithm.
Mode 2 : Compress the input file using Run Length Encoding.
Mode 3 : Decompress the input file using Run Length Encoding.
Example:
Mode 0 : 
