# HackerRank_Staircase
//Write a program that prints a staircase of size .
//Input Format
//A single integer,denoting the size of the staircase.
//Output Format
//Print a staircase of size  using # symbols and spaces.
//Note: The last line must have  spaces in it.
//https://www.hackerrank.com/challenges/staircase
using System;
using System.Collections.Generic;
using System.IO;
using System.Linq;
class Solution {

    static void Main(String[] args) {
        int n = Convert.ToInt32(Console.ReadLine());
    string character="#";
    for(int i=1;i<=n;i++){        
            Console.WriteLine(character.PadLeft(n));
            character+="#";            
        }        
    }
    
}
