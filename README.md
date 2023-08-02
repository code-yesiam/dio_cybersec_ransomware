# Explaining how to use this code

This is a CyberSec project from [Dio](https://dio.me) where we build a ransomware Python script to decrypt and encrypt some info, simulating a ransomware attack. We use ```encrypt.py``` script to encrypt all information, and when the victim pays the ransom, we use the ```decrypt.py``` to turn back the encryption.

### Step-by-step (encryption)

- Open a Kali Linux VM;
- On terminal, use ```nano yourfileencrypt.py``` to start creating your first Python script, which is the encryption (you can get the script right above, on the project);
- Create a text file with ```nano yourfiletext.txt``` and go write something to test the encryption;
- After that, run your script with ```python yourfilename.py```. If no messages appears, it means that that ```yourfiletext.txt``` is encrypted now;

### Step-by-step (decryption)

- Make a folder for your project with ```mkdir your_ransom_project```;
- Now you gonna enter on this folder using ```cd your_ransom_project```;
- Create three files using ```touch``` command on Kali cmd: one will be a ```.txt``` file and the other two will be a ```.py``` file for encryption and decryption. It can be something like ```touch test.txt```, ```touch encrypt.py``` and ```touch decrypt.py```;
- Use the scripts on the project to use on each file to proceed with the ransomware test;
- After that, you can redo the same steps to encrypt a file.
- With the file encrypted, use ```ls``` to see the files you have on your Kali. Maybe you'll see a ```test.txt.ransomwaretroll``` file, if it's all okay, and you can also see his encrypted content with ```nano test.txt.ransomwaretroll```;
- After that, use ```decrypt.py``` to decrypt all file.
- Use ```ls``` again and you'll see that your file had got back to ```test.txt```. You can see also his content with ```nano test.txt```.

This is all for this project. I hope you learned something :))
