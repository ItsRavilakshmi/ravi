Nan Mudhalvan Project

Arrays  :
-------------
It can store more than one element in a single variable name. But the datatype should be same.
[ ] - subscript. within subscript pass the array size.
Array index starts with 0.
combination of rows and columns are called cells.

Types.
1. One dimentional array  ex: int a[2];
2. Two dimentional array
     1.   2 dim  --  int a[2][2];
     2.   3 dim  --  int a[2][2][2];
--------------------------------------------------------------------------------------------------
int main()
{
int a[2][2][2] ,b[3][3][3] ,c[4][4][4];
int no=100,m,i,j;
for(m=0;m<2;m++)
{
printf("\nMatrix : %d\n",(m+1));
for(i=0;i<2;i++)
{
for(j=0;j<2;j++)
{
a[m][i][j]=no;
b[m][i][j]=a[m][i][j];
c[m][i][j]=a[m][i][j]+b[m][i][j];
printf(" %d",c[m][i][j]);
no++;
}
printf("\n");
}
printf("\n\n");
}
return 0;
}
-----------------------------------------------------------------------------

int main()
{
int a[10][10]={{1*2,2*2,3*2,4*2},
                          {1*3,2*3,3*3,4*3},
                          {1*4,2*4,3*4,4*4}};
printf(" %d",a[1][1] );
return 0;
}
-------------------------------------------------------------------------------

int main()
{
int a[2]={10,20};
func(a);
return 0;
}
func(int x[2])
{
int i;
for(i=0;i<2;i++)
{
printf("\n%d", x[i]);
}
-------------------------------------------------------------------------------------
int main()
{
int a[100][100],size,i,j;
printf("enter size : ");
scanf("%d",&size);
for(i=0;i<size;i++)
{
for(j=0;j<size;j++)
{
printf("enter element : ");
scanf("%d",&a[i][j]);
}
}
for(i=0;i<size;i++)
{
for(j=0;j<size;j++)
{
printf("\n%d row %d column : %d",i,j,a[i][j]);
}
printf("\n");
}
return 0;
}
-----------------------------------------------------------------------------------------


1929  concatination of array
3190  find maximum operations to make all elements divisible by three.
1512  number of good pairs.






















































