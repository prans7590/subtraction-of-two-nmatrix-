# subtractio-of-two-matrix-

#include <stdio.h>

int main(int argc, char const *argv[])
{  
    int i = 0 ;
    int j = 0; 
    int c[i][j];

    int  a[3][3]= {{2,3,4},
                   {4,3,2}, 
                   {3,3,2}};
    int  b[3][3] = {{3,3,3,}, 
                   {5,4,3,}, 
                   {9, 8, 8}};

           for(int i=0;i<3;i++){    
               for(int j=0;j<3;j++){    
                 c[i][j]=a[i][j]-b[i][j];    
      printf("%d   ", c[i][j]);
}    
      printf("\n");
} 
    
     
    return 0;
}
