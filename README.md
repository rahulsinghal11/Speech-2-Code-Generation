# four_spaces

BGL Intern Hackathon 2020 | Team four_spaces



Usage Instructions regarding usage of speech2text file from MATLAB 

1. Open matlab
2. Run this command - 
    ```Matlab
    [status, commandOut]=system("python C:\Users\akash\OneDrive\Desktop\Hackathon\speech2Text.py a.txt")
    % Here, the inside param of system is in the format: python | absolute path to the python file(speech2text.py) | name of the text file | 
    % every '|' is a space in the above format XD
    ```
3. This will open the microphone and say whatever u want and wait for 3 seconds to stop
4. Your generated text will go inside (append-write) into the named txt file.

PreReqs:
1. Make sure u have python on the system u are trying 
2. You need to have MATLAB obviously
3. When I say MATLAB I dont mean MATLAB Online !

Integration:
- Reeshabh will trigger this MATLAB Command from the GUI's button he has created
- After this maybe u have to read the generated txt as input and give out the apt command jo execute hoga

    
