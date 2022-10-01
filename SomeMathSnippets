Code Snippet for Math Operations to use in projects when .NET won't work across platforms

// [...]
                if (myOperator == 0) {
                    //values holds the numbers you need to add up
                    //result is the variable that holds the answer to the sum

                    for (int addend = 0; addend < values.Length; addend++)
                    {
                        result += values[addend];
                    }
                }
 
                // Subtraction

                if (myOperator == 1)
                {
                    result = values[0];
                    for (int subtrahend = 1; subtrahend < values.Length; subtrahend++)
                    {
                        result -= values[subtrahend];
                    }
                }

                //Multiplication
                if (myOperator == 2 || myOperator == 5)
                {
                    result = 1;
                    for (int multiplier = 0; multiplier < values.Length; multiplier++)
                    {
                        result *= values[multiplier];
                    }
                } 

                //Division
                if (myOperator == 3 || myOperator == 6)
                {
                    result = values[0];
                    for (int divisor = 1; divisor < values.Length; divisor++)
                    {
                        result /= values[divisor];
                    }

                }
                //Averaging
                if (myOperator == 7)
                {
                    for (int addend2 = 0; addend2 < values.Length; addend2++)
                    {
                        result += values[addend2];
                    }
                    result /= values.Length;
                }

                //Powers
                if (myOperator == 8) 
                {
                    result = Exponentation(values[0], values[1]);
                }

                //Factorials
                if (myOperator == 9)
                {
                    result = 1;
                            for (int factorial = 1; factorial < values[0]+1; factorial++) 
                            { 
                                result *= factorial;
                                Debug.Log(factorial);
                                Debug.Log(result);
                            }
                }



//      [...]


    public float Exponentation(float myBase, float myPower)
    {
        float result = 1;

        if (myPower > 0)
        {
            for (int i = 1; i <= myPower; ++i)
            {
                result *= myBase;
            }
        }
        else if (myPower < 0)
        {
            for (int i = -1; i >= myPower; --i)
            {
                result /= myBase;
            }
        }

        return result;
    }                
