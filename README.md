# 2

### How to Use

- This is the code for square matrix multiplication.
- You can execute in your console. Please input like `java Matrix N`.
- `N` is the size of a square matrix.
- The execution time and sum of the all values in the result matrix will be shown.

***
### Data Visualization

- __data.txt__ is the result of the __MatrixImpl.run()__.

- I have plot the datas to a graph using __gnuplot__.
    - `set xrange [100:1000]`
    - `set yrange [0:20]`
    - `set title 'Matrix Size and Execution Time'`
    - `set xlabel 'matrix size'`
    - `set ylabel 'execution time'`
    - `plot "data.txt" using 1:2 with points`
    ![graph](https://user-images.githubusercontent.com/34668695/58796707-fd736700-8638-11e9-8811-690da2e14a03.png)
    
    - `replot 0.000000015*((x - 100)**3)`
    ![graph2](https://user-images.githubusercontent.com/34668695/58797169-437cfa80-863a-11e9-88df-6cb87cb05953.png)
  
