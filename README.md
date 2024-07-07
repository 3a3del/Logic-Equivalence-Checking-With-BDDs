# Logic-Equivalence-Checking-With-BDDs                    
An Assignment in VLSI CAD Part I: Logic Course under supervision of Rob A. Rutenbar, Adjunct Professor
We can use a BDD to determine if two gate-level networks are implementing the same function or not. And, if they are not the same, we can use the BDD to find an assignment of the variables that will make the network outputs different. In this problem, we will let you play with a real BDD package: kbdd from Prof. Randy Bryant’s research group at Carnegie Mellon University (
http://www.cs.cmu.edu/~bryant/
)
To explain how to use kbdd, let us compare these two very simple logic networks:                      
![](https://github.com/3a3del/Logic-Equivalence-Checking-With-BDDs/blob/main/Q9_sim.png)                    
If you go look in the TOOLS section of the course website (https://www.coursera.org/learn/vlsi-cad-logic/programming/ct9Sx/kbdd), you will find two helpful tutorials about kbdd: a written document that explains the tool and its capabilities 'Don't worry i will provide them here', and also a short video tutorial about to use kbdd in the Coursera MOOC environment (https://youtu.be/kfaFnkljskg?si=3ABDR3aBWdY4VnXB). Please go look at those before you proceed further in this problem.

Assuming you have read/viewed these tutorial materials, the kbdd script for checking equivalence of z1 and z2 is shown below. Note that i have embedded some comments in the script to help you read it more easily.                                                                                                    
So You will see two results. (1) “0 verify failed” It means 𝑧 1 z1 and 𝑧 2 z2 are NOT equivalent. (2) “Variables: a 0” It means inputs < 𝑎 = 0 , 𝑏 = 1 > <a=0,b=1> and < 𝑎 = 0 , 𝑏 = 0 > <a=0,b=0> will make two logic networks have equivalent.                                                                                                    
# Compare the two logic networks 𝐹 and 𝐺 , each functions of 5 variables ( 𝑣 , 𝑤 , 𝑥 , 𝑦 , 𝑧 ) shown below using kbdd.
![](https://github.com/3a3del/Logic-Equivalence-Checking-With-BDDs/blob/main/temp.png)

**The Answar provieded, GoodLuck!
#Results
KBDD: satisfy diff
 - The means that the two gate level network equivalent 'only when'                                                                              
Variables: x y z w v become
01101
10001
10101
11000  
  
  
  
  
  
  
  
  
