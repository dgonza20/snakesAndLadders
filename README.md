/******************************************************************************

Welcome to GDB Online.
GDB online is an online compiler and debugger tool for C, C++, Python, Java, PHP, Ruby, Perl,
Pascal, Fortran, Haskell, Objective-C, Assembly, HTML, CSS, JS, SQLite, Prolog.
Code, Compile, Run and Debug online from anywhere in world.

*******************************************************************************/
#include <stdio.h>
// ConsoleApplication1.cpp : Defines the entry point for the console application.
//

// ChutesAndLadders.cpp.cpp : Defines the entry point for the console application.
//
//#include "stdafx.h
#include <iostream>
#include <cstring>
#include <cmath>
#include <cstdlib>
#include <ctime>


//#include "studio.h"
//#include <Windows.h>
using namespace std;
//void startScreen();
//char gameBoard();              // make another class related to movement
//void diceRoll();
//void playerMove();               // dont know about this one, this might be inclusive of if we want to show motion
								//void endScreen();
								//void checkChutes();
								//void checkLadders();
								//int numPlayers[i];

														//the players gamepeice information
	void gamePiece(int &totalPlayers) {
        char startgame;
		char playerCharacter[totalPlayers];
		cout << " how many players are there?"<< endl;
		cin >> totalPlayers;
	/*	while(startgame != 'y'){
		for (int a= 0;a<totalPlayers;++a){
		    playerCharacter[a]={*/
		    /*
		switch (totalPlayers) {														//sets the game peices for the number of players
		case 2:
			playerCharacter[totalPlayers] = { 'A','B' };
			gamestart = 'y';
			break;
		case 3:
			playerCharacter[totalPlayers] = { 'A','B','C' };
			gamestart = 'y';
			break;
		case 4:
			playerCharacter[totalPlayers] = { 'A','B','C','D' };
		    gamestart = 'y';
		    
		}
		default 0;
		    cout << "enter a valid input..." << endl;
		    
	}*/
}
int main() {

	string player[totalPlayers];              											//playerOne through playerFour (how applicable)
	int gameStart;
	int i, j, k, l, m;
	const int height = 5;
	const int width = 17;
													     							// I was planning on making the start screen look like some thing
																					//straight out the 80s it would look like an actual main Menu from
	for (i = 0; i < totalPlayers; ++i) {   											//like zelda, or doom. if we do the research, it shouldnt take more
		getline(cin, player[i]);       												//than a few hours to write and i think would really complete our
	}              																	//code in terms of looks and style. let me know what you guys think
																					//of that    
	char map[height][width];
																					//initializes the gameboard
																					//gameboard map array
	for (int j = 0; j < height; ++j) {          									//{|_|_|_|_|_|_|_|_|}
		for (int k = 0; k < width; ++k) {      										//{|_|_|_|_|_|_|_|_|}
			if (k % 2 == 1) {      													//{|_|_|_|_|_|_|_|_|}
				map[j][k] = '_';                 									//{|_|_|_|_|_|_|_|}
			}              															//{|_|_|_|_|_|_|_|}
			if (k % 2 == 0) {
				map[j][k] = '|';
			}
		}
	}
	i = 0;
    int currNumSpaces = 0;
    while(playerCoor[i][j] != map[Xfinal][yfinal]){
	    while((playerCurrPos[i][j] + (2(numSpaces - currNumSpaces)+1)) != xEnd) && (numSpaces != 0)){
		    i = 2i + 1;
		    currNumSpaces = numSpaces - i;
		    playerCoor[i][j] = { 40 - (2i + 1) }, { j };
		    snakes();
		ladders();
	for (j = 0; j < height; ++j) {
		for (k = 0; k < width; ++k) {
			cout << map[j][k];
		}
		cout << endl;
	}
	
	void startScreen(int numPlayers, int gameStart);
	cout << "please enter players' names:" << endl;
	playerChar::gamePiece

		
	int xEnd=4;
	int yEnd=16;
	
		
		if(map[xEnd][yEnd] == playerCoor[][]){
			


	while (gameRunning == 'y'&& gameWin = 0) {										//snakes and ladders main body; iterates through the number of players  
		for (l = 0; l<numPlayers; ++l) {
		while (map[0][16] != playerCharacter[l]) {												//until a winner is found. then the game ends
			
				cout << player[j] << ": Its your turn." << endl;
				void diceRoll();
				void playerMove();
				void snakes(playerChar[numPlayers]);
				void ladders(playerChar[numPlayers]);
			}
		}
		void endScreen();
		return 0;
	}

	void startScreen(int& playerNum, char& gameRunning);
	cout << " would you like to play snkaes and ladders?"
	switch(gameRunning){
		case 'y':
			cout << "Thank You, and welcome to Snakes and Ladders" << endl;	
			cout << "A Potato 1 production" << endl;								// note: get that dub is the choice the
}                																	// user makes on whether to play the greatest game in
																					//the world, chutes and ladders
int diceRoll() {
	srand(time(0));
	int numspaces;																	// the value of the diceroll is a random number between 
	numspaces = (rand() % 6) + 1;													//1 & 6. this will be genertated and outputed as the 
																					//number of spaces the player moves. this doesn't define
	return numspaces;																//the 	
}
void playerMove(int V, int H) {
	int numSpaces;
	if (numSpaces != 0 && map[
	void snakes(int& player, int& board) {											//gives the reference coordinates for each "snake" 
		if (player == board[5][16]) {												//that when a player lands on the given coordinate
			player = board[1][10];													// it will move the player back to a specified 
		}																			//location somewhere else on the board
		if (player == board[4][3]) {												// note: there are three snakes for the board
			player = board[3][2];
		}

		if (player == board[2][13]) {
			player = board[1][3];
		}
	}
	void ladders(int& player, int& board) {											//gives the reference coordinates for each "ladder"
		if (player == board[1][2]) {												//that when a player lands on the given coordinate
			player = board[4][13];													// it will move the player forward to a specified 
		}																			//location somewhere else on the board
		if (player == board[3][12]) {												//note: there are three ladders for the board
			player = board[5][10];
		}
		if (player == board[2][3]) {
			player = board[4][5];
		}



	}
	return 0;
}

        
# snakesAndLadders
snakes and ladders
