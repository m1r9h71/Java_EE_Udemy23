# Java_EE_Udemy23
Singleton Session Enterprise Java Beans

#In this tutorial i created a Singleton local Bean called CounterBean with a counter set to 0 and getters and setters created.
One Servlet called ShowCount
One Servlet called AddOne
I changed the name of the interface to FlightLocal_ejb11 in case of conflicts
Going to localhost:8080/ejb11/ShowCount displayed the zero count.
Going to localhost:8080/ejb11/AddOne added one to the count each time the page was refreshed.

This proves that CounterBean object cb refers to the same object on an ejb container.


