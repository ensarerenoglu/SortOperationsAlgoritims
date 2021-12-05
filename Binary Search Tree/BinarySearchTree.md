# Binary Search Tree [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] 

- Dizinin Binary-Search-Tree aşamaları
    * [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] 
    * Root 5 olması durumunda Aşamalar
        - 7 5'ten büyük mü? büyük -sağında yaz
        - 1 5'ten büyük mü? küçük -soluna yaz
        - 8 5'ten büyük mü? büyük -8 7'den büyük mü? büyük -sağına yaz
        - 3 5'ten büyük mü? küçük -3 1'den büyük mü? büyük -sağına yaz
        - 6 5'ten büyük mü? büyük -6 7'den büyük mü? küçük -soluna yaz
        - 0 5'ten büyük mü? küçük -0 1'den büyük mü? küçük -soluna yaz
        - 0 5'ten büyük mü? büyük -9 7'den büyük mü? büyük -9 8'den büyük mü? büyük -sağına yaz
        - 4 5'ten büyük mü? küçük -4 1'den büyük mü? büyük -4 3'ten büyük mü? büyük -sağında yaz
        - 2 5'ten büyük mü? küçük -2 1'ten büyük mü? büyük -2 3'ten büyük mü? küçük -soluna yaz
    * 
                    [5]
            [1]            [7]
        [0]     [3]     [6]    [8]
            [2]     [4]           [9]
