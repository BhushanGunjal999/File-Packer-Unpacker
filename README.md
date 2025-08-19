# 📦 File Packer & Unpacker in Java

## 🔹 Project Overview

This project is a **Java-based File Packer and Unpacker utility** that allows users to combine multiple files into a single packed file and later extract them back to their original state. It demonstrates the concept of file handling, I/O streams, and data serialization in Java.

The project is divided into two main modules:

* **File Packer** → Reads multiple files from a directory and combines them into a single packed file.
* **File Unpacker** → Extracts the original files from the packed file and restores them with their original content.

## 🔹 Features

* Pack multiple files into a single compressed file.
* Unpack files to retrieve original contents.
* Handles text and binary data.
* Demonstrates practical use of **File I/O, Streams, and Object-Oriented Programming in Java**.
* Efficient and lightweight implementation.

## 🔹 Use Cases

* Bundling multiple small files into one for easy sharing.
* Backup and restore system for files.
* Educational project to understand **Java File Handling & Streams**.

## 🔹 Technologies Used

* **Java** (Core Java, File I/O, Streams, Exception Handling)

## 🔹 How to Run

1. Compile both files:

   ```bash
   javac FilePacker.java FileUnpacker.java
   ```
2. Run the packer:

   ```bash
   java FilePacker <source_directory> <packed_file_name>
   ```
3. Run the unpacker:

   ```bash
   java FileUnpacker <packed_file_name> <destination_directory>
   ```
