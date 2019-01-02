# Menginput dan menampilkan array



## Coding Program lengkap


    #include <stdio.h>
    #include <stdlib.h>
    int main()
    {
    int nilai[5],x;
    printf("Memasukkan nilai : \n");
    for (x=0;x<5;x++)
    {
        printf("Nilai Angka : "); scanf("%d",&nilai[x]);
    }
    printf("\n");
    printf("Membaca Nilai : \n");
    for (x=0;x<5;x++)
    {
        printf("Nilai Angka : %d\n",nilai[x]);
    }
    return 0;
    }

## Hasil Program
![img](https://github.com/MUTIARAIZMI/Menginputdanmenampilkanarray/blob/master/1.algo9.jpg?raw=true)
