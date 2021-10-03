#include <stdio.h>

int main() {



    setbuf(stdout,NULL);

    printf("---------------------------\n");

    printf("\nJawahar Navodaya Vidyalaya\n");

    printf("\n Annual Report Card");

    char Name [15];

    printf("Name");

    scanf("%c",Name);

    while((getchar())!='\n');

    char Standard[15];

    printf("Standard");

    scanf ("\n%c",Standard);

    while((getchar())!='\n');

    char Section[10];

    printf("Section : ");

    scanf("%c",Section);

    printf("\n Marks Secured out of 100");

    while((getchar())!='\n');

    float Mathematics;

    printf("\n Mathematics : ");

    scanf("%f",&Mathematics);



    while((getchar())!='\n');

    float English;

    printf("\n English : ");

    scanf("%f",& English);



    while((getchar())!='\n');

    float Hindi;

    printf("\n Hindi : ");

    scanf("%f", & Hindi);



    while((getchar())!='\n');

    float Science;

    printf("Science : ");

    scanf("%f",&Science);



    while((getchar())!='\n');

    float SocialScience ;

    printf("\n Social science : ");

    scanf("%f",&SocialScience);

    printf("\n Total marks secured:");

    while((getchar())!='\n');

    float marks;

    marks=Mathematics+English+Hindi+Science+SocialScience;





    if (marks>=450 && marks<=500){

        printf("\ngradeA");

    }

    else if(marks>=400 && marks<=449){

        printf("\ngradeB");

    }

    else if (marks>=350 && marks<=399){

        printf("\ngradeC");

    }

    else if(marks>=300 && marks<=349){

        printf("\ngradeD");

    }

    else if (marks>=200 && marks<=299){

        printf("\ngradeE");

    }

    else if(marks>=0&& marks<=200){

        printf("\ngradeF");

    }

    else

        printf("\n invalid marks");

    printf("\n--------------------------------");

    return 0;

}
