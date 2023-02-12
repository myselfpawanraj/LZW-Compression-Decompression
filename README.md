## LZW Compression/Decompression Algorithm
### Introduction
LZW (Lempel-Ziv-Welch) is a lossless data compression algorithm that is widely used for data compression and data transmission. The algorithm is simple, fast, and provides good compression ratios. This Java implementation of LZW can be used to compress and decompress text files.

### Algorithm Overview
The LZW algorithm works by creating a dictionary of unique strings and their corresponding codes. As the input text is processed, the algorithm adds new strings to the dictionary and assigns them a unique code. This process continues until all of the input text has been compressed into a sequence of codes.

When decompressing, the algorithm uses the codes to look up the corresponding strings in the dictionary and rebuilds the original text.

The LZW algorithm uses a variable-width code, meaning that the number of bits required to represent a code can change as the size of the dictionary grows. The algorithm starts with a fixed number of bits (usually 8 or 12) and increases the number of bits as needed to accommodate the growing size of the dictionary.

### Usage
This implementation provides two classes for compression and decompression: compress and decompress.

* [Compression](./MyComp.java)
* [Decompression](./MyDecomp.java)

### Conclusion
The LZW compression/decompression algorithm is a simple and effective way to compress and decompress text data. This Java implementation provides an easy-to-use interface for compressing and decompressing text files.
