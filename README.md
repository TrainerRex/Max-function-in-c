//#Max-function-in-c
#include <stdio.h>
int main() {
    int ans;
    int max(int a, int b, int c, int d);
    int a, b, c, d;
    scanf("%d \n%d \n%d \n%d", &a, &b, &c, &d);
    ans = max(a, b, c, d);
    printf("%d", ans);
}
    int max (int a,int b,int c,int d)
    {
        if (a<b&&c<b&&d<b)
        {
            return b;
        }
        else if (a<c&&b<c&&d<c)
        {
            return c;
        }
        else if (a<d&&b<d&&c<d)
        {
            return d;
        }
        else if (b<a&&c<a&&d<a)
        {
            return a;
        }
        return 1;
    }
