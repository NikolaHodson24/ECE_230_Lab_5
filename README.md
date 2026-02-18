# Lab 05 - Combinatorial Logic


In this lab, you’ve learned real world applications of digital logic, as well
as how to assemble your own Verilog modules. In addition, you’ve learned how
the constraints file maps your inputs and outputs to real pins on the FPGA.


## Rubric


| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |


## Name
Cameron Bannon & Nikola Hodson
## Lab Summary
We made two modules in verilog and connected them to make a complete digital logic circuit. From this we gained a better understanding of verilog syntax and how to connect components on a board using it. It is especially important to know how to design modules like we did in the lab as it allows us to reuse them either by instantiating a similar module multiple times in one project or by using the same module for a different project.
## Lab Questions


### 1 - Explain the role of the Top Level file.
It’s the control type module that is responsible for combining the different files and mapping all the inputs and outputs to different switches and leds and when necessary mapping different file outputs to other file inputs. Kinda like a manager or something assigning different tasks to different people.


### 2 - Explain the function of the Constraints file.
The constraints file defines the components on the board, namely which are being used and what they are called in verilog.
### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?
The use of Minterm and Maxterm does result in the most minimal function however looking at the KMAP it would have also been minimal to use Minterms for A instead of Maxterms, as it would have also led to the same function.
