1. Матрицалық көбейту __matmul.cpp__ файлында жүзеге асырылған

#### command: make

        Matrix mult: ijk run time is: 0.75526

        Matrix mult: jik run time is: 0.779777

        Matrix mult: kij run time is: 0.401694

        Matrix to vector mult: run time is: 0.00355

#### command: make -EXTFLAGS='-O3' 

        Matrix mult: ijk run time is: 0.262969

        Matrix mult: jik run time is: 0.268058

        Matrix mult: kij run time is: 0.046232

        Matrix to vector mult: run time is: 0.00123


2. N = 500, 512, 1000, 1024, 2000, 2048 матрицалық көбейту уақыттары 
Барлық командалар __O3__ флагымен компиляцияланған
###### N = 500:
        Matrix mult: ijk run time is: 0.149832
        
        Matrix mult: jik run time is: 0.130572
        
        Matrix mult: kij run time is: 0.045606
        
        Matrix to vector mult: run time is: 0.000624
        
###### N = 512:
        Matrix mult: ijk run time is: 0.278448
        
        Matrix mult: jik run time is: 0.267043
        
        Matrix mult: kij run time is: 0.045168
        
        Matrix to vector mult: run time is: 0.000275

###### N = 1000:
        Matrix mult: ijk run time is: 1.3334
        
        Matrix mult: jik run time is: 1.2496
        
        Matrix mult: kij run time is: 0.344876
        
        Matrix to vector mult: run time is: 0.001065
        
###### N = 1024:
        Matrix mult: ijk run time is: 2.44418
        
        Matrix mult: jik run time is: 2.28913
        
        Matrix mult: kij run time is: 0.388196
        
        Matrix to vector mult: run time is: 0.001221
        
###### N = 2000:
        Matrix mult: ijk run time is: 28.6923
        
        Matrix mult: jik run time is: 27.0391
        
        Matrix mult: kij run time is: 4.91789
        
        Matrix to vector mult: run time is: 0.004674
        
###### N = 2048:
        Matrix mult: ijk run time is: 45.9769
        
        Matrix mult: jik run time is: 36.4702
        
        Matrix mult: kij run time is: 6.20823
        
        Matrix to vector mult: run time is: 0.004632
