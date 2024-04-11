# Lab 5 Exercise 6

## Static Class


1. สร้าง console application project

```
dotnet new console --name Lab05_Ex08
```
2. เปลี่ยน code ให้เป็นดังต่อไปนี้

```cs
int x = 2, y = 3;
int add_result = Calculator.add(x, y);
System.Console.WriteLine($"{x} + {y} = {add_result}");

int i = 2, j = 3;
int multiply_result = Calculator.multiply(i, j);
System.Console.WriteLine($"{i} x {j} = {multiply_result}");

public static class Calculator
{
    public static int add(int a, int b)
    {
        return a + b;
    }
    public static int multiply(int a, int b)
    {
        return a * b;
    }
}
```

3. Build project โดยการใช้คำสั่ง

```
dotnet build  Lab05_Ex08
```

4. บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3

5. Run project โดยการใช้คำสั่ง

```
dotnet run --project Lab05_Ex08
```

6. บันทึกผลที่ได้จากการรันคำสั่งในข้อ 5
<img width="960" alt="5 8 1" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-05/assets/144870609/595bc243-6232-4ca0-a51a-261789decc5e">


7. อธิบายสิ่งที่พบในการทดลอง
โปรแกรมจะแสดงผล 2+3=5, 2*3=6 จาก Code ใช้ Class Calculator เป็น static class เพื่อสร้าง method add และ multiply ที่สามารถเรียกใช้ได้

