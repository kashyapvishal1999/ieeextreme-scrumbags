# counting molecules

Your task is to count the number of molecules in a cup of soda which contains distilled water, carbon dioxide, and glucose. You have a machine that counts the number of atoms of carbon, hydrogen, and oxygen in a given sample.

## Input Format

The input consists of a single line with three space separated integers: *c*, *h*, and *o*

where

*c* is the count of carbon atoms

*h* is the count of hydrogen atoms

*o* is the count of oxygen atoms

## Constraints

0 ≤ *c*, *h*, *o* < 1010

## Output Format

If the number of atoms is consistent with a mixture containing only water, carbon dioxide, and glucose molecules, the output should consist of a single line containing three space separated integers: the number of water molecules, the number of carbon dioxide molecules, and the number of glucose molecules.

If the number of atoms is not consistent with a mixture containing only water, carbon dioxide, and glucose molecules, the output should consist of a line containing the word Error

## Sample Input
```
10 0 20
```

## Sample Output
```
0 10 0
```

## Explanation

The input indicates that there are 10 carbon atoms and 20 oxygen atoms. The only way that this could occur would be if there were 0 water molecules, 10 carbon dioxide molecules, and 0 glucose molecules.
