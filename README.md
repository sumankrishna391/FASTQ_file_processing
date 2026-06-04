# FASTQ_file_processing

To check the quality of reads in FASTQ file:
follow the steps:
# Step 1: go to ubuntu

# Step 2: type cd
# Step 3: cd / mnt 
# Step 4: ls 
 you will get the drives where the file is present: c  d  wsl  wslg 
# step 5: Go to C drive

# Step 6: Copy FASTQ file from C drive to Ubuntu home
cp /mnt/c/test_udemy.fastq ~/

# Step 7: Go to Home directory
cd ~

# Step 8: Check file exists
ls

# You should see:
test_udemy.fastq

# Step 9: Run FastQC
fastqc test_udemy.fastq

# Step 10: Check output files
ls 
<img width="1475" height="377" alt="Screenshot 2026-06-04 121134" src="https://github.com/user-attachments/assets/7876f2be-ba21-4f91-8a73-a49fde3a317b" />

# Result files you will get:
test_udemy.fastq
test_udemy_fastqc.html
test_udemy_fastqc.zip

# Step 11:  To open the HTML report in Windows browser
explorer.exe .
Then double-click:
test_udemy_fastqc.html

OR 

# To save HTML report to Windows Desktop
cp test_udemy_fastqc.html /mnt/c/Users/HP/Desktop/

OR

# To Save HTML report to Downloads folder
cp test_udemy_fastqc.html /mnt/c/Users/HP/Downloads/

<img width="924" height="574" alt="image" src="https://github.com/user-attachments/assets/66139214-d2c4-4cc2-8d0c-5bcd9b443e4c" />

