TASK-1

c PROGRAM TO ADD SUM OF NUMBERS

![WhatsApp Image 2024-06-24 at 19 12 19_3a3ef8b7](https://github.com/varshamano1404/internship/assets/175196469/51a16880-5bc6-48f6-a950-cec4f5a30129)

CALCULATION OF RISC-V

![WhatsApp Image 2024-06-24 at 19 12 19_5d2007fe](https://github.com/varshamano1404/internship/assets/175196469/1682b4b9-1f1d-4925-83f0-f71780812cb7)

FAST INSTRUCTIONS

![WhatsApp Image 2024-06-24 at 19 12 26_97ac9330](https://github.com/varshamano1404/internship/assets/175196469/047b6227-95a9-47c8-9ce7-b8e7f1b73fc2)

UBUNTU INSTALLATION

![ubuntu installation](https://github.com/varshamano1404/internship/assets/175196469/4ae8e4b9-5816-4616-8855-c2c890d25efb)

TERMINAL

![terminal](https://github.com/varshamano1404/internship/assets/175196469/7cdcb686-97a2-4719-8f34-309aa7b5d10c)

TASK-2

C PROGRAM FOR 7-SEGMENT DISPLAY

![WhatsApp Image 2024-06-28 at 19 39 27_ccb3223b](https://github.com/varshamano1404/internship/assets/175196469/0bd121d0-cf38-4676-9823-a4ba4421590e)

OUTPUT FOR THE PROGRAM

![WhatsApp Image 2024-06-28 at 19 44 04_dd4a0ec3](https://github.com/varshamano1404/internship/assets/175196469/0c7fbb08-ecee-4e70-b9cc-d73adb840eb1)


TASK-3

SPIKE Simulation and observation with -O1 and -Ofast. Upload snapshot of compiled C Code

![WhatsApp Image 2024-06-28 at 19 50 55_e745de59](https://github.com/varshamano1404/internship/assets/175196469/d1205bcc-c8be-4643-a9ee-5c577e924e6d)

OUTPUT FROM RISC-V GCC AND C LANGUAGE VCC:

![WhatsApp Image 2024-06-28 at 19 53 38_5041b8d2](https://github.com/varshamano1404/internship/assets/175196469/8a1d547e-de6f-4430-80c4-299bcca0cfcd)


O1 MODE:

![WhatsApp Image 2024-06-28 at 19 54 58_4af9902c](https://github.com/varshamano1404/internship/assets/175196469/f2bba730-46c1-4872-8990-db601ca3b4c5)

![WhatsApp Image 2024-06-28 at 19 55 30_b128ef5c](https://github.com/varshamano1404/internship/assets/175196469/54816af4-be3c-45ac-835b-fc156ab90e2a)


OFAST MODE:

![WhatsApp Image 2024-06-28 at 19 59 54_5ce62c13](https://github.com/varshamano1404/internship/assets/175196469/bd1552ef-1f0a-4b72-a5dc-b173f8224411)

![WhatsApp Image 2024-06-28 at 20 00 26_2f4e424d](https://github.com/varshamano1404/internship/assets/175196469/fb38fc75-028f-4a7c-8bd6-4f29b374dd54)


TASK-4

RISC-V Instructions: Identify various RISC-V instruction type (R, I, S, B, U, J) and exact 32-bit instruction code in the instruction type format for below RISC-V instructions

![image](https://github.com/varshamano1404/internship/assets/175196469/81f5ba7a-f9dd-437e-9ba2-ec52da01f57b)

R-type Instruction:
R-type is an operation without immediate. The immediate is the number that exists as an integer in the instructions. The 7 bits from 0 to 6 are opcode (operation code), used to identify the type of instruction. 
Bits 7 to 11 are the index of the rd register.rs1 and rs2 arefunc7(7-bit), combined with opcode and fun3, this field describes what operation to perform. called source registers. In most cases, instructions need to read the values of the two source registers for operations.

![image](https://github.com/varshamano1404/internship/assets/175196469/d3c66bdd-92d4-40ed-af46-08b0a05cd92f)


I-type Instruction:
I stands for immediate in I-type instructions, indicating that operations are executed using registers and immediate values and are not dependent on memory locations.
The upper 12 bits of I-type is an immediate number.
The opcode is different from other instruction formats because the corresponding specific operations are different, and other parts are very similar to R-type.

![image](https://github.com/varshamano1404/internship/assets/175196469/08cc6567-bfd1-42cd-a891-ddf684fe5a7a)

S-type Instruction
S stands for "store" in S-type instructions, indicating that they are store-type instructions that aid in storing register values in memory. This type of command is mostly used for storing.
The characteristic of S-type instruction is that there is no rd register.
The immediate is divided into two parts, the first part is in bit 11-5, and the second part is in bit 4-0.

![image](https://github.com/varshamano1404/internship/assets/175196469/169426ef-d2c5-4d2d-885b-ee1b9dbdf39c)
