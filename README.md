# java_hackerrank
To keep track of java programs in hackerrank

13/11/2019 Things learnt today about string:
Java implements string as string object not array.
String is immutable , every time you do modifications on strings a new object is created.
If you want to make string mutable use StringBuffer and StringBuilder.
String,stringbuffer,stringbuilder classes are all in java.lang.
***IMP these classes are declared final, so they dont have subclasses.
*** All three implement the charSequence Interface ***

String constructor:
1.String a = new String() ---> creates empty string.
char a[]= {'a','b'};
2.String s = new String(a)---> creates "ab".
3.String s = new String(char chars[],int startindex, number of characters);
4.string s1 = new string(string s2) assigns string s2 to s1.
5.string(byte ascii); where ascii is a byte array. ex: byte ascii[]={65,66,67} prints string as abc
6.String creation using stringbuilder and string buffer
7.String(StringBuilder stringbuilderobjecy), String(StringBuffer stringbuffer object);

