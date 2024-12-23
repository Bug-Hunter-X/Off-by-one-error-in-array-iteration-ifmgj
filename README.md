This repository contains a simple Java program demonstrating a common off-by-one error during array iteration. The error occurs in the first for loop. The loop iterates from 0 to arr.length (inclusive), causing an ArrayIndexOutOfBoundsException because the valid indices for an array of length 5 are 0 to 4 (inclusive). The solution demonstrates the correct way to iterate through an array using a loop condition of i < arr.length. The fixed code iterates correctly through the array without throwing any exceptions.