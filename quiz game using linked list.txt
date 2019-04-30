#include<stdio.h>
#include<stdlib.h>
#include <string.h>
typedef struct Node
{
    char name[10];
    int final_score;
    struct Node *next;
} node;
int quiz(int score)
{
    int ans;
    printf("\n\n\t\t\t\t Who is father of C Language?\n\n\n\t\t");
    printf("\t\t 1.Bjarne Stroustrup  2.James A.Gosling\n\n\t\t\t\t 3.Dennis Ritchie     4.Dr.E.F.Codd\n\n");
    printf("\n\t\t\t\tANS:");
    scanf("%d",&ans);
    if(ans==3)
    {
        printf("\nCorrect Ans.Plz press ENTER for Answer next the Qustion! \n\n\n");
        score=score+3;
    }
    else
    {
        printf("\nSORRY,Wrong Ans.Plz press ENTER for Answer the next Qustion! \n\n\n");
        score=score-1;
    }
    system ("PAUSE");
    system("cls");
    printf("\n\n\t\t\t\t C programs are converted into machine language with the help of ?\n\n\n\t\t");
    printf("\t\t 1.An Editor\t\t   2.A compiler\n\n\t\t\t\t 3.An operating system     4.None of these.\n\n");
    printf("\n\t\t\t\tANS:");
    scanf("%d",&ans);
    if(ans==2)
    {
        printf("\nCorrect Ans.Plz press ENTER for Answer next the Qustion! \n\n\n");
        score=score+3;
    }
    else
    {
        printf("\nSORRY,Wrong Ans.Plz press ENTER for Answer the next Qustion! \n\n\n");
        score=score-1;
    }
    system ("PAUSE");
    system("cls");
    printf("\n\n\t\t\t\t A Queue is a ?\n\n\n\t\t");
    printf("\t\t 1.FIFO(First in First out)list\t     2.Ordered array \n\n\t\t\t\t 3.LIFO(Last is Ftrst Out)list\t     4.Linear tree\n\n");
    printf("\n\t\t\t\tANS:");
    scanf("%d",&ans);
    if(ans==1)
    {
        printf("\nCorrect Ans.Plz press ENTER for Answer next the Qustion! \n\n\n");
        score=score+3;
    }
    else
    {
        printf("\nSORRY,Wrong Ans.Plz press ENTER for Answer the next Qustion! \n\n\n");
        score=score-1;
    }
    system ("PAUSE");
    system("cls");
    printf("\n\n\t\t\t\t A Stack is a ?\n\n\n\t\t");
    printf("\t\t 1.FIFO(First in First out)list\t     2.Ordered array \n\n\t\t\t\t 3.LIFO(Last is Ftrst Out)list\t     4.Linear tree\n\n");
    printf("\n\t\t\t\tANS:");
    scanf("%d",&ans);
    if(ans==3)
    {
        printf("\nCorrect Ans.Plz press ENTER for Answer next the Qustion! \n\n\n");
        score=score+3;
    }
    else
    {
        printf("\nSORRY,Wrong Ans.Plz press ENTER for Answer the next Qustion! \n\n\n");
        score=score-1;
    }
    system ("PAUSE");
    system("cls");
    printf("\n\n\t\t\t\t Process of inserting an element in stack is called ?\n\n\n\t\t");
    printf("\t\t 1.Create\t     2.Push\n\n\t\t\t\t 3.Evaluation\t     4.pop\n\n");
    printf("\n\t\t\t\tANS:");
    scanf("%d",&ans);
    if(ans==2)
    {
        printf("\nCorrect Ans.Plz press ENTER for Answer next the Qustion! \n\n\n");
        score=score+3;
    }
    else
    {
        printf("\nSORRY,Wrong Ans.Plz press ENTER for Answer the next Qustion! \n\n\n");
        score=score-1;
    }
    system ("PAUSE");
    system("cls");
    printf("\n\n\t\t\t\t Process of removing an element in stack is called ?\n\n\n\t\t");
    printf("\t\t 1.Create\t     2.Push\n\n\t\t\t\t 3.Evaluation\t     4.pop\n\n");
    printf("\n\t\t\t\tANS:");
    scanf("%d",&ans);
    if(ans==4)
    {
        printf("\nCorrect Ans.Plz press ENTER for Answer next the Qustion! \n\n\n");
        score=score+3;
    }
    else
    {
        printf("\nSORRY,Wrong Ans.Plz press ENTER for Answer the next Qustion! \n\n\n");
        score=score-1;
    }
    system ("PAUSE");
    system("cls");
    printf("\n\n\t\t\t\tIn doubly linked lists, traversal can be performed ?\n\n\n\t\t");
    printf("\t\t 1.Only in forward direction\t     2.In both directions\n\n\t\t\t\t 3.Only in reverse direction\t     4.None\n\n");
    printf("\n\t\t\t\tANS:");
    scanf("%d",&ans);
    if(ans==2)
    {
        printf("\nCorrect Ans.Plz press ENTER for Answer next the Qustion! \n\n\n");
        score=score+3;
    }
    else
    {
        printf("\nSORRY,Wrong Ans.Plz press ENTER for Answer the next Qustion! \n\n\n");
        score=score-1;
    }
    system ("PAUSE");
    system("cls");
    printf("\n\n\t\t\t\tWhat is the time  Complexity of inserting a node in a doubly linked list ?\n\n\n\t\t");
    printf("\t\t 1.O(nlogn)\t     2.O(n)\n\n\t\t\t\t 3.O(logn)\t     4.O(1)\n\n");
    printf("\n\t\t\t\tANS:");
    scanf("%d",&ans);
    if(ans==2)
    {
        printf("\nCorrect Ans.Plz press ENTER for Answer next the Qustion! \n\n\n");
        score=score+3;
    }
    else
    {
        printf("\nSORRY,Wrong Ans.Plz press ENTER for Answer the next Qustion! \n\n\n");
        score=score-1;
    }
    system ("PAUSE");
    system("cls");
    printf("\n\n\t\t\t\tWhat is the time  Complexity of searching for element in a circular linked list ?\n\n\n\t\t");
    printf("\t\t 1.O(nlogn)\t     2.O(1)\n\n\t\t\t\t 3.O(logn)\t     4.O(n)\n\n");
    printf("\n\t\t\t\tANS:");
    scanf("%d",&ans);
    if(ans==4)
    {
        printf("\nCorrect Ans.Plz press ENTER for Answer next the Qustion! \n\n\n");
        score=score+3;
    }
    else
    {
        printf("\nSORRY,Wrong Ans.Plz press ENTER for Answer the next Qustion! \n\n\n");
        score=score-1;
    }
    system ("PAUSE");
    system("cls");
    printf("\n\n\t\t\t\tWhich of the following computer language is used for artificial intelligence?\n\n\n\t\t");
    printf("\t\t 1.FORTRAN\t     2.C\n\n\t\t\t\t 3.PROLOG\t     4.COBOL\n\n");
    printf("\n\t\t\t\tANS:");
    scanf("%d",&ans);
    if(ans==3)
    {
        printf("\nCorrect Ans.Plz press ENTER for Answer next the Qustion! \n\n\n");
        score=score+3;
    }
    else
    {
        printf("\nSORRY,Wrong Ans.Plz press ENTER for Answer the next Qustion! \n\n\n");
        score=score-1;
    }
    system ("PAUSE");
    system("cls");
    return score;

}
void insert(node *point, char name[],int final_score)
{
    while(point->next!=NULL)
    {
        point = point -> next;
    }
    point->next = (node *)malloc(sizeof(node));
    point = point->next;
    strcpy(point->name, name);
    point->final_score = final_score;
    point->next = NULL;
    printf("\n\n\n\n\t\t\t\t\t*** Store information! ***\n\n");
    system ("PAUSE");
    system("cls");

}
void print(node *point)
{
    if(point==NULL)
    {
        return;
    }

    printf("\n\n\t\tName: %s \t\t final_score: %d \n\n\n",point->name,point->final_score);
    print(point->next);

}
void h_print(node *point)
{
    int max_score=point->final_score;
    if (point==NULL)
    {
        return;
    }

    while(point!=NULL)
    {
        if(max_score < point->final_score)
        {
            max_score=point->final_score;
        }
        point=point->next;

    }
    printf("\n\t\thigh_score: %d\n",max_score);
    printf("\n\t\tThank U for attending at quiz. See you again later!\n\n\n");
}
int main()
{
    node *start,*temp;
    char choice,name[20];
    int final_score,score=0,value;
    start = (node *)malloc(sizeof(node));
    temp = start;
    temp -> next = NULL;
    printf("\n\n\n\n\t\t\t\t\t WELCOME TO QUIZ GAME\n\t\t\t\t\t||||||||||||||||||||||\n\t\t\t\t\t----------------------\n\n\n");
    printf("\t\t\t\t\tEnter S | s FOR START\n \t\t\t\t\tENTER I | i FOR INFORMATION\n \t\t\t\t\tENTER Q | q FOR QUIT\n");
    printf("\n\n\t\t\t\t\t|||||||||||||||||||||||\n\t\t\t\t\t-----------------------\n");
    printf("\n\n\t\t\t\t\tGive me your choice:");
    scanf("%c",&choice);
    system("cls");
    if(choice=='S' ||choice=='s' )
    {
        while(1)
        {
            printf("\n\n\t\tpress 1 to get Insert\n");
            printf("\t\tpress 2 to get Result\n");
            printf("\n\n\t\twhat do you want:");
            scanf("%d",&value);
            system("cls");
            switch(value)
            {
            case 1:
                printf("\n\nEnter your name plz:");
                scanf("%s",name);
                printf("\n\nhlw %s ,Let's start ->->\n\n",name);
                final_score=quiz(score);
                insert(start,name,final_score);
                break;

            case 2:
                printf("\n## RESULT: ## ");
                print(start->next);
                printf("\n");
                h_print(start->next);
                printf("\n");
                break;

            default:
                printf("invild selection\n\n");
            }

        }



    }



    else if(choice=='I' ||choice=='i')
    {
        printf("\n\n\n\t\t WELCOME TO QUIZ GAME\n\t\t||||||||||||||||||||||\n\t\t----------------------\n\n\n");
        printf("This is a very easy game.Here we will ask some questions.\nYou have to answer them.for each answer 3 point will added,\nAnd if you are wrong 1 will diducted.best of luck!\n");
        getch();

    }
    else if(choice=='Q' ||choice=='q')
    {
        printf("\n\n\n\n\n\n\n\t\t\t\t|||  GOOD BYE,,,,,SEE YOU AGAIN  |||\n\n\n");
        getch();
    }
    else
    {
        printf("invild selection\n\n");
    }


}



