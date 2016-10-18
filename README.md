# HackerRank_Staircase
using System;
using System.Collections.Generic;
using System.IO;
using System.Linq;
class Solution {

    static void Main(String[] args) {
        int n = Convert.ToInt32(Console.ReadLine());
        string character="#";
        for(int i=1;i<=n;i++){
            for(int j=1;j<=i;j++){
                Console.Write(character.PadLeft(n));
            }
            
            Console.WriteLine();
        }
    }
}
