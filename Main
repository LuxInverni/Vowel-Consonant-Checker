#include <stdio.h>

    int main()
    {
        char c [40];
        int vowels, consonants = 0;
            printf("Enter a word: ");
            scanf("%[^\n]", c);

        for(int i=0; c[i]!='\0'; ++i)
        {
            if(c[i] == 'a' || c[i] == 'e' || c[i] == 'i' || c[i] == 'o' || c[i] == 'u' || c[i] == 'A' || c[i] == 'E' || c[i] == 'I' || c[i] == 'O' || c[i] == 'U')
                {++vowels;}
                else
                {++consonants;}
        }
        printf("%s has %d Vowels and %d Consonants.", c, vowels, consonants);
        return 0;
}
