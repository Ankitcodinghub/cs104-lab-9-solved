# cs104-lab-9-solved
**TO GET THIS SOLUTION VISIT:** [CS104 Lab 9 Solved](https://www.ankitcodinghub.com/product/cs-104-solved-11/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109364&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS104 Lab 9 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
1. Assume we are given two lists named vect1 and vect2. Write a method that returns a list containing the meaningful values of vect1[i]/vect2[i]. Use exceptions and raising errors in your code as much as possible. For instance, you should throw an exception if entries are not float or integer. Similarly, you can throw an exception if the lists are not of same size. In these instances, one exception raise can be raise ValueError(‘getRatios called with bad arguments’)

2. Write a method to read grades from a file and calculates the median of the grades. Use exceptions in your code as much as possible. For instance, you should throw an exception if entries are not float or integer. Similarly, you can throw an exception if the file does not exist. If there is an exception, print the exception to the screen.

3. Write a function that asks for an integer and prints the square of it. Use a while loop with a try, except, else block to account for incorrect inputs.

4. Debug the following program by using breakpoints in your IDE.

import math

def demo(a, b, c):

d = b ** 2 – 4 * a * c if d &gt; 0:

disc = math.sqrt(d) root1 = (-b + disc) / (2 * a)

root2 = (-b – disc) / (2 * a)

return root1, root2 elif d == 0: return -b / (2 * a) else:

return “This equation has no roots”

if __name__ == ‘__main__’: while True:

a = int(input(“a: “)) b = int(input(“b: “)) c = int(input(“c: “)) result = demo(a, b, c)

print(result)

5. Below is buggy code to get a list of primes less than equal to a given number n. Try to debug it, and fix it such that it properly returns list of primes.

def primes_list_buggy(n):

“””

input: n an integer &gt; 1

returns: list of all the primes up to and including n

“””

# initialize primes list if i == 2:

primes.append(2)

# go through each elem of primes list for i in range(len(primes)): # go through each of 2…n for j in range(len(n)):

# check if not divisible by elem of list if i%j != 0:

primes.append(i)
