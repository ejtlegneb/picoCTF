# Step 1
check what the command netcat does:
netcat (often abbreviated to nc) is a computer networking utility for reading from and writing to network connections using TCP or UDP. The command is designed to be a dependable back-end that can be used directly or easily driven by other programs and scripts.

# Step 2
running nc mercury.picoctf.net 43239

# Step 3
I immediately realised that it sends ascii char codes in decimal, so I just turned them into characters to get the flag