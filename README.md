#include <stdio.h>
int main() {
    int i, n;
    int arr[100],sum=0;
    printf("\n Enter the number of elements: ");
    scanf("%d", &n);
    printf("Enter numbers: ");
    for (i=0;i<n;++i)
        {
        scanf("%d", &arr[i]);
    }
    printf("\n the elements are :);
    for (i=0;i<n;++i)
        {
        printf("%d", arr[i]);
    }
    for(i=0;i<n;i++)
    {sum+=arr[i];
    }
    return 0;
    }
    
