

































































































//Miguel Fletes
//10/16/15
// Math Tutor 2


char menu()
{
    char ans;
    cout << "Which math operation tutoring would you like to start:\n addition(type 'a')\n subtraction(type 's')\n multiplication(type 'm')\n division(type 'n')\n or to quit program type 'q')" << endl;
    cin >> ans;
    
    while((ans < 'a') || (ans > 'z'))
    {
        cout << "Please type an appropriate option:\n addition(type 'a')\n subtraction(type 's')\n multiplication(type 'm')\n division(type 'n')\n or to quit program type 'q')" << endl;
        cin >> ans;
    }
    
    return ans;  
}

void multi(int valA, int valB, int& runningScore)
{
    runningScore = 0;
    int count = 0;
    int product, userAns;
    for(int i = 0; i < 6; i++)
    {
        randNum(valA, valB);
        product = valA * valB;
        cout << "What is " << valA << " * " << valB << " equal to: ";
        cin >> userAns;
        if(product == userAns)
        {
            compliment();
            count++;
            runningScore++;
        }
        else
        {
            encouragement();
        }
    }
    cout << "You got " << count << " problems correct.";
}
