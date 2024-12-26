# 2024cha_7-1
#include <stdio.h>

int main()
{
    char greetings[] = "Hello World!";
    
    printf("%s\n",greetings);
    
    greetings[0] = 'J';
    
    printf("%s", greetings);
    
    greetings[0] = '4';
    return 0;
}
