# 📝 Web Programming HW2

> **Author:** Kaveh Ahmadi / lkavehamdl  
> **Date:** Oct 26 2026  


- [Question 1](#question-1)
- [Question 2](#question-2)
- [Question 3](#question-3)
- [Question 4](#question-4)
- [Question 5](#question-5)
- [Question 6](#question-6)
- [Disclaimer](#%EF%B8%8F-disclaimer)



---

## Question 1




**Answer:**Differences of HTTP versions is in the table below:

![Diagram](images/Q1.png)

And for "Why does HTTP/3 use UDP?":

TCP treats all data as one single stream. If one packet is lost, everything behind it has to wait until it is sent again. This is called head-of-line blocking, and in HTTP/2 it slows down every file on the page, even unrelated ones. TCP is also very hard to change, because it is built into operating systems and network devices.

UDP is simple and almost every network lets it through, so QUIC was built on top of it. QUIC adds reliability, ordering, congestion control and encryption by itself, but for each stream separately. This means a lost packet only stops its own stream.

## Question 2

**Answer:**



## Question 3
**Answer:** 

## Question 4

**Answer:**
## Question 5
**Answer:**
## Question 6
**Answer:**
## ⚠️ Disclaimer

I used AI to create the template and image used in Q1
.