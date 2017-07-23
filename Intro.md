<h1>Introduction</h1>
We have all had our interaction with if not advanced but basics of C programming sooner or later in the ciriculumn via FCP.<br>
You may have felt great at the time you ran your first programme which might have been mostly hello world or when actually created some something usefull<br>
But thats all.Your introduction c/c++ is limited to what you have been taught, if not for much exploration,Cos many of the schools,colleges even ours are directing the students to TURBO C++.<br>
If at any point of time you didn't feel that your interface was crappy your then probably you are very optimistic.<br>
Frankly Speaking TURBO C is nothing but * C++ - all the cool life easy making feature + boring user interface *.I guarantee TURBO C interface itself is probably the major reason why many people end up not taking much intrest in C++<br>
The current C++ developers use GCC compiler which gets updated regularly is standardised by the ASCII commitee and this compiler will go all the way which I am almost sure of considering the fact that it is open sourced.<br>
New standards are put into force every 3 years.THe latest C++17 is already Out unlike Turbo C which had its last stable version released in 2006 11 years from today.<br>
Installation and using GCC is also very easy and can also be done online one which well be using today.<br>
Now there are several reason why we need to desperately need to switch to GCC compiler from TURBO C on which I can keep talking for one complete workshop but It can be for sure a good topic for discussion some other day with all faculty ariund us etc.coming back to point.<br>
GCC compiler has better standards and has few syntactical changes which well be seeing.<br>
<ul>
	<li>No Conio.h so no getch(),putch(),gets() etc.</li>
	<li>Using namespace std(nothing but acts as surname in Indian)</li>
	<li>use int main() always return 0 so that we can get non zero exit value</li>
	<li>if need be we can make use of c header files removing .h and appending C at the begining</li>
</ul>

<h2>Templates</h2>

Templates was one of the recent addition that was worked out by bell labs now known as AT&T in 1990's and now finally included to the C++11 version.
Templates as the name suggest are nothing but a set of predifined statements that provide us with ready to use instances
Now the doubt that might arise in your mind is this not what function does how is it different.
<h3>Method to define a function->for other datatype?</h3>
The answer is templates provides us with generic function.That is instead of defining a fuction individually for every datatype what you can do is define a single template
Transition-> 

```C++

template <class  datatype> return-type function-name (parameter-list)
```

In similar manner complete Datastructure classes can be defined


```C++

template <class T> class mypair 
{
    T values [2];
  public:
    mypair (T first, T second)
    {
      values[0]=first; values[1]=second;
    }
};

```

To make our life further Simpler C++ introduced to us with set of pre-defined containers in the library called
"Standard Temple Library"
These provide us with several containers which can be used as when required and all of them have their own set of member values and functions which we will learn on the go.
Now this workshop is intended to be a introducer to problem Solving Stratergies using various tools and techniques in no way do we intend to use teach every possible container and fuction for which we at codecell have created extended documentation were you can checkout the details.
As the name suggest well follow the approach of problem solving where we have cherry picked a few problems that make use of these containers and we'll discuss them in the go
