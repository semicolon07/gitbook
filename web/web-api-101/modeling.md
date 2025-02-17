# 6.การใช้ Model

💬 ถ้าเราเริ่มเขียน API ไปได้ซักพักเราจะเริ่มรู้สึกหงุดหงิดกับ parameters ที่ใช้รับส่งกันของ API \(หรือผมเป็นอยู่คนเดียวหว่า\) เช่น ถ้าผมต้องการรับข้อมูลนักเรียน ผมก็ต้องเขียน parameter ให้เป็นตามโค๊ดด้านล่าง ซึ่งมันไม่สนุกเลยถ้าข้อมูลนักเรียนมีเยอะมากจริงๆ ดังนั้นในรอบนี้เราจะลองใช้ **model** มาช่วยในการทำงานที่ตรงกับ programming ยุคนี้กัน

```csharp
[HttpPost("{id}/{name}/{age}")]
public void CreateNewStudent(string id, string name, int age)
{
  // Do something
}
```

{% embed url="https://www.youtube.com/watch?v=apWi2ku4tME&list=PLUjAn8nwWniheN3OLy6i7xu1VYq4Tzj7p&index=6" %}

## 🎯 สรุปสั้นๆ

### 👨‍🚀 ข้อดีในการนำ model มาช่วย

1. ลดความวุ่นวายของโค๊ดลง
2. จัดการโค๊ดได้เป็นสัดเป็นส่วนมากขึ้น
3. เวลาแก้ไข แก้แค่ที่เดียว แล้วทุดจุดที่ใช้ model นั้นๆก็จะถูกแก้ไปด้วย

{% hint style="info" %}
**JSON**  
เวลาที่ตัว Web API มันส่งข้อมูลหากัน มันจะส่งข้อมูลผ่านไปในรูปแบบที่เรียกว่า JSON \(เจสัน หรือ เจซอน ก็ได้อ่านได้ทั้งสองสำเนียง\) ซึ่งอยู่ในรูปแบบของ text ซึงสามารถดูตัวอย่างของ JSON ได้จากตัวอย่างด้านล่างครับ
{% endhint %}

{% hint style="warning" %}
ข้อมูลที่ส่งผ่าน Web API ไม่จำเป็นต้องเป็น JSON เสมอไปนะครับ ขึ้นอยู่กับ protocol ที่กำหนดไว้ครับ
{% endhint %}

### 👨‍🚀 ตัวอย่างข้อมูลในรูปของ object และ JSON

สมมุติว่าเรามีข้อมูลในรูปของ object เป็นภาพนี้

```csharp
Student s1 = new Student
{
  Id = "S01",
  Name = "Sakul",
  Age = 18
};
```

พอเราส่งข้อมูล object นั้นออกมาสู่โลกของ Web API ซึ่งอยู่ในรูปแบบของ JSON เราจะได้มันออกมาเป็นตามด้านล่างครับ

```javascript
{
  "id": "S01",
  "Name": "Sakul",
  "Age": 18
}
```

