# choose-a-food.c
choosing your food based on a choice that you enter between 1 to 5
{
    int choice;
    printf("enter your choice\n so that i will choose an item for you to eat\n");
    scanf("%d",&choice);
    switch(choice)
    {
        case 1 : printf("have a pizza , cost is239");
        break;
        case 2: printf("have a burger , cost is 129 ");
        break;
        case 3 : printf("have a pasta, cost is 179");
        break;
        case 4 : printf("have a frenchfries , cost is 99");
        break;
        case 5 : printf("have a sandwitch, cost is 149");
        break;
        default:printf("invalid choice");
        
    }
    return 0;
    
}
