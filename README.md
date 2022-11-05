# SpringCore

Inversion of Control :
                      IOC is a inversion of control which can create object and manage. 
                      Spring Bean is a part of IOC, objects are created by IOC, those objects are known as beans.
                      

IOC is a container where we store all the objects of our configuration files as "Beans". Bean is nothing but a object of our class that we store inside the IOC container.

IOC container have two interface which acts as IOC containers:
1. BeanFactory          (legacy)
2. ApplicationContext     

- ClassPathXmlApplicationContext is an implementation class of ApplicationContext 

 *spring container or IOC container is the core of spring framework.*

The Spring Container is responsible to:

1.create the objects (bean)
2.wire the created objects together
3.configure the objects
4.manage the objects complete life cycle from creation till destruction.
