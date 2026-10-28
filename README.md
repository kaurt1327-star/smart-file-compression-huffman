# Smart File Compression & Decompression Tool using Huffman Coding

A simple client-side web application that demonstrates lossless file compression and decompression using Huffman Coding. It uses plain HTML, CSS, and JavaScript, so no installation or build tools are required.

## Run the project
1. Extract the project folder.
2. Double-click `index.html` to open it in a modern browser (Chrome, Edge, or Firefox).
3. Choose a file and click **Compress File**. The tool downloads a `.huff` file.
4. To restore it, select that `.huff` file under **Decompress a File** and click **Decompress File**.

## Files
- `index.html` — complete interface and Huffman coding implementation.

## Notes
- Processing happens in the browser; files are not uploaded.
- This is an educational Huffman format (`HUF1`) intended for use with this application.
- Already-compressed formats may not shrink and can become larger due to metadata overhead.
