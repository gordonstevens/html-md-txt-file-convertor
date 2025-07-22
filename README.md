# **File Converter**

This is a simple, client-side web application designed to convert files between various text-based formats, including HTML, Markdown, and plain Text.

**This script emphasizes user privacy by performing all conversions locally within your browser, ensuring that your files are never uploaded to any server.**

## **✨ Features**

* **HTML to Markdown Conversion:** Transform your HTML documents into Markdown format.  
* **Markdown to HTML Conversion:** Convert Markdown files back into HTML.  
* **HTML to Text Conversion:** Extract plain text content from HTML files.  
* **Text to HTML Conversion:** Wrap plain text content into basic HTML paragraphs.  
* **Markdown to Text Conversion:** Get the raw text content from Markdown files.  
* **Text to Markdown Conversion:** Convert plain text files into a basic Markdown structure.  
* **Offline Processing:** All conversions happen directly in your browser, guaranteeing that your data remains private and secure. No files are ever sent to a server.  
* **Batch Processing:** Upload and convert multiple files at once. The converted files will be downloaded as a single ZIP archive.  
* **Dark Mode:** A toggle for a comfortable viewing experience in different lighting conditions.  
* **Local Fonts & Inlined CSS:** Uses system fonts and embeds all custom CSS directly into the HTML for faster loading and reduced external dependencies.  
* **Error Handling:** Provides clear messages for file loading, conversion, and download issues.  
* **Timestamped Downloads:** Generated ZIP files include a date and time suffix for easy organization.

## **🚀 How to Use**

1. **Open the Application:** Open the index.html file (or the HTML file containing this code) in your web browser.  
2. **Select Conversion Type:** The application is divided into sections for different conversion types (e.g., "HTML to Markdown", "Markdown to HTML").  
3. **Upload Files:**  
   * Click the "Upload \[File Type\] Files" button within the desired conversion section.  
   * Select one or more files from your local machine.  
   * Once uploaded, the file names will appear in a list, indicating they are "Ready for conversion".  
4. **Convert and Download:**  
   * Click the "Convert \[Source Type\] to \[Target Type\]" button.  
   * The application will process the files locally.  
   * A ZIP file containing all the converted documents will be automatically downloaded to your computer. The ZIP file name will include a timestamp (e.g., converted\_html\_to\_markdown\_YYYYMMDD\_HHMMSS.zip).  
5. **Toggle Theme:** Use the sun/moon icon in the top-right corner to switch between light and dark modes.

## **🔒 Privacy**

A core principle of this File Converter is **privacy**. All file processing and conversions occur entirely within your web browser. Your files are **never uploaded to any external server**, ensuring that your sensitive data remains on your device.

## **🛠️ Technologies Used**

* **HTML5:** For the application structure.  
* **CSS (Tailwind CSS & Custom Inlined Styles):** For styling and responsive design. Tailwind CSS is used via a CDN for utility classes, while custom styles are inlined.  
* **JavaScript:** For all interactive functionality and conversion logic.  
  * **JSZip:** A JavaScript library for creating, reading, and editing .zip files.  
  * **Marked.js:** A Markdown parser and compiler written in JavaScript.

## **🔗 More Useful Tools**

Here are some other helpful tools for document manipulation that you might find useful:

* [**Scribe OCR (Image/PDF to Text)**](https://scribeocr.com/) \- For optical character recognition to extract text from images and PDFs.  
* [**Stirling PDF (PDF Manipulation)**](https://stirlingpdf.io/) \- For various operations on PDF documents, such as merging, splitting, compressing, and more.
