# Logger
Handle the real time logging challenges
Basic-requirements
1. Can be used with any language/OS/Platform.
2. Easy Integration (easy link and unlink)
3. Easy to use
4. Provide different levels of logs (Error, Info, Warning)
5. Easy enabler for feature specific logging
6. Random variable support
7. Real time data update
8. Support for heavy size of log files
9. Auto reduction of random and repeated logs, if no issues found - Model needs to be trained with successful logs for various scenarios.
10. Logs should generate alert if any error found - Again, model can be trained with failure logs.
11. Automatic type deduction for provided data type, and print it in most readable form.
12. e.g.
13.   int a =5; double b = 5.5;
14.   // All the below examples should generate --> a is 5 b is 5.5
15.   Log("a is " a "b is " b); 
16.   Log("a is "+ a "b is "+ b);
17.   Log("a is "<< a "b is "<< b);
18.   Log("a is %d b is %f",a, b);
