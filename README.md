#include <iostream>
#include <fstream>
using namespace std;
 
int main()
{
    int x,y,z,i;
    ifstream f("xyz.in");
    ofstream g("xyz.out");
    f>>x>>y>>z;
    for (i=1;i<x;i++)
        y=y*10+z;
    g<<y;
    return 0;
