# Lab 5 Exercise 2

## การประกาศสมาชิกในคลาส (fields)


1. สร้าง console application project

```
dotnet new console --name Lab05_Ex02
```
2. เปลี่ยน code ให้เป็นดังต่อไปนี้

```cs
Person p = new Person();
p.name = "Rambo";
p.id = "1987";
p.income = 2500;
System.Console.WriteLine($"Type of p is {p.GetType()}");
System.Console.WriteLine($"p.name = {p.name}\ttype = {p.name.GetType()}");
System.Console.WriteLine($"p.id = {p.id}\ttype = {p.id.GetType()}");
System.Console.WriteLine($"p.income = {p.income}\ttype = {p.income.GetType()}");

class Person
{
    string name;
    string id;
    int income;
}
```

3. Build project โดยการใช้คำสั่ง

```
dotnet build  Lab05_Ex02
```

4. บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3
<img width="960" alt="5 2 1" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-05/assets/144870609/5aa6c2d6-437f-4988-b2ca-695d0606a66e">

5. Run project โดยการใช้คำสั่ง

```
dotnet run --project Lab05_Ex02
```

6. บันทึกผลที่ได้จากการรันคำสั่งในข้อ 5


7. อธิบายสิ่งที่พบในการทดลอง

โปรแกรม ERROR เพราะไม่ได้กำหนดการเข้าถึง Field ต้องกำหนดเป็น Public ก่อนถึงจะสามารถรันได้
