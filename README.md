# Logger
Handle the real time logging challenges
Basic-requirements
1. Can be used with any language/OS/Platform.
2. Easy Integration (easy link and unlink)
3. Easy to use
4. Provide multithreading support
5. Provide different levels of logs (Error, Info, Warning)
6. Easy enabler for feature specific logging
7. Random variable support
8. Real time data update
9. Support for heavy size of log files
10. Auto reduction of random and repeated logs, if no issues found - Model needs to be trained with successful logs for various scenarios.
11. Logs should generate alert if any error found - Again, model can be trained with failure logs.
12. Automatic type deduction for provided data type, and print it in most readable form.

 e.g.
 
   int a =5; double b = 5.5;
   
   // All the below examples should generate --> a is 5 b is 5.5

   Log("a is " a "b is " b);

   Log("a is "+ a "b is "+ b);
   
   Log("a is "<< a "b is "<< b);
   
   Log("a is %d b is %f",a, b);
