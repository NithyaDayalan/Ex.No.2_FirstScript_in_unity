## Ex.No.2_FirstScript_in_unity
### DATE: 28/04/2024
### REGISTER NUMBER : 212223240110
### AIM:
To learn the basic scripting in Unity and print welcome message in Console window.

### Procedure:
1. Start the program
2. Open the Unity hub and Create a new 3D project
3. In Assets window, create the new folder and name it as Scripts
4. Create a new script with file name as FirstScript
5. Open the Script and print message "Welcome to Unity" inside the start function
6. Save the script
7. Create a new 3D game object in Hierarchy window and name it as 3DObject.
8. Add the component Firstscript in inspector window of 3Dobject.
9. Run the program
10. Stop the program.
    
### Program
```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
public class FirstScript : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        print("Welcome to the world of Unity!");
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}
```
### Output:
<img width="1919" height="1024" alt="Screenshot 2026-04-28 092118" src="https://github.com/user-attachments/assets/182fa85b-ae87-4144-9118-3639bd88cffa" />
<img width="1919" height="1020" alt="Screenshot 2026-04-28 092131" src="https://github.com/user-attachments/assets/fa3dddc1-6740-4ed2-8cbd-0c0f72cf9775" />

### Result:
Thus the welcome script was printed on Console Window sucessfully.
