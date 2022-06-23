### EX.NO: 05

### DATE :


## JaggedArray

## Aim:
To write a C# program to create a sample CPU usage on a network with 4 nodes using a jagged array.

## Algorithm:

### Step1:
Start.

### Step2:
Declare a Jagged Array for four element.

### Step3:
Initialize the elements.

### Step4:
Accessing the elements.

### Step5:
Stop.


## Program:

```python3 

using System;
class CPUactivity
{
    public static void Main(String[] args)
    {
        int[][] array = new int[4][];
        array[0] = new int[3];
        array[1] = new int[5];
        array[2] = new int[6];
        array[3] = new int[4];
        for(int i = 0; i < 4; i++)
        {
            for (int j = 0; j <array[i].Length; j++)
            {
                array[i][j] = i * j + 70;
            }
        }
        for(int i = 0; i < array.Length; i++)
        {
            for(int j = 0; j <array[i].Length; j++)
            {
                Console.WriteLine("CPU usage at node" + "is" +array[i][j] +"%");
                
            }
            Console.WriteLine();
        }
    }
}

```


## Output:

![image](https://user-images.githubusercontent.com/81132849/167238933-463ec746-c713-46fc-bb71-9364c20cf4f5.png)


## Result:


Thus, the C# program to create a sample CPU usage on a network with 4 nodes using a jagged array is executed successfully.
