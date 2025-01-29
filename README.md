# code--9
Recursion in array

#include <stdio.h>

int main()
{
    int arr[]={1,2,4,2,5,4,7,2,7,8,3,3};
    int len= sizeof(arr)/sizeof(arr[0]);
    for(int i=0;i<len;i++){
        for(int j=i+1;j<len;j++){
            if(arr[i]==arr[j]){
                printf("%d\n",arr[i]);
            }
        }
    }
    return 0;
}
