#include<stdio.h>
#include<conio.h>
int main()
{
    int ans,score=0;
    char choice,name[20];
    printf("\t\t\t\t WELCOME TO QUIZ GAME\n\t\t\t\t||||||||||||||||||||||\n\t\t\t\t----------------------\n\n\n");
    printf("\t\t\t\tEnter S FOR START\n \t\t\t\tENTER H FOR HIGH SCORE\n \t\t\t\tENTER I FOR INFORMATION\n \t\t\t\tENTER Q FOR QUIT\n");
    printf("\n\n\t\t\t\t|||||||||||||||||||||||\n\t\t\t\t-----------------------\n");
    getch();
    system("cls");
home:
    printf("\t\t\t\t Give me your choice\n\n");
    scanf("%c",&choice);
    switch(choice){
    case 'I':
    case 'i':
    printf("\n\n\nThis is a very easy game.....\n\nHere we will ask you 10 questions.\n\n You have to answer them.\n\n for each answer 3 pointk will added, And if you are wrong 1 will diducted.\n\n best of luck\n");
    getch();
    system("cls");
    break;
goto home;
    case 'e':
    case 'Ee':
    printf("\n\n\nGOOD BYE,,,,SEE YOU AGAIN\n\n\n HAVE A GOOD DAY\n\n\n");
    getch();
    system("cls");
goto home;
    break;
    case 'h':
    case 'H':
    printf("High score is %d",score);
    getch();
    system("cls");
goto home;
    break;
    default:
    printf("Invalid operation");
    goto home;
    case 'S':
    case 's':
        printf("\t\t\t\t Hellow let's start\n\n");
        printf("\n\n\t\t\t\t|||||||||||||||||||||||\n\t\t\t\t-----------------------\n");
        printf("\n\n\t\t\t\t Enter your name plz\n\n\n");
        scanf("%s",&name);
        printf("hlw %s ,Let's start",name);
        getch();
        system("cls");
        int timecount;
        int timelimit=0;
        int endtime= clock()+30000;
        while( !timelimit && clock() < endtime)
        {
            printf("\n\n\t\t\t\t What is the name of the capital of japan ?\n\n\n\t\t");
            printf("\t\t 1.tokeo  2.dhaka\n\n\t\t\t\t 3.frank  4.new york\n\n");
            scanf("%d",&ans);
            timelimit=1;
            if( clock() < endtime)
            {
                if(ans==1)
                {
                    printf("Correct");
                    score=score+3;
                }
                else
                {
                    printf("SORRY,Wrong ans\t");
                    score=score-1;
                }
                timecount = clock()/1000;
                printf("passing time: %d seconds...",timecount);
                if( timelimit == 1 )
                    printf(" congratulation \n");
                else
                    printf(" time over\t passing time: %d seconds... \n",timecount);
            }

            printf("\n\n\t\t\t\t Bangladesh have how many divisions ?\n\n\n\t\t");
            printf("\t\t 1.65\t\t 2.64\n\n\t\t\t\t 3.66 \t\t 4.67 \n\n");
            scanf("%d",&ans);
            timelimit = 1;
            if( clock() < endtime)
            {
                if(ans==2)
                {
                    printf("Correct");
                    score=score+3;
                }
                else
                {
                    printf("SORRY,Wrong ans\t");
                    score=score-1;
                }
                timecount = clock()/1000;
                printf("passing time: %d seconds...",timecount);
                if( timelimit == 1 )
                    printf(" congratulation \n");
                else
                    printf(" time over\t passing time: %d seconds... \n",timecount);
            }

            printf("\n\n\t\t\t\t What year did Bangladesh finally become independent and gain the nameit has today?\n\n\n\t\t");
            printf("\t\t 1.1947      \t 2.1971\n \t\t\t\t 3.1967     \t 4.1999\n\n");
            scanf("%d",&ans);
            timelimit=1;
            if( clock() < endtime)
            {
                if(ans==1)
                {
                    printf("Correct");
                    score=score+3;
                }
                else
                {
                    printf("SORRY,Wrong ans\t");
                    score=score-1;
                }
                timecount = clock()/1000;
                printf("passing time: %d seconds...",timecount);
                if( timelimit == 1 )
                    printf(" congratulation \n");
                else
                    printf(" time over\t passing time: %d seconds... \n",timecount);
            }

         printf("\n\n\t\t\t What is the natonal flower of Bangladesh\n\n\n\t\t");
            printf("\t\t 1.Water lily   2.Rose\n\t\t\t\t 3.Tulip       4.sun flower \n\n");
            scanf("%d",&ans);
            timelimit=1;
            if( clock() < endtime)
            {
                if(ans==1)
                {
                    printf("Correct");
                    score=score+3;
                }
                else
                {
                    printf("SORRY,Wrong ans\t");
                    score=score-1;
                }
                timecount = clock()/1000;
                printf("passing time: %d seconds...",timecount);
                if( timelimit == 1 )
                    printf(" congratulation \n");
                else
                    printf(" time over\t passing time: %d seconds... \n",timecount);
            }



            printf("\n\n\t\t\t\t What is the name of national parlament of Bangladesh ?\n\n\n\t\t");
            printf("\t 1.Dhaka shangshad \t 2.Bangladesh shangshad\n\t\t\t 3.Jatio shangshad \t 4.razzoshova \n\n");
            scanf("%d",&ans);
            timelimit=1;
            if( clock()<endtime)
            {
                if(ans==3)
                {
                    printf("Correct");
                    score=score+3;
                }
                else
                {
                    printf("SORRY,Wrong ans\t");
                    score=score-1;
                }
                timecount = clock()/1000;
                printf("passing time: %d seconds...",timecount);
                if( timelimit == 1 )
                    printf(" congratulation \n");
                else
                    printf(" time over\t passing time: %d seconds... \n",timecount);
            }
 printf("\n\nYour total score is %d\n\n",score);



        if (score>10)
        {
            printf("\n\n\nExcellent performance\n\n");

        }
        else
        {
            printf("\n\n\n\ntry harder,,,,,you will do better next time\n\n\n\n\n\n");
        }
   if (clock()/1000 <= 30)
                goto home;
   else
            {
                printf("Sorry!! Time out.");

            }

        }
        }





    return 0;
}
