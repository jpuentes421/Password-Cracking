# Password-Cracking
Cracking a password with Kali

## Objective
 To demonstrate how easily a simple password can be cracked. 


### Skills Learned

- How to hash a password using a hash generator 
- Using the **Kali Ophcrack** program to crack a hash 


### Tools Used

- NTML Hash Generator from Tobtu.com 
- Kali linux-Ophcrack

## Steps
1. Need to first grab a hash, Google **nt hash generator** and select **LM/NTLM Hash Generator** from Tobtu.
2. The website has a hash generator, we will be using the LM Hashes. Input a simple password like Car then click the Calculate Hashes button.
3. We see the resulting hashes for NTLM hashes and LM hashes. We will be focusing on the LM Hash; LM hashes or LAN Manager hash are legacy security protocols used in Windows to store user passwords.
4. Go to the **Ophcrack** program on Kali.
5. Select **Single Hash** under the **Load** option. Paste the resulting LM Hash from the LM/NTLM Hash Generator. Click **OK**.
6. Press the **Crack** button on the top menu. You will see the hash was quickly cracked. Demonstrates that if you use easy passwords, they are easily crackable.
7. Try a more complext password, input **P@ssw0rd** into the hash generator and copy the resulting LM hash.
8. Repeat steps 4, 5, and 6.
9. The password cracking program only found 1 letter within the password. 
10. Use complex passwords!
