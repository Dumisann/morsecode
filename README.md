# morsecode
#include <iostream>
#include <cctype> // for using toupper
#include <algorithm> // for transform

using namespace std;

int main()
{
	string message; // stores the etire message
	string morsecode;
	string letter;
	
string A,B,C,D,E,F,G,H,I,J,K,L,M,N,O,P,Q,R,S,T,U,V,W,X,Y,Z;
A=".-";
B="-...";
C="-.-.";
D="-..";
E=".";
F="..-.";
G="--.";
H="....";
I="..";
J=".---";
K="-.-";
L=".-..";
M="--";
N="-.";
O="---";
P=".--.";
Q="--.-";
R=".-.";
S="...";
T="-";
U="..-";
V="...-";
W=".--";
X="-..-";
Y="-.--";
Z="--..";

cout << "Enter a message in english" << "\n";
getline(cin,message);  // this input line includes the spaces,

transform(message.begin(),message.end(),message.begin(),
			::toupper); // convert all user input to uppercase
			
for (int i=0; i<= int(message.length());i++)
{
	letter = message.substr(i,1);
	
if (letter == "A")
	{
		cout << "A:" << A << "\n";
		morsecode += A;
		morsecode += "  ";
	}
	
if (letter == "B")
	{
		cout << "B:" << B << "\n";
		morsecode += B;
		morsecode += "  ";
	}

if (letter == "C")
	{
		cout << "C:" << C << "\n";
		morsecode += C;
		morsecode += "  ";
	}		

if (letter == "D")
	{
		cout << "D:" << D << "\n";
		morsecode += D;
		morsecode += "  ";
	}
		
if (letter == "E")
	{
		cout << "E:" << E << "\n";
		morsecode += E;
		morsecode += "  ";
	}

if (letter == "F")
	{
		cout << "F:" << F << "\n";
		morsecode += F;
		morsecode += "  ";
	}
	
if (letter == "G")
	{
		cout << "G:" << G << "\n";
		morsecode += G;
		morsecode += "  ";
	}	
	
if (letter == "H")
	{
		cout << "H:" << H << "\n";
		morsecode += H;
		morsecode += "  ";
	}	
	
if (letter == "I")
	{
		cout << "I:" << I << "\n";
		morsecode += I;
		morsecode += "  ";
	}	
	
if (letter == "J")
	{
		cout << "J:" << J << "\n";
		morsecode += J;
		morsecode += "  ";
	}	

if (letter == "K")
	{
		cout << "K:" << K << "\n";
		morsecode += K;
		morsecode += "  ";
	}

if (letter == "L")
	{
		cout << "L:" << L << "\n";
		morsecode += L;
		morsecode += "  ";
	}

if (letter == "M")
	{
		cout << "M:" << M << "\n";
		morsecode += M;
		morsecode += "  ";
	}

if (letter == "N")
	{
		cout << "N:" << N << "\n";
		morsecode += N;
		morsecode += "  ";
	}

if (letter == "O")
	{
		cout << "O:" << O << "\n";
		morsecode += O;
		morsecode += "  ";
	}

if (letter == "P")
	{
		cout << "P:" << A << "\n";
		morsecode += P;
		morsecode += "  ";
	}

if (letter == "Q")
	{
		cout << "Q:" << Q << "\n";
		morsecode += Q;
		morsecode += "  ";
	}

if (letter == "R")
	{
		cout << "R:" << R << "\n";
		morsecode += R;
		morsecode += "  ";
	}

if (letter == "S")
	{
		cout << "S:" << S << "\n";
		morsecode += S;
		morsecode += "  ";
	}

if (letter == "T")
	{
		cout << "T:" << T << "\n";
		morsecode += T;
		morsecode += "  ";
	}

if (letter == "U")
	{
		cout << "U:" << U << "\n";
		morsecode += U;
		morsecode += "  ";
	}

if (letter == "V")
	{
		cout << "V:" << V << "\n";
		morsecode += V;
		morsecode += "  ";
	}

if (letter == "W")
	{
		cout << "W:" << W << "\n";
		morsecode += W;
		morsecode += "  ";
	}

if (letter == "X")
	{
		cout << "X:" << X << "\n";
		morsecode += X;
		morsecode += "  ";
	}

if (letter == "Y")
	{
		cout << "Y:" << Y << "\n";
		morsecode += Y;
		morsecode += "  ";
	}

if (letter == "Z")
	{
		cout << "Z:" << Z << "\n";
		morsecode += Z;
		morsecode += "   ";
	}



}

cout << "Full Morse Code Message: " << morsecode;



}
#################################################################################################33


#include <iostream>

using namespace std;

int main()
{
float kiloOhms,current,voltage,resistance,omhs; 
int selection;
 cout<<("1. convert kiloOhms to ohms")<<"\n";
 cout<<("2. calculate current")<<"\n";
 cout<<("3. calculate resistance")<<"\;n";
 cout<<("4. calculate voltage")<<"\n";
 cout<<("5. close")<<"\n";
 
if(selection==1)
{
	cout<<"Enter the kiloOhms : \n";
	cin>> kiloOhms;
	cout<<("kiloOhms*1000")<<
	} 
if(selection==2)
{
	cout<<"Enter the voltage :\n";
	cin>> voltage;
	cout<<"Enter the resistance : \n";
	cin>> resistance;
	cout<<("voltage / resistance \n");
	}	
if(selection==3)
{
	cout<<"Enter the voltage : \n";
	cin>> voltage;
	cout<<"Enter the current : \n";
	cin>> current;
	cout <<"(voltage/current)\n"
	} 
	
if (selection==4)
{
	cout<<"Enter the current :\n";
	cin>>current;
	cout<<"Enter the resistance : \n"
	cin>> resistance;
	cout<<("current*resistance");
	
if (selection==5)
{
	cout<<
	}	
	
	}	


return 0;
}
##########################################################################################################333

#include <iostream>
using namespace std ;

void greeting(); // global variables
void add();
void diff();
void multiply();
void divide();

int total,a,b;

int main()

{
	int n;
	greeting();
	total =0;
	
	
	for (n=1;n<=5;n++)
	{
	cout<<"Enter number 1:";
	cin>> a;
	
	cout<< "Enter number 2:";
	cin>> b;
	add();
	diff();
	multiply();
	divide();
	
	}

return 0;

}  //main program code

void greeting()

{
	cout<< "Hello"<<endl;
	cout<< "Welcome to the program"<< endl;
	
	}
	
void add()
{
	total = a + b;
	cout<<"The total is : "<<total<<endl;
	}	
	
void diff()
{
	int subtract; // local variable
	subtract = a - b;
	cout<<"The difference is : "<< subtract<<endl;
	}	
	
void multiply()
{
	int multiply;
	multiply = a * b;
	cout << "The answer is : "<< multiply<< endl;
	
	}
	
void divide()
{
	int divide;
	divide = a / b ;
	cout<< "The answer is :"<< divide<< endl;
	}	

