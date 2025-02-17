---
description: "\U0001F914 Data Scientist เขาเลือก Algorithm ในการแก้ปัญหายังไงกันนะ"
---

# การเลือก Algorithms ให้ AI \(1/5\)

โดยปรกติก่อนที่เราจะเขียน AI ได้ เราจะต้องตั้งโจทย์ก่อนว่า **เราอยากจะแก้ปัญหาเรื่องอะไร?** ซึ่งเชื่อไหมว่าปัญหาทุกปัญหาในวงการนี้มันถูกแบ่งออกเป็นแค่ 5 กลุ่มเท่านั้นเอง ดังนั้นหลักการในการเลือก **Algorithm** นั้นก็แสนจะง่าย เพียงแค่เราดูว่าปัญหาของเรามันไปตรงกับกลุ่มไหน เราก็จะเลือก Algorithms จากกลุ่มนั้นมาลองใช้ แล้วเอาผลลัพท์ที่ดีที่สุดมาใช้เพียงเท่านี้เอง ดังนั้นในรอบนี้เราจะมาทำความเข้าใจ**ปัญหาทั้ง 5 กลุ่มของวงการ AI** กันครัช

{% hint style="success" %}
**แนะนำให้อ่าน**  
บทความนี้เป็นส่วนหนึ่งของบทความ [**👶 Data Scientist**](https://saladpuk.gitbook.io/learn/basic/data-scientist) หากเพื่อนๆสนใจอยากรู้หลักการของพวก Data science ทั้งหมดแนะนำให้ไปอ่านบทความหลักได้โดยการจิ้มชื่อสีฟ้าๆนั้นเลยนะครับ ส่วนใครที่อยากลองสร้าง AI เป็นของตัวเองก็สามารถดูตัวอย่างได้จากบทความด้านล่างนี้ครับ  
[**สร้าง AI ตัดสินใจอนุมัติบัตรเครดิต 💳**](https://saladpuk.gitbook.io/learn/cloud/machine-learning-studio/credit-risk)\*\*\*\*
{% endhint %}

## 🔥 ถามหาคำตอบเป็น A หรือ B

![](../../.gitbook/assets/image%20%28375%29.png)

เวลาที่เราต้องการจะสร้าง AI ที่ต้องตอบ**คำถามที่มีคำตอบเพียง 2 คำตอบ** เช่น เป็นหมาหรือแมว, ชอบหรือไม่ชอบ, เป็นเพศชายหรือเพศหญิง ไรงี้ และรวมถึง**คำถามที่มีคำตอบมากกว่า 2 คำตอบ**ด้วย เช่น หน้าตาดีหรือหน้าตาธรรมดาหรือหน้าตาขี้เหร่, เป็น A หรือ B หรือ C หรือ D ... Z บลาๆ ซึ่งถ้าเราเจอโจทย์ที่ถามลักษณะนี้ แสดงว่าเราต้องเลือกใช้ Algorithm ในหมวดที่ชื่อว่า **`Classification`** นั่นเอง

{% hint style="info" %}
**คำถามที่มีคำตอบเพียง 2 ข้อ**  
จะอยู่ในหมวด **Classification** และมีกลุ่มย่อยเป็นตระกูล **Two-class classification**
{% endhint %}

เราลองไปดูกลุ่มของ **Two-class classification algorithms** กันบ้างนะว่ามีอะไรให้เล่นบ้าง ซึ่งให้ไล่จากกจุดเหลืองๆว่าโจทย์ของเราตรงกับลักษณะไหน ก็ให้เลือกใช้ algorithm ตัวนั้นได้เลย

![](../../.gitbook/assets/image%20%287%29.png)

{% hint style="info" %}
**คำถามที่มีคำตอบมากกว่า 2 ข้อ**  
จะอยู่ในหมวด **Classification** และมีกลุ่มย่อยเป็นตระกูล **Multi-class classification**
{% endhint %}

เราลองไปดูกลุ่ม **Multi-class classification algorithms** กันบ้างนะว่ามีอะไรให้เล่นบ้าง ซึ่งให้ไล่จากกจุดเหลืองๆว่าโจทย์ของเราตรงกับลักษณะไหน ก็ให้เลือกใช้ algorithm ตัวนั้นได้เลย

![](../../.gitbook/assets/image%20%28266%29.png)

## 🔥 ถามหาของที่ผิดปรกติ

![](../../.gitbook/assets/image%20%28420%29.png)

เวลาที่เราต้องการจะสร้าง AI ที่ต้องหาว่ามันมีของที่ผิดปรกติอยู่ในนั้นหรือเปล่า เช่น การใช้จ่ายเงินมีอะไรผิดแปลกไปหรือเปล่า, มีการโกงบัญชีเกิดขึ้นหรือเปล่า, เซ็นเซอร์ต่างๆยังทำงานเป็นปรกติดีหรือเปล่า บลาๆ ซึ่งถ้าเราเจอโจทย์ที่ถามลักษณะนี้ แสดงว่าเราต้องเลือกใช้ Algorithm ในหมวดที่ชื่อว่า **`Anomaly detection`** นั่นเอง

เราลองไปดูกลุ่ม **Anomaly detection** กันบ้างนะว่ามีอะไรให้เล่นบ้าง ซึ่งให้ไล่จากกจุดเหลืองๆว่าโจทย์ของเราตรงกับลักษณะไหน ก็ให้เลือกใช้ algorithm ตัวนั้นได้เลย

![](../../.gitbook/assets/image%20%28371%29.png)

## 🔥 ถามหาตัวเลข

![](../../.gitbook/assets/image%20%28196%29.png)

เวลาที่เราต้องการจะสร้าง AI ที่ต้องหาคำตอบเป็นตัวเลข เช่น อุณหภูมิพรุ่งนี้จะเป็นยังไง, หุ้นมีโอกาสจะขึ้นกี่เปอร์เซ็นต์, ราคาควรจะเป็นเท่าไหร่ บลาๆ ซึ่งถ้าเราเจอโจทย์ที่ถามลักษณะนี้ แสดงว่าเราต้องเลือกใช้ Algorithm ในหมวดที่ชื่อว่า **`Regression`** นั่นเอง

เราลองไปดูกลุ่ม **Regression** กันบ้างนะว่ามีอะไรให้เล่นบ้าง ซึ่งให้ไล่จากกจุดเหลืองๆว่าโจทย์ของเราตรงกับลักษณะไหน ก็ให้เลือกใช้ algorithm ตัวนั้นได้เลย

![](../../.gitbook/assets/image%20%28187%29.png)

## 🔥 ถามหาว่ามันอยู่กลุ่มไหน

![](../../.gitbook/assets/image%20%28165%29.png)

เวลาที่เราต้องการจะสร้าง AI ที่ต้องหาว่าของพวกนั้นมันควรจะจัดไว้กลุ่มไหน เช่น เป็นหนังแนวไหน, อาการป่วยแบบนี้อยู่ในระยะไหน, สัตว์แบบนี้อยู่ในตระกูลไหน โดยในบางครั้งเราอาจจะไม่รู้ด้วยซ้ำว่ามันจะมีกลุ่มอะไรบ้าง แล้วเราอยากให้คอม AI แบ่งกลุ่มออกมาให้ก็รวมอยู่ในนี้ด้วย ซึ่งถ้าเราเจอโจทย์ที่ถามลักษณะนี้ แสดงว่าเราต้องเลือกใช้ Algorithm ในหมวดที่ชื่อว่า **`Clustering`** นั่นเอง

เราลองไปดูกลุ่ม **Clustering** กันบ้างนะว่ามีอะไรให้เล่นบ้าง \(มีอยู่อันเดียว\)

![&#xE40;&#xE2B;&#xE07;&#xE32;&#xE08;&#xE38;&#xE07;](../../.gitbook/assets/image%20%28283%29.png)

## 🔥 ถามว่าต้องตัดสินใจทำอะไรต่อ

![](../../.gitbook/assets/image%20%28347%29.png)

เวลาที่เราต้องการจะสร้าง AI ที่ต้องหาว่าถ้าเราได้ผลลัพท์ออกมาแบบนี้ แล้วเราจะต้องทำอะไรต่อดี เช่น รถกำลังวิ่งด้วยความเร็วเท่านี้แล้วเห็นทางเลี้ยวควรทำอะไรต่อดี, น้ำขึ้นถึงระดับนี้แล้วควรทำอะไรต่อดี, ไม่มีคนอยู่บ้านแล้วควรทำอะไรต่อดี บลาๆ ซึ่งถ้าเราเจอโจทย์ที่ถามลักษณะนี้ แสดงว่าเราต้องเลือกใช้ Algorithm ในหมวดที่ชื่อว่า **`Reinforcement Learning`** นั่นเอง 

ลักษณะของ **Reinforcement Leaning** จะต้องใช้ผลลัพท์ของขั้นตอนก่อนหน้ามาเป็น input เพื่อใช้ในการตัดสินใจว่าควรจะต้องทำอะไรต่อ ซึ่งในตอนที่เขียนบทความนี้ Machine Learning Studio นั้นยังไม่มี algorithms ในหมวดนี้ออกมาให้เราใช้งานครับ

## 🤔 มีแบบสรุปสรุปสั้นๆเลยไหม ?

ถ้าบทความนี้ยังสรุปไม่สั้นสะใจพอ เอาแผนผังการเลือก Algorithms นี่ไปดูเลย

{% file src="../../.gitbook/assets/ml-algorithm-cheat-sheet.pdf" caption="Algorithm cheat sheet" %}

ส่วนอันนี้เป็นการเลือก Algorithm แบบเป็น Infographic

{% file src="../../.gitbook/assets/ml-infographic-algorithms.pdf" caption="Algorithms infographic" %}

## 🎯 บทสรุป

เราก็จะเห็นว่าจริงๆแล้วการเลือกใช้ Algorithms ให้กับ AI นั้นไม่ได้ยากอะไรเลย เพียงแค่ดูว่าปัญหาที่เราต้องการจะแก้ มันไปตรงกับหมวดไหน แล้วเราก็แค่เลือก algorithms ที่ตรงกับลักษณะของ data ที่เรามีก็พอ เพียงเ่ทานี้เราก็จะสามารถเลือก Algorithms ได้แบบง่ายๆแล้วครับ

