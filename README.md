# PatikaDEV_Project3
Binary Search Tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] 

~Question: Write Binary Search Tree stages of the array

~Solution:

Binary Search Tree is a node-based binary tree data structure which has the following properties:

 1)The left subtree of a node contains only nodes with keys lesser than the node’s key.

 2)The right subtree of a node contains only nodes with keys greater than the node’s key.

 3)The left and right subtree each must also be a binary search tree.
 
 1.step: 7    ,2.step:   7    ,3.step:      7       ,4.step:         7       ,5.step:         7
                        /                  /                        / \                      / \
                       5                  5                        5   8                    5   8
                                         /                        /                        /
                                        1                        1                        1
                                                                                           \
                                                                                            3

6.step:         7       ,7.step:     7         , 8.step:       7          ,9.step:          7
               / \                  / \                       / \                          / \
              5   8                5   8                     5   8                        5   8
             / \                  / \                       / \   \                      / \   \
            1   6                1   6                     1   6   9                    1   6   9
             \                  / \                       / \                          / \
              3                0   3                     0   3                        0   3
                                                                                           \
                                                                                            4
   
10.step:          7
                 / \
                5   8
               / \    \
               1  6    9     
              / \              
             0   3    
                / \
               2   4
                
                
www.patika.dev 
