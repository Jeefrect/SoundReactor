# Creating Kino Objects with KeyShapes and Sound Reactor

Suppose you have a ready 3D model of a subwoofer that you want to animate.

<img width="1919" height="1024" alt="image" src="https://github.com/user-attachments/assets/ab65ef17-6e3d-426d-b641-e8714a65fc03" />


---

## 1. Add a base shape
In **Blender**, select your object and go to the **Data Properties** tab (triangle icon).  
Find the **Shape Keys** panel and press **`+`** once.  
This will create a **Basis** key - it stores the original (default) geometry of the object.

<img width="1078" height="681" alt="image" src="https://github.com/user-attachments/assets/a6f57e9d-7fc6-456d-9f7a-d953334bf2b1" />


---

## 2. Create a new shape key
Press **`+`** again. A new shape key will appear (e.g. *Key 1*).  
On this key you can edit the mesh (move vertices, scale, deform, etc.).  

The **Value** slider of the shape key will blend between:
- **0.0** → the Basis (original) shape
- **1.0** → the modified shape


https://github.com/user-attachments/assets/ba850199-fbe4-432c-8dda-196d1447a1b3


---

## 3. Add more keys
You can add as many shape keys as you want.  
**Sound Reactor automatically detects all of them.**  

Each key can be linked to different audio bands (**Low**, **Mid**, **High**, or **Volume**).  
Keys can also blend together, which allows you to create more advanced effects — for example lip-sync or organic animations, not just a simple "on/off" movement.  

---

## ✅ Done
Just save your the object in FBX format and create the kino object as you normally would.
