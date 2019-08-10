# ps2asciikeyboard
Arduino ascii keyboard.

Send the codes like an ASCII keyboard.

So you can copy and paste program to Apple I or Apple II/II+ .

Add ps2 keyboard support.


const int DataPin = 12;

const int IRQpin =  3;

int ASCII0 = 7;

int ASCII1 = 8;

int ASCII2 = 11;

int ASCII3 = 5;

int ASCII4 = 4;

int ASCII5 = 6;

int ASCII6 = 2;

int STROBE = 10;

int NRESET = 9; //reset active low

int LED = 13;
