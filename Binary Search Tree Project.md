# BINARY SEARCH TREE PROJECT
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] Write down the Binary Search Tree sequence stages.

### Root : 7
## 1. Pass: 5<7                

             7 
            /
           5
    
## 2. Pass: 1<7 --> 1<5

             7
            / 
           5
          /
         1
         
## 3. Pass: 8>7

               7
              / \
             5   8
            /
          1
          
## 4. Pass: 3<7 --> 3<5 --> 3>1 

              7
             / \
            5   8
           /
          1
           \
             3
            
## 5. Pass: 6<7 --> 6>5

               7
              / \
             5   8
            / \
           1   6
           \
             3
            
## 6. Pass: 0 < 7 --> 0<5 --> 0<1

               7
              / \
             5   8
            / \
           1   6
          / \
         0   3
        
## 7. Pass: 9>7 --> 9>8 

                7
               / \
              5   8
             / \    \
            1   6    9
           / \
          0   3
         
## 8. Pass: 4<7 --> 4<5 --> 4>1 --> 4>3
         
                 7
                / \
               5    8
              / \     \
             1   6     9
            / \
           0   3
                \
                 4
                
## 9. Pass: 2<7 --> 2<5 --> 2>1 --> 2<3

                   7
                  / \
                 5   8
                / \    \
               1   6    9
              / \
             0   3
                 / \
                2    4

---
* Patika.dev link: https://app.patika.dev/yigitmustu                                                    