#include<bits/stdc++.h> 

int main()
{
    //variables
    int count = 0;
    int n = 0;
    
    //User input 
    std::cout << "Enter a postive number" << std::endl;
    std::cin >> n;
    
    //calculate size of array
    int SIZE = (n * 2);
    
    //Create array of size 2 * n
    int Arr[SIZE];
    
    //check if input is valid
    if (n <= 0)
    throw std::invalid_argument("invalid input");
    
    //Add ones and zeros to the array to represent white and black circles 
    for (int i = 0; i < SIZE; i++)
    {
        if (i % 2 == 0)
        {
            Arr[i] = 0;
        }
        else
        {
            Arr[i] = 1;
        }
    }
    
    
    
    // Sorting the array using bubble sort
    for (int j = 0; j < SIZE; j++)
    {
        for (int i = 0; i < (SIZE - 1 ); i++)
        {
            if (Arr[i + 1] < Arr[i])
            {
                std::swap(Arr[i + 1], Arr[i]);
                count++;
            
            }
        }
    }
    
    //Display elements in the array
    for (int i = 0; i < SIZE; i++) 
    {
        std::cout << Arr[i] << ' ';
    }
    
    //Display count 
    std::cout << std::endl;
    std::cout << "count : " << count << std::endl;
 
   
    return 0;
}
