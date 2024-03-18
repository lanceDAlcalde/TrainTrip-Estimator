
    /* Title:            TRAIN TRIP ESTIMATOR */

    /* Programmer:       LANCE KERWIN D. ALCALDE */

    /* Student Number;   20230183-M */

    /* Date:             December 9 2023 */

   #define Station1 21
   #define Fare1 21
   #define Station2 14
   #define Fare2 14
   #define Station3 14
   #define Fare3 14
   #include<stdio.h>
   #include<conio.h>

    // station names for LRT-1
    char*  LRT1_stations[] = {"error!","Baclaran","EDSA","Libertad","Gil Puyat","Vito Cruz","Quirino","Pedro Gil","UN Avenue","Central","Carriedo", "D.Jose", "Bambang", "Tayuman", "Blumentritt", "Abad Santos", "R.Papa", "5th Avenue", "Monumento", "Balintawak", "Fernando jr"};

    // station names for LRT-2
    char* LRT2_stations[] = {"error!","Recto","Legarda","Pureza","V.Ruiz","J.Cruz","Gilmore","Belmonte","Araneta Center","Anonas","Katipunan","Santolan","Marikina","Antipolo"};

    // station names for MRT-3
    char* MRT3_Stations[] = {"error!","North Ave","Quezon Ave","Kamuning","Cubao","Santolan","Ortigas","Shaw","Boni","Guadalupe","Buendia","Ayala","Magallanes","Taft"};

    // function for TRAINMENU display
    void displaymenu(){
    gotoxy(18,7);
    textcolor(LIGHTGRAY);
    cprintf ("\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2 TRAIN TRIP ESTIMATOR \xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2");
    gotoxy(34,9);
    textcolor(YELLOW);
    cprintf ("\xB2 [1] LRT-1\n");
    gotoxy(34,10);
    textcolor(MAGENTA);
    cprintf ("\xB2 [2] LRT-2\n");
    gotoxy(34,11);
    textcolor(CYAN);
    cprintf ("\xB2 [3] MRT-3\n");
    gotoxy(18,13);
    textcolor(LIGHTGRAY);
    cprintf ("\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2");
    }

    // function for LRT-1 display
    void lrt1fareMatrix(){
    clrscr();
    textcolor(YELLOW);
    cprintf("  \xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2 LRT-1 SINGLE JOURNEY FARE MATRIX \xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\n");
    textcolor(LIGHTGRAY);
    cprintf("    [1]Baclaran      0  15 15 20 20 20 20 20 25 25 25 25 25 30 30 30 30 30 35 35");
    cprintf("    [2]EDSA          15 0  15 15 20 20 20 20 25 25 25 25 25 25 30 30 30 30 35 35");
    cprintf("    [3]Libertad      15 15 0  15 15 20 20 20 20 25 25 25 25 25 25 30 30 30 35 35");
    cprintf("    [4]Gil Puyat     20 15 25 0  15 20 20 20 20 20 25 25 25 25 25 25 30 30 30 35");
    cprintf("    [5]Vito Cruz     20 20 15 15 0  15 15 20 20 20 20 20 25 25 25 25 25 30 30 35");
    cprintf("    [6]Quirino       20 20 20 20 15 0  15 15 20 20 20 20 20 25 25 25 25 25 30 30");
    cprintf("    [7]Pedro Gil     20 20 20 20 15 15 0  15 20 20 20 20 20 20 25 25 25 25 30 30");
    cprintf("    [8]UN Avenue     20 20 20 20 20 15 15 0  15 20 20 20 20 20 20 25 25 25 30 30");
    cprintf("    [9]Central       25 25 20 20 20 20 20 15 0  15 15 20 20 20 20 20 20 25 25 30");
    cprintf("    [10]Carriedo     25 25 25 20 20 20 20 20 15 0  15 15 20 20 20 20 20 25 25 30");
    cprintf("    [11]D.Jose       25 25 25 25 20 20 20 20 15 15 0  15 15 20 20 20 20 20 25 25");
    cprintf("    [12]Bambang      25 25 25 25 20 20 20 20 20 15 15 0  15 15 20 20 20 20 25 25");
    cprintf("    [13]Tayuman      25 25 25 25 25 20 20 20 20 20 15 15 0  15 15 20 20 20 25 25");
    cprintf("    [14]Blumentritt  30 25 25 25 25 25 20 20 20 20 20 15 15 0  15 15 20 20 20 25");
    cprintf("    [15]Abad Santos  30 30 25 25 25 25 25 20 20 20 20 20 15 15 0  15 15 20 20 25");
    cprintf("    [16]R.Papa       30 30 30 25 25 25 25 25 20 20 20 20 20 15 15 0  15 20 20 25");
    cprintf("    [17]5th Avenue   30 30 30 30 25 25 25 25 20 20 20 20 20 20 15 15 0  15 20 20");
    cprintf("    [18]Monumento    30 30 30 30 30 25 25 25 25 25 20 20 20 20 20 20 15 0  20 20");
    cprintf("    [19]Balintawak   35 35 35 30 30 30 30 30 25 25 25 25 25 20 20 20 20 20 0  20");
    cprintf("    [20]Fernando jr  35 35 35 35 35 30 30 30 30 30 25 25 25 25 25 25 20 20 20 0 ");
    textcolor(YELLOW);
    cprintf("    \xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\n");
    }

    // function for LRT-2 display
    void lrt2fareMatrix(){
    clrscr();
    textcolor(MAGENTA);
    cprintf(" \n\n\n             \xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2 LRT-2 SINGLE JOURNEY FARE MATRIX \xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\n");
    textcolor(LIGHTGRAY);
    cprintf("                        [1]Recto          0  15 20 20 20 25 25 25 25 30 30 35 35 ");
    cprintf("                       [2]Legarda        15 0  15 20 20 20 25 25 25 25 30 30 35 ");
    cprintf("                       [3]Pureza         20 15 0  15 20 20 20 20 25 25 30 30 30 ");
    cprintf("                       [4]V.Ruiz         20 20 20 0  15 15 20 20 20 20 25 25 30 ");
    cprintf("                       [5]J.Cruz         20 20 20 15 0  15 20 20 20 20 25 25 30 ");
    cprintf("                       [6]Gilmore        25 20 20 20 15 0  15 20 20 20 25 25 30 ");
    cprintf("                       [7]Belmonte       25 25 20 20 20 15 0  15 20 20 20 25 25 ");
    cprintf("                       [8]Araneta Center 25 25 20 20 20 20 15 0  15 20 20 25 25 ");
    cprintf("                       [9]Anonas         25 25 25 20 20 20 20 15 0  15 20 20 25 ");
    cprintf("                       [10]Katipunan     30 25 25 25 20 20 20 20 15 0  20 20 20 ");
    cprintf("                       [11]Santolan      30 30 30 25 25 25 20 20 20 20 0  15 20 ");
    cprintf("                       [12]Marikina      30 30 30 30 25 25 25 25 20 20 15 0  20 ");
    cprintf("                       [13]Antipolo      35 35 30 30 30 30 25 25 25 20 20 20 0  \n");
    textcolor(MAGENTA);
    cprintf("                       \xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xb2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\n");
    }

    //function for MRT-3 display
    void mrt3fareMatrix(){
    clrscr();
    textcolor(CYAN);
    cprintf("\n\n\n             \xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2 MRT-3 SINGLE JOURNEY FARE MATRIX \xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\n");
    textcolor(LIGHTGRAY);
    cprintf("                        [1]North Ave    0  13 13 16 16 20 20 20 24 24 24 28 28 ");
    printf("                         [2]Quezon Ave   13 0  13 13 16 16 20 20 20 24 24 24 28 ");
    printf("                         [3]Kamuning     13 13 0  13 13 16 16 20 20 20 24 24 24 ");
    printf("                         [4]Cubao        16 13 13 0  13 13 16 16 20 20 20 24 24 ");
    printf("                         [5]Santolan     16 16 13 13 0  13 13 16 16 20 20 20 24 ");
    printf("                         [6]Ortigas      20 16 16 13 13 0  13 13 16 16 20 20 20 ");
    printf("                         [7]Shaw         20 20 16 16 13 13 0  13 13 16 16 20 20 ");
    printf("                         [8]Boni         20 20 20 16 16 13 13 0  13 13 16 16 20 ");
    printf("                         [9]Guadalupe    24 20 20 20 16 16 13 13 0  13 13 16 16 ");
    printf("                         [10]Buendia     24 24 20 20 20 16 16 13 13 0  13 13 16 ");
    printf("                         [11]Ayala       24 24 24 20 20 20 16 16 13 13 0  13 13 ");
    printf("                         [12]Magallanes  28 24 24 24 20 20 20 16 16 13 13 0  13 ");
    printf("                         [13]Taft        28 28 24 24 24 20 20 20 16 16 13 13 0\n");
    textcolor(CYAN);
    cprintf("             \xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xb2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\xB2\n");
    }
    //function for TRAINMENU
    int menu(){
    int matrix;
    do{
    clrscr();
    displaymenu();
    gotoxy(34,15);
    textcolor(LIGHTGRAY);
    printf ("Enter mode: ");scanf("%d", &matrix);
    if (matrix != 1 && matrix != 2 && matrix != 3){
    printf("\t\t\tInvalid input. Try again"); }
    } while ( matrix != 1 && matrix != 2 && matrix != 3);
    return matrix; }

    // function for LRT-1 SINGLE JOURNEY FARE MATRIX
    int LRT_1(int totalLRT2fare, int totalMRT3fare){
    int st1, fr1, toLRT2, toMRT3, trainmenu, value, matrix;
    int loop;
    int totalLRT1fare = 0;

    int LRT1[Station1][Fare1] = {
	{0},
	{1,0,15,15,20,20,20,20,20,25,25,25,25,25,30,30,30,30,30,35,35,},
	{2,15,0,15,20,20,20,20,25,25,25,25,25,25,30,30,30,30,35,35},
	{3,15,15,0,15,20,20,20,20,25,25,25,25,25,25,30,30,30,30,35,35},
	{4,20,15,15,0,15,20,20,20,20,20,25,25,25,25,25,25,30,30,30,35},
	{5,20,20,15,15,0,15,15,20,20,20,20,20,25,25,25,25,25,30,30,35},
	{6,20,20,20,20,15,0,15,15,20,20,20,20,20,25,25,25,25,25,30,30},
	{7,20,20,20,20,15,15,0,15,20,20,20,20,20,20,25,25,25,25,30,30},
	{8,20,20,20,20,20,15,15,0,15,20,20,20,20,20,20,25,25,25,30,30},
	{9,25,25,20,20,20,20,20,15,0,15,15,20,20,20,20,20,20,25,25,30},
	{10,25,25,25,20,20,20,20,20,15,0,15,15,20,20,20,20,20,25,25,30},
	{11,25,25,25,25,20,20,20,20,15,15,0,15,15,20,20,20,20,20,25,25},
	{12,25,25,25,25,20,20,20,20,20,15,15,0,15,15,20,20,20,20,25,25},
	{13,25,25,25,25,25,20,20,20,20,20,15,15,0,15,15,20,20,20,25,25},
	{14,30,25,25,25,25,25,20,20,20,20,20,15,15,0,15,15,20,20,20,25},
	{15,30,30,25,25,25,25,25,20,20,20,20,20,15,15,0,15,15,20,20,25},
	{16,30,30,30,25,25,25,25,25,20,20,20,20,20,15,15,0,15,20,20,25},
	{17,30,30,30,30,25,25,25,25,20,20,20,20,20,20,15,15,0,15,20,20},
	{18,30,30,30,30,30,25,25,25,25,25,20,20,20,20,20,20,15,0,20,20},
	{19,35,35,35,30,30,30,30,30,25,25,25,25,25,20,20,20,20,20,0,20},
	{20,35,35,35,35,35,30,30,30,30,30,25,25,25,25,25,25,20,20,20,0}
    };

    while ( loop != 1){
    lrt1fareMatrix();
    textcolor(LIGHTGRAY);
    cprintf("   Enter your start station:  ");
    scanf ("%d", &st1);
    if (st1 <= 0 || st1 >= 21) {// alignment of station name
	cprintf(" Invalid start station index. Try again.\n");
	continue; }
    printf("  Start Station: %s\n", LRT1_stations[st1]);
    printf("  Enter your end station:  ");
    scanf ("%d", &fr1);
     if (fr1 <= 0 || fr1 >= 21) {// alignment of station name
	printf("Invalid end station index. Try again.\n");
	continue; }
    textcolor(LIGHTGRAY);
    printf("  End Station: %s\n", LRT1_stations[fr1]);
    if (st1 >= 1 && st1 <= 20  && fr1 >= 1 && fr1 <= 20){//alignment of station
	value = LRT1[st1][fr1];
	totalLRT1fare += totalMRT3fare + totalLRT2fare + value;
	printf("  Fare :: %d\n", value);

    if (st1 == fr1){ printf("  Your in the same station No travel needed!\n"); }
    if (fr1 == 11) { printf("  [1]proceed to LRT-1 | [2]proceed to LRT-2 ::  ");scanf("%d", &toLRT2);//for D.JOSE to LRT-2
    if (toLRT2 == 1){ continue; }// back to start and end station input
    if (toLRT2 == 2){ LRT_2(totalLRT1fare, totalMRT3fare); return 0;} // proceed to LRT-2
    }

    if (fr1 == 2) { printf("  [1]proceed to LRT-1 | [2]proceed to MRT-3 ::  ");scanf("%d", &toMRT3);//for EDSA to MRT-3
    if (toMRT3 == 1) { continue; }// back to start and End input
    if (toMRT3 == 2) { MRT_3(totalLRT1fare, totalLRT2fare); return 0; } //proceed to MRT-3
    }

    if (fr1 == 20) { printf("  [1]proceed to LRT-1 | [2]proceed to MRT-3 ::  ");scanf("%d", &toMRT3);//for F.POE  to MRT-3
    if (toMRT3 == 1) { continue; }// back to start and End input
    if (toMRT3 == 2) { MRT_3(totalLRT1fare, totalLRT2fare); return 0; } //proceed to MRT-3
    }   textcolor(LIGHTGRAY);
	cprintf("              [PRESS ANY KEY] exit | [1] proceed | [2] estimate ::  ");// choices for proceeding
	scanf("%i", &loop);
    if (loop != 0 && loop != 1 && loop != 2) { printf("\nInvalid input"); exit(0); }// back to start and and input
    if (loop == 0){ printf ("exiting...(press any key)"); exit(0); }// exit program
    } else { printf ("  The station you're trying to go is not align in LRT-1. try again"); continue; }// if the input is not align

    do{// main looping for next station
    clrscr();
    lrt1fareMatrix();
    if (loop == 1) {
	lrt1fareMatrix();
	st1 = fr1;
	printf("   You're currently in: %s station\n", LRT1_stations[st1]);// station name
	printf("  Enter your next station:  ");scanf("%d", &fr1);// input user for NEW END STATION
	printf("  Next Station: %s\n", LRT1_stations[fr1]);// display name of next station

    if (st1 >= 1 && st1 <= 20  && fr1 >= 1 && fr1 <= 20){// alignment of station
	value = LRT1[st1][fr1];// get the fare of two stations
	totalLRT1fare += totalMRT3fare + totalLRT2fare + value;// add every fare of station
	printf("  Fare:: %d\n", value);//display fare of every stations

    if (st1 == fr1){ printf("  Your in the same station No travel needed!\n"); }// display for same station
    if (fr1 == 11) { printf("  [1]proceed to LRT-1 | [2]proceed to LRT-2 ::  ");scanf("%d", &toLRT2);//for D.JOSE to LRT-2
    if (toLRT2 == 1){ continue; }
    if (toLRT2 == 2){ LRT_2(totalLRT1fare, totalMRT3fare); return 0;}
    }
    if (fr1 == 2) { printf("  [1]proceed to LRT-1 | [2]proceed to MRT-3 ::  ");scanf("%d", &toMRT3);//for EDSA to MRT-3
    if (toMRT3 == 1) { continue; }
    if (toMRT3 == 2) { MRT_3(totalLRT1fare, totalLRT2fare); return 0;  }
    }
    if (fr1 == 20) { printf("  [1]proceed to LRT-1 | [2]proceed to MRT-3 ::  ");scanf("%d", &toMRT3);//for F.POE  to MRT-3
    if (toMRT3 == 1) { continue; }
    if (toMRT3 == 2) { MRT_3(totalLRT1fare, totalLRT2fare); return 0; }
    }           textcolor(LIGHTGRAY);
	cprintf("                [PRESS ANY KEY]exit | [1]proceed | [2]estimate ::  ");// choices for proceeding
	scanf("%i", &loop);
    if (loop != 0 && loop != 1 && loop != 2) { printf("Invalid input. Try again"); exit(0); }// back to start and and input
    if (loop == 0){ printf ("exiting...(press any key)"); exit(0); } //exit program
    } else { printf ("The station you're trying to go is not align. try again"); continue; } }// back to end input
    if (loop == 2){
	clrscr();
	textcolor(LIGHTGRAY);
	cprintf("\nThe estimated fare for your trip is :: %d", totalLRT1fare);//display of estimated fare for trip in LRT-1
	totalLRT1fare = 0;
	cprintf("                                       [0]exit | [1]new trip ::  ");// choices  for making new trip
	scanf("%d", &trainmenu);
    if (trainmenu != 0 && trainmenu != 1 ) { printf("invalid input"); }// alignment input
    if (trainmenu == 0 ) { printf("exiting...(press any key)"); exit(0); }// exit program
    if (trainmenu == 1) {// proceeding to TRAINMENU
    loop = 1;
    return 0; } }
      } while ( loop == 1 );
    }
 return 0; }

    // function for LRT-2 SINGLE JOURNEY FARE MATRIX
    int LRT_2(int totalLRT1fare, int totalMRT3fare){
    int st2, fr2, loop, trainmenu, value, matrix;
    int totalLRT2fare = 0;
    int toLRT1,toMRT3;
    int LRT2[Station2][Fare2] = {
		     {0},
		     {1,0 ,15,20,20,20,25,25,25,25,30,30,35,35},
		     {2,15,0 ,15,20,20,20,25,25,25,25,30,30,35},
		     {3,20,15,0 ,15,20,20,20,20,25,25,30,30,30},
		     {4,20,20,20,0 ,15,15,20,20,20,20,25,25,30},
		     {5,20,20,20,15,0 ,15,20,20,20,20,25,25,30},
		     {6,25,20,20,20,15,0 ,15,20,20,20,25,25,30},
		     {7,25,25,20,20,20,15,0 ,15,20,20,20,25,25},
		     {8,25,25,20,20,20,20,15,0 ,15,20,20,25,25},
		     {9,25,25,25,20,20,20,20,15,0 ,15,20,20,25},
		     {10,30,25,25,25,20,20,20,20,15,0 ,20,20,20},
		     {11,30,30,30,25,25,25,20,20,20,20,0 ,15,20},
		     {12,30,30,30,30,25,25,25,25,20,20,15,0 ,20},
		     {13,35,35,30,30,30,30,25,25,25,20,20,20,0 },
		     };
    while( loop != 1){
    clrscr();
    lrt2fareMatrix();
    gotoxy(21,30);
    textcolor(LIGHTGRAY);
    cprintf("                        Enter your start station: ");
    scanf ("%d", &st2);
    if (st2 <= 0 || st2 >= 14) {
	printf("              Invalid start station index. Try again.\n");
	continue; }// alignment of station name
    printf("              Start Station: %s\n", LRT2_stations[st2]);
    cprintf("              Enter your end station:  ");
    scanf ("%d", &fr2);
    if (fr2 <= 0 || fr2 >= 14) {// alignment of station name
	    printf("              Invalid end station index. Try again.\n");
	    continue; }
    printf("              End Station: %s\n", LRT2_stations[fr2]);
    if (st2 >= 1 && st2 <= 13  && fr2 >= 1 && fr2 <= 13){
	 value = LRT2[st2][fr2];
	 totalLRT2fare += totalMRT3fare + totalLRT1fare + value;

	cprintf("              Fare:: %d\n", value);
    if (st2 == fr2){ printf("              Your in the same station No travel needed!\n"); }
    if (fr2 == 1) { printf("                   [1]proceed to LRT-2 | [2]proceed to LRT-1 ::  ");scanf("%d", &toLRT1);//for RECTO to LRT-1
    if (toLRT1 == 1){ continue; }
    if (toLRT1 == 2){ LRT_1(totalLRT2fare, totalMRT3fare); return 0;}
    }
    if (fr2 == 8) { printf("                   [1]proceed to LRT-2 | [2]proceed to MRT-3 ::  ");scanf("%d", &toMRT3); //for ARANETA to MRT-3
    if (toMRT3 == 1){ continue; }
    if (toMRT3 == 2){ MRT_3(totalLRT1fare, totalLRT2fare); return 0;}
    }
    printf("[PRESS ANY KEY]exit | [1]proceed | [2]estimate ::  ");
	scanf("%i", &loop);
    if (loop != 0 && loop != 1 && loop != 2) { printf("Invalid input. Try again"); exit(0); }
    if (loop == 0){ printf ("exiting...(press any key)"); exit(0); } }

    do {

    if (loop == 1) {
	lrt2fareMatrix();
	st2 = fr2;
	textcolor(MAGENTA);
	cprintf("                        You're currently in: %s station", LRT2_stations[st2]);
	textcolor(LIGHTGRAY);
	cprintf("                                             Enter your next station:  ");scanf("%d", &fr2);
	printf("              End Station: %s\n", LRT2_stations[fr2]);
    if (st2 >= 1 && st2 <= 13  && fr2 >= 1 && fr2 <= 13){
	value = LRT2[st2][fr2];
	 totalLRT2fare += totalMRT3fare + totalLRT1fare + value;
	 printf("              Fare :: %d\n", value);
    if (fr2 == 1) { printf("             [1]proceed to LRT-2 | [2]proceed to LRT-1 ::  ");scanf("%d", &toLRT1);//for RECTO to LRT-1
    if (toLRT1 == 1){ continue; }
    if (toLRT1 == 2){ LRT_1(totalLRT2fare, totalMRT3fare); return 0;}
    }
    if (fr2 == 8) { printf("             [1]proceed to LRT-2 | [2]proceed to MRT-3 ::  ");scanf("%d", &toMRT3); //for ARANETA to MRT-3
    if (toMRT3 == 1){ continue; }
    if (toMRT3 == 2){ MRT_3(totalLRT1fare, totalLRT2fare); return 0;}
    }
    if (st2 == fr2){ printf("              Your in the same station No travel needed!\n"); }
	printf("                 [PRESS ANY KEY]exit | [1]proceed | [2]estimate ::  ");
	scanf("%i", &loop);
    if (loop != 0 && loop != 1 && loop != 2) { printf("Invalid input. Try again"); exit(0); }
    if (loop == 0){ printf ("exiting...(press any key)"); exit(0); }
    } else { printf ("The station you're trying to go is not align. try again"); continue; } }
    if (loop == 2){
	clrscr();
	printf("\nThe estimated fare for your trip is :: %d\n", totalLRT2fare);
	totalLRT2fare = 0;
	printf("\n[0]exit | [1]new trip ::  ");
	scanf("%d", &trainmenu);
    if (trainmenu != 0 && trainmenu != 1 ) { printf("invalid input"); }
    if (trainmenu == 0 ) { printf("exiting...(press any key)"); exit(0); }
    if (trainmenu == 1) {
    loop = 1;
    return 0; } }
      } while ( loop == 1 );
    }
 return 0; }

    // Function for MRT-3 SINGLE JOURNEY FARE MATRIX
    int MRT_3(int totalLRT1fare, int totalLRT2fare){
    int st3, fr3, loop, trainmenu, value, matrix;
    int toLRT2, toLRT1;
    int totalMRT3fare = 0;
    int MRT3[Station3][Fare3] = {
				 {0},
				 {1,0,13,16,16,20,20,20,20,24,24,24,28,28},
				 {2,13,0,13,13,16,16,20,20,20,24,24,24,28},
				 {3,13,13,0,13,13,16,16,20,20,20,24,24,24},
				 {4,16,13,13,0,13,13,16,16,20,20,20,24,24},
				 {5,16,16,13,13,0,13,13,16,16,20,20,20,24},
				 {6,20,16,16,13,13,0,13,13,16,16,20,20,20},
				 {7,20,20,16,16,13,13,0,13,13,16,16,20,20},
				 {8,20,20,20,16,16,13,13,0,13,13,16,16,20},
				 {9,24,20,20,20,16,16,13,13,0,13,13,16,16},
				 {10,24,24,20,20,20,16,16,13,13,0,13,13,16},
				 {11,24,24,24,20,20,20,16,16,13,13,0,13,13},
				 {12,28,24,24,24,20,20,20,16,16,13,13,0,13},
				 {13,28,28,24,24,24,20,20,20,16,16,13,13,0}
				};

    while ( loop != 1){
    clrscr();
    mrt3fareMatrix();
    textcolor(LIGHTGRAY);
    cprintf("                        Enter your start station: ");
    scanf ("%d", &st3);
    if (st3 <= 0 || st3 >= 14) {
	    printf("Invalid end station index. Try again.\n");
	    continue; }
    printf("             Start Station: %s\n", MRT3_Stations[st3]);
    printf("             Enter your end station: ");
    scanf ("%d", &fr3);
    if (fr3 <= 0 || fr3 >= 14) {// alignment of station name
	    printf("Invalid end station index. Try again.\n");
	    continue; }
    printf("             End Station: %s\n", MRT3_Stations[fr3]);
    if (st3 >= 1 && st3 <= 13  && fr3 >= 1 && fr3 <= 13){
	value = MRT3[st3][fr3];
	totalMRT3fare += totalLRT2fare + totalLRT1fare + value;
	printf("             Fare: %d\n", value);
    if (st3 == fr3){ printf("             Your in the same station No travel needed!\n"); }
    if (fr3 == 4) { printf("             [1]proceed to MRT-3 | [2]proceed to LRT-2 ::  ");scanf("%d", &toLRT2);//for CUBAO to LRT-2(Araneta Center)
    if (toLRT2 == 1){ continue; }// back to start and end station input
    if (toLRT2 == 2){ LRT_2(totalLRT1fare, totalMRT3fare); return 0;} // proceed to LRT-2
    }
    if (fr3 == 1) { printf("             [1]proceed to MRT-3 | [2]proceed to LRT-1 ::  ");scanf("%d", &toLRT1);//for N.AVE to LRT-1(ROOSEVELT)
    if (toLRT1 == 1){ continue; }// back to start and end station input
    if (toLRT1 == 2){ LRT_1(totalLRT2fare, totalMRT3fare); return 0;} // proceed to LRT-1
    }
    if (fr3 == 13) { printf("            [1]proceed to MRT-3 | [2]proceed to LRT-1 ::  ");scanf("%d", &toLRT1);//for TAFT to LRT-1(EDSA)
    if (toLRT1 == 1){ continue; }// back to start and end station input
    if (toLRT1 == 2){ LRT_1(totalLRT2fare, totalMRT3fare); return 0;} // proceed to LRT-1
    }
	printf("                  [PRESS ANY KEY]exit | [1]proceed | [2]estimate ::  ");
	scanf("%i", &loop);
    if (loop != 0 && loop != 1 && loop != 2) { printf("Invalid input. Try again");  exit(0);}
    if (loop == 0){ printf ("exiting...(press any key)"); exit(0); } }

    do{

    if (loop == 1) { mrt3fareMatrix();
	st3 = fr3;
	textcolor(CYAN);
	cprintf("                        You're currently in %s station", MRT3_Stations[st3]);
	textcolor(LIGHTGRAY);
	cprintf("                                            Enter your next station: ");scanf("%d", &fr3);
	printf("             End Station: %s\n", MRT3_Stations[fr3]);
    if (st3 >= 1 && st3 <= 13  && fr3 >= 1 && fr3 <= 13){
	value = MRT3[st3][fr3];
	totalMRT3fare += totalLRT2fare + totalLRT1fare + value;
	 printf("             Fare: %d\n", value);
    if (st3 == fr3){ printf("             Your in the same station No travel needed!\n"); }
    if (fr3 == 4) { printf("             [1]proceed to MRT-3 | [2]proceed to LRT-2 : ");scanf("%d", &toLRT2);//for CUBAO to LRT-2(Araneta Center)
    if (toLRT2 == 1){ continue; }// back to start and end station input
    if (toLRT2 == 2){ LRT_2(totalLRT1fare, totalMRT3fare); return 0;} // proceed to LRT-2
    }
    if (fr3 == 1) { printf("             [1]proceed to MRT-3 | [2]proceed to LRT-1: ");scanf("%d", &toLRT1);//for N.AVE to LRT-1(ROOSEVELT)
    if (toLRT1 == 1){ continue; }// back to start and end station input
    if (toLRT1 == 2){ LRT_1(totalLRT2fare, totalMRT3fare); return 0;} // proceed to LRT-1
    }
    if (fr3 == 13) { printf("            [1]proceed to MRT-3 | [2]proceed to LRT-1: ");scanf("%d", &toLRT1);//for TAFT to LRT-1(EDSA)
    if (toLRT1 == 1){ continue; }// back to start and end station input
    if (toLRT1 == 2){ LRT_1(totalLRT2fare, totalMRT3fare); return 0;} // proceed to LRT-1
    }
	printf("                  [0]exit | [1]proceed | [2]estimate: ");
	scanf("%i", &loop);
    if (loop != 0 && loop != 1 && loop != 2) { printf("Invalid input. Try again");  exit(0);}
    if (loop == 0){ printf ("exiting...(press any key)"); exit(0); }
    } else { printf ("The station you're trying to go is not align. try again"); continue; } }
    if (loop == 2){
	clrscr();
	printf("\nThe estimated fare for your trip is: %d\n", totalMRT3fare);
	totalMRT3fare = 0;
	printf("\n[0]exit | [1]new trip: ");
	scanf("%d", &trainmenu);
    if (trainmenu != 0 && trainmenu != 1 ) { printf("invalid input"); }
    if (trainmenu == 0) { printf("exiting...(press any key)"); exit(0); }//exit program
    if (trainmenu == 1) {
    loop = 1;
    return 0;}// back to menu
	}
      } while ( loop == 1 );
    }
 return 0; }

    // Main function
    int main(){
    int matrix = 0;//variable for menu function
    int trainService;// Variable to store the chosen train service
    int totalLRT1fare = 0;
    int totalLRT2fare = 0;
    int totalMRT3fare = 0;

    do {
	trainService = menu();
	switch (trainService) {
	    case 1:

		matrix = LRT_1(totalLRT2fare, totalMRT3fare);
		break;

	    case 2:

	       matrix = LRT_2(totalLRT1fare, totalMRT3fare);
		break;

	    case 3:

		matrix = MRT_3(totalLRT1fare, totalLRT2fare);
		break;

	    default:
		return 0;
	}
      } while (matrix == 0);

    return 0;
}
