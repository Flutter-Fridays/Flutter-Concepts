# What is **with** keyword in Flutter?
The **with** keyword indicates the use of a "mixin". 

A mixin refers to the ability to add the capabilities of another class or classes to your own class, without inheriting from those classes. The methods of those classes can now be called on your class, and the code within those classes will execute. Dart does not have multiple inheritance, but the use of mixins allows you to fold in other classes to achieve code reuse while avoiding the issues that multiple inheritance would cause.

I note that you have answered some questions about Java -- in Java terms, you can think of a mixin as an interface that lets you not merely specify that a given class will contain a given method, but also provide the code for that method.

In conclusion, **with** keyword is used for mixin. And mixim is like an interface in Java to Dart.
