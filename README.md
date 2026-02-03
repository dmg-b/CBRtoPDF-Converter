# CBRtoPDF-Converter
A simple Windows .exe application for converting comic book archives (.cbr) into high-quality PDF files without resizing or quality loss.

CBR to PDF Converter is a lightweight Windows desktop application built with C# and WinForms.
It allows you to convert one or multiple .cbr (Comic Book RAR) files into .pdf format while preserving the original image resolution, aspect ratio, and quality.

The application is designed to be minimal, fast, and easy to use — no complicated settings, just select files and convert.

## Features

✅ Convert .cbr (Comic Book RAR) files to .pdf
📂 Batch conversion (multiple files at once)
🖱 Drag & Drop support
🖼 No image resizing or compression (maximum quality)
📄 Correct page order (natural sorting: 1, 2, 10 instead of 1, 10, 2)
📊 Progress bar and status indicator
💻 Simple and clean GUI
📦 Can be built as a standalone .exe

<img width="386" height="266" alt="image" src="https://github.com/user-attachments/assets/f2c76daa-5e88-402a-9af9-ee3478845aa0" />

## System Requirements

Windows 10 / 11
.NET 6 / 7 / 8 (not required if using self-contained build)

## How to Use

1. Launch the application (.exe)
2. Click «Choose CBR» or drag .cbr files into the window
3. Click «Convert»

The resulting PDF files will be saved next to the original .cbr files

## Built With

C# (.NET WinForms)
SharpCompress — for extracting .cbr (RAR) archives
PDFsharp — for creating PDF files

## Output

Each .cbr file is converted into a .pdf file with the same name
Output PDF files are saved in the same directory as the source files

⚠ Notes

Supported image formats inside CBR: JPG, JPEG, PNG, WEBP

Files are processed in natural order to ensure correct page sequence

Temporary files are automatically removed after conversion

## License

This project is released under the MIT License.
You are free to use, modify, and distribute it.
⭐ Acknowledgements

Thanks to the open-source community and the developers of SharpCompress and PDFsharp.
