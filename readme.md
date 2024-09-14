# Simple Archiver

A command-line archiver tool written in Go, capable of compressing files using the Shannon-Fano encoding algorithm. The tool allows you to pack files using Variable-Length Coding (VLC) and store them with a `.vlc` extension.

## Features

- **File Compression**: Compress files using Shannon-Fano encoding via the VLC method.
- **Custom Methods**: Easily extendable to support additional compression methods.
- **Command-line Interface**: Interact with the tool via simple CLI commands using the `cobra` library.

## Installation

To install the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/akuliakuli/goarchiver
