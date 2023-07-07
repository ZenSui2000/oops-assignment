# oops-assignment

 A1 There are six methds of opening a file : 

Read Only ('r') : Open text file for reading. ...
Read and Write ('r+'): Open the file for reading and writing. ...
Write Only ('w') : Open the file for writing. ...
Write and Read ('w+') : Open the file for reading and writing. ...
Append Only ('a'): Open the file for writing.

1. Read Only ('r'): This mode opens the text files for reading only. 
2.Read and Write ('r+'): This method opens the file for both reading and writing. 
3. Write Only ('w'): This mode opens the file for writing only. 
4. Write and Read ('w+'): This mode opens the file for both reading and writing.
5. To append to a file in Python, you first need to open the file in append mode. You can do it with open() function

A2 We use the close() file python as we have limited resources that are being managed by the operating system. Hence, closing the files properly helps to protect against hard-to-debug errors like file handles running out or experiencing corrupted data.

A3 file_object  = open("i want to become a data scientist", "mode")

A4 f = open("samplefile.txt", "r")
print(f.read())
file = open("filename.txt", "r")
file.readline()
file = open("filename.txt","r")
file.readlines()

A6 The write() method writes a specified text to the file

f = open("demofile2.txt", "a")
f.write("\nSee you soon!")
f.close()

The writelines() method writes the items of a list to the file.

f = open("demofile3.txt", "a")
f.writelines(["\nSee you soon!", "\nOver and out."])
f.close()
