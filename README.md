![ha ganna with 3d printed shoe](https://github.com/user-attachments/assets/c07dc04c-ff55-4b3c-8450-d411163b5286)

## Background

Kumiko is a labor-intensive Japanese woodworking technique that involves assembling wooden lattices and small strips cut at precise angles to form geometric patterns. With my introductory knowledge of kumiko, I believed cutting these small wooden strips was the  bottleneck of the kumiko-making process.

When learning about different methods of making these small kumiko *leafs*, the most common approach seemed to be using a ([jig and chisel setup](https://www.youtube.com/watch?v=zId1w-6QfYw&ab_channel=JohnnyTromboukis%28JTWoodworks%29)) to cut pieces at the required angles. However, this method seemed impractical for scaling up production, especially if I wanted to create the large kumiko panels that I admired.

There are very few resources available on making kumiko ([ha ganna planes](https://www.youtube.com/watch?v=-NuqwJz9RNE&ab_channel=%E7%AB%B9%E4%B8%AD%E5%A4%A7%E5%B7%A5%E9%81%93%E5%85%B7%E9%A4%A8)), but one particularly valuable blog post from ([Big Sand Woodworking](https://www.bigsandwoodworking.com/ha-ganna-%E8%91%89%E9%89%8B-making-dai/)) provided insight into the process. In my opinion, this was the only valuable English resource online discussing ha-ganna planes, and without it, I would have never attempted to try kumiko. With these ha-ganna planes, making large kumiko panels seemed for feasible, but how does one acquire or make these planes if no one sells them (at a reasonable price)?

In his blog, Jon describes the process of chiseling out the *dai* to embed specialty kumiko blades. As a novice woodworker, I knew this level of precision was beyond my skill set as I can really only make straight cuts with a table saw. Still determined to try kumiko, I wanted to find a compromise: making most of the *dai* from wood while 3D printing a sleeve to hold the blade.  This blog mentions a shop in Japan that sells kumiko blades, **[Pro Shop Hokuto](https://www5e.biglobe.ne.jp/~ttoishi/sumurai.index.html)**. So, I went and bought thier four available kumiko blades and started planning.
 
![image](https://github.com/user-attachments/assets/d407cb57-fe6d-4c60-b314-a0cb37ff7478)
*Left: from [JT Woodworks](https://www.youtube.com/watch?v=BUaQEjO0qOw&ab_channel=JohnnyTromboukis%28JTWoodworks%29) making 1 leaf at a time. Right: from [Tanihata](https://www.youtube.com/watch?v=VyLIOfhaLms&t=3s&ab_channel=%E7%AB%B9%E4%B8%AD%E5%A4%A7%E5%B7%A5%E9%81%93%E5%85%B7%E9%A4%A8) making multiple leafs at a time

## The Kumiko Sleeve

The sleeves are 3D printed in **PETG**, a common 3D printing material that is tougher and more forgiving than alternatives like PLA. This flexibility is useful since it allows the blade to dig into the material without fracturing.

Initially, the sleeve was designed as a **one-piece part**, but I later split it into **two halves** to make it easier to assemble and disassemble the blade. The two halves are held together by **four countersunk M4 screws**, which thread into **four pressed-in threaded inserts**. The inner two threaded inserts also serve to secure the sleeve to the main *dai*.

![unexploded shoe](https://github.com/user-attachments/assets/02a4e559-d27f-475a-b210-59c85874bac5)
![exploded shoe](https://github.com/user-attachments/assets/192cfbe0-efa4-4184-ae05-b7ea895c70ff)

## The Dai

I feel like 3D printing a tool like this is already a shortcut, so I resisted the idea of printing the entire *ha-ganna* plane. It didn’t feel right. I wanted most of the tool to be made from wood, so that when using it, I would primarily be touching wood.

The *dai* and fence are designed to be as simple as possible. The main body is a **rectangular block with a cutout** to fit the sleeve. The height of the *dai* is **greater than the sleeve height**, allowing for depth adjustments when cutting kumiko pieces. Slotted holes provide additional height adjustments.

![unexploded all](https://github.com/user-attachments/assets/d3809e8a-787d-46bf-98ce-5103159e0b5a)
![exploded all](https://github.com/user-attachments/assets/694ccc46-b9c5-4c09-9adf-8cd14eb4c454)

I made one key modification to the **fence** compared to standard *ha-ganna* designs: I **removed material from the inner section**. Since my *dai* is wider than usual to accommodate the 3D-printed sleeve, it was ergonomically difficult to use. Removing material from the fence improved the grip and handling.
![image](https://github.com/user-attachments/assets/db0390a5-b56a-4af8-abfd-c91d47d70c21)

To improve ergonomics, I also sanded down any edges of the *dai* that would come into contact with my hands.

I don't believe these blades are manufactured precisely the same. I went through an iterative process to get the angles right for my specific set of blades. These files should serve as a guideline on how to 3D print a sleeve to make ha-ganna planes, and fine-tuning is almost certainly necessary for each set of blades.   



