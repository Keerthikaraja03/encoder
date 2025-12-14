# encoder


AIM:

To implement Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

SOFTWARE REQUIRED: Quartus prime

THEORY

Encoder 8 To 3

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

<img width="393" height="302" alt="image" src="https://github.com/user-attachments/assets/ace512ef-9bd5-46b6-b0d3-e27d69892533" />


Figure 01 Block Diagram of Encoder 8 * 3

Truth Table

<img width="501" height="382" alt="image" src="https://github.com/user-attachments/assets/17b28de2-5a1b-4b40-97ba-a4cdfef52513" />


The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

<img width="742" height="416" alt="image" src="https://github.com/user-attachments/assets/3fcf202c-54e3-4345-8eea-b9a04bf1fb97" />


Figure 02 Encoder 8 * 3

Procedure

/* write all the steps invloved */

PROGRAM

/* Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming.

Developed by: R . Keerthika

RegisterNumber: 25017601

RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling

TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling

RESULTS


