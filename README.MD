# Creating a SSH Key
## Setup in Windows
---------
1. Go to Settings
2. Choose the App tab
3. Choose "Optional Features"
4. Install the "OpenSSH Client"

## Command Prompt
------
1. Open Command Prompt
- It can be done by opening searching "cmd" in Start
2. Enter the code below 
```sh
ssh-keygen -t -rsa
```
- It will come out like this


![Step 2 for SSH key](https://github.com/dhaloshorns/Assignment-3/blob/main/Screenshot%202022-02-09%20172628.png)

Press "Enter"

3. It will ask for a passphrase

   * Passphrase is a phrase that is used for identifying the user similarly to password. However, instead of only a word it requires a phrase. For example, "I like cheeseburger".

   * Choose a phrase that you can easily remember

4. Reenter the passphrase

5. Your SSH key is generated when the key randomart image is generated.
      
      * You can retrieved your SSH key by entering the code below
     ```sh
    notepad C:\Users\user/.ssh/id_rsa.pub
    ```
**'user' is dependent on how you save your username in Windows**

After entering the code above, a Notepad file will pop up with your SSH key.
