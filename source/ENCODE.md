## **How to Batch Download ENCODE Data**

##### Use the filters to select the experiments you need.

<img src="_static/ENCODE/01.png" alt="RTDimport" style="zoom:40%;" />

##### Click the shopping cart icon on the right to add the desired experiments to the cart.

<img src="_static/ENCODE/02.png" alt="RTDimport" style="zoom:40%;" />

##### Click **View Cart**.

<img src="_static/ENCODE/03.png" alt="RTDimport" style="zoom:40%;" />

##### In **DATASET TYPE**, check **experiment**, otherwise you will not be able to download. 

<img src="_static/ENCODE/04.png" alt="RTDimport" style="zoom:40%;" />

##### After selecting the file types you need, click **Download**. Save the `files.txt` file. Then enter the following command in the terminal to start downloading:

<img src="_static/ENCODE/05.png" alt="RTDimport" style="zoom:40%;" />

```
xargs -n 1 curl -O -L < files.txt
```

##### **Tip:** The downloaded `.bigBed` files can be converted into `.bed` files.

