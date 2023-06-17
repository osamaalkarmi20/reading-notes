# What is file and stream I/O ?
file and stream I/O (Input/Output) refers to the process of reading from and writing to files or other input/output streams using the classes provided in the System.IO namespace.
It allows you to interact with data stored in files or work with other input/output devices such as the console, network sockets, and memory streams.

<hr>

## Writing to a File:
Create an instance of the StreamWriter class, which is responsible for writing characters to a stream.
Open the file in write mode using the StreamWriter constructor and provide the file path.
Use the Write or WriteLine method of the StreamWriter object to write data to the file.
Close the file to release resources using the Dispose method of the StreamWriter or by wrapping it in a using statement.

<hr>

## Reading from a File:

Create an instance of the StreamReader class, which is responsible for reading characters from a stream.
Open the file in read mode using the StreamReader constructor and provide the file path.
Use the Read or ReadLine method of the StreamReader object to read data from the file.
Close the file to release resources using the Dispose method of the StreamReader or by wrapping it in a using statement.

<hr>

## Things I want to know more about
how to utalize this file and stream I/O  to help control the memory consumption for a certin app if possible.
