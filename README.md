# MDP REPRESENTATION

## AIM:
To Create any one real world problem in Markov Decision Problem(MDP).

## PROBLEM STATEMENT:
```
Developed By:P.Siva Naga Nithin
Reg.No:212221240037
```

### Problem Description
To complete the school admisssion process , the role of the agent is to promote if the student is eligible , if not eligible , no admisssion.

### State Space
{A1,A2,A3}->{0,1,2}

A1-> Admission Process 1

A2-> Admission Process 2

A3-> Final Process of Admission

### Sample State
A1 -> Admission Process 1

### Action Space
{E,NE} -> {0,1} E -> Eligible NE -> Not Eligible

### Sample Action
E-> Eligible

### Reward Function
R= { +1, if eligible +0, otherwise}


### Graphical Representation

![image](https://github.com/user-attachments/assets/2903e78c-f940-41e1-a628-16ac6a1d0247)


## PYTHON REPRESENTATION:
```
T = {
    0 : {
        0 : [(1.0, 1, 1.0, True)],
        1 : [(1.0, 0, 0.0, False)]
    },
    1 : {
        0 : [(1.0, 2, 1.0, True)],
        1 : [(1.0, 0, 0.0, False)]
    },
    2 : {
        0 : [(1.0, 2, 1.0, True)],
        1 : [(1.0, 1, 0.0, False)]
    }
}

T
```
## OUTPUT:
![RL1 2](https://github.com/user-attachments/assets/566ca98d-f17b-421d-a01f-174e6ff72a05)


## RESULT:
Thus the given Markov Decision Process(MDP) problem is represented in the following ways.
Text representation, Graphical representation, Python - Dictonary representation.
