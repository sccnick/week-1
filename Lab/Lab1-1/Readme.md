# Instruction

## Read and understand the code, the logic behind it, the limitation of it
* Answer the question 1 - 4 below (you can edit this file directly)
* Change the code such that it will sort from larger to smaller, put the revision of your code below
* Change the code such that there is no flag variable, put the commit number below and answer question 5 


## Revision, put your commit number here
* Sort from larger to smaller:
* Without flag:

## Questions
1. How this code can sort number from smaller to larger
 
Answer: มีการตรวจสอบเลขจากที่ตำแหน่งiและi+1 โดยเริ่มที่i=0 ถ้าตำแหน่งiมากกว่าi+1จะสลับเลขไปเรื่อยๆจนกว่าจะเริ่มเลขเสร็จ

2. What if two numbers equal, what will happen? 

Answer: ตัวเลขจะไม่สลับเพราะไม่เข้าเงื่อนไข

3. How many times at line 24 will be executed (as a function of the size of input) 

Answer: 27 n(n-1)

4. Why we need flag variable ? 

Answer: เพื่อกำหนดว่าการทำงานเป็นจริงหรือเท็จ โดยถ้าเป็นริ่มต้นที่เท็จ แต่ถ้าเป็นไปตามเงื่อนไขจะเป็นจริง

5. When we remove the flag variable, the code will run faster or slower? in which scenario? 

Answer: