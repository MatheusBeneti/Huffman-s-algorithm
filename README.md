# Huffman Compression Algorithm

This is a simple text compression algorithm based on Huffman coding. It allows compressing and decompressing text using Huffman encoding, which is a lossless compression method.

## How does it work?

The Huffman algorithm works by assigning shorter binary codes to more frequent letters and longer binary codes to less frequent letters. This allows the text to be compressed based on the occurrence frequency of letters in the original text.

The compression process involves three main steps:
1. Counting the occurrence frequency of each letter in the original text.
2. Building a Huffman tree based on the frequencies of the letters.
3. Assigning binary codes to each letter based on the Huffman tree.

## How to use?

The compression and decompression algorithm are implemented in Python. To use:

1. **Compress text:**
   ```python
   text = "Text to be compressed"
   compress = Compress(text)
   binary_text = compress.get_binary_text()
   letters_code = compress.get_letters_code()
