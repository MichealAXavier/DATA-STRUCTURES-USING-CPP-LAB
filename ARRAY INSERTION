// C++ Program to Insert an element at a specific position in an Array

#include <iostream.h>
#include<conio.h>

// Function to insert x in arr at position given; remember array index starts at 0;
int *insertion(int datacount, int array_insert[], int insertdata, int position)
{
    int i;
    // increase the size by 1 since one data is to inserted
datacount++;
    // shift elements forward
    for (i = datacount; i>= position; i--)
array_insert[i] = array_insert[i - 1];

    // insert newdata at position
array_insert[position - 1] = insertdata;
    return array_insert;
}
void traverse(int datacount,int array_insert[])
    {
	for (int i = 0; i<datacount; i++)
cout<<array_insert[i] << " "<<endl;
    }

void main()
{
    clrscr();
    int array_insert[100] = { 0 };
    int i, insertdata, position, datacount = 10;

    // initial array of size 10
    for (i = 0; i< 10; i++)
array_insert[i] = i + 1;
cout<<endl<<"Array before insertion"<<endl;// display purpose

    // print the original array
traverse(datacount, array_insert);

    // element to be inserted
insertdata = 50;

    // position at which element is to be inserted
    position = 5;
cout<<endl<<"Array after inserting the element 50 at position 5"<<endl;// display purpose

    // Insert data at the given position
insertion(datacount, array_insert, insertdata, position);

    // print the updated array
    traverse(datacount,array_insert);
    getch();
}
