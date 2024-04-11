# Lab 5 Exercise 1

## การสร้าง Class


1. สร้าง console application project

```
dotnet new console --name Lab05_Ex01
```
2. เปลี่ยน code ให้เป็นดังต่อไปนี้

```cs
Person p = new Person();
System.Console.WriteLine($"Type of p is {p.GetType()}");

class Person
{

}
```

3. Build project โดยการใช้คำสั่ง

```
dotnet build  Lab05_Ex01
```

4. บันทึกผลที่ได้จากการรันคำสั่งในข้อ 3
<img width="960" alt="5 1 1" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-05/assets/144870609/699998a2-a99e-4414-a25c-d606871dba5c">

5. Run project โดยการใช้คำสั่ง

```
dotnet run --project Lab05_Ex01
```

6. บันทึกผลที่ได้จากการรันคำสั่งในข้อ 5


7. อธิบายสิ่งที่พบในการทดลอง
โปรแกรมแสดงข้อความ Type of p is Person ใน Code กรณี Person คือ คลาสที่ไม่มีอะไรภาย แต่โปรแกรมไม่ฟ้อง ERROR

