*******************************************************************
 
#include <stdio.h>
#include <stdlib.h>
int main(){
    int day, x1 = 0, x2;
    day=9;
    x2=1;
    while(day>0) {
        x1=(x2+1)*2;  // 第一天的桃子?是第2天桃子?加1后的2倍
        x2=x1;
        day--;
    }
    printf("??? %d\n",x1);
    
    return 0;
}
********************************************************************