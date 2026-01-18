
Although the market is constantly introducing games with complex graphics, minimalist game genres like Flappy Bird remain a classic case study for researching software architecture and real-time event processing workflows.

******Regarding Software Architecture******
* Rigorously applying **Object-Oriented Programming (OOP)** to manage object classes such as Characters, Obstacles, and Items. This ensures **Inheritance** and **Polymorphism** when expanding new features.

******Regarding Technical Processing******
* **'Invulnerability Shield' Functionality:** Requires intervention in the **Collision Detection** algorithm. The system needs to check the character's **State Management** to ignore the 'Game Over' event when a collision occurs during the shield's active duration.
  
  <img width="400" height="500" alt="image" src="https://github.com/user-attachments/assets/5f8e536d-63cb-4fa0-a4f0-cfbaca2b6bea" />
* **'Speed Boost Lightning' Functionality:** Challenges the ability to manage time variables and **Frame rate**. The game must synchronously increase the movement speed of the background and obstacles.

  <img width="400" height="500" alt="image" src="https://github.com/user-attachments/assets/eb97333f-08f3-4004-9922-a3f4789123cb" />
* **Random Generation Algorithm:** Ensuring items appear at logical, reachable coordinates, avoiding cases where they spawn inside the pipes."


******OUTPUT******

<img width="383" height="683" alt="image" src="https://github.com/user-attachments/assets/fce03e66-e029-4c5b-aaf8-42061fb2afc5" />


<img width="404" height="721" alt="image" src="https://github.com/user-attachments/assets/7610dd22-df51-4b71-b566-ad2e75a609fc" />


<img width="385" height="700" alt="image" src="https://github.com/user-attachments/assets/760719d9-1405-4f00-908f-b06f3a944354" />


## HOW TO PLAY
```bash
python main.py
