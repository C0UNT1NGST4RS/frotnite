using System;
using System.IO;
class Program
{
    static void Main()
    {
        // path of the file that we want to create
        string pathName = @"C:\Program\myFile.txt";

        // Create() creates a file at pathName 
        FileStream fs = File.Create(pathName);

        // check if myFile.txt file is created at the specified path 
        if (File.Exists(pathName))
        {
            Console.WriteLine("File is created.");
        }
        else
        {
            Console.WriteLine("File is not created.");
        }
    }
}
