# TestBed
Chapter 3:<br/>
  Question 3:<br/>
  Implemement the following method which takes two int parameters a and b and returns the sum of the squares of all integers in [a,b]. For example, sumSquares(3,5) should return 50 because (3^2 + 4^2 + 5^2 = 50). The method should return 0 if a is not less than b.<br/>
    public int sumSquares(int a, int b)<br/>
  Question 4:<br/>
  Implement the method shown below which computes the price of a movie ticket based on this algorithm: On Wednesdays (day Code W), the price of the ticket is $8. On all other days, the price depends on the age of the customer. For a child who is less than 10, the price is $8, and for a teen who is between 10 and 17, the price is $10, and for a senior who is 60 or over, the price is also $10. For other ages, the price is $12.<br/>
    public static double moviePrice(int age, String dayCode)<br/>
  Question 5:<br/>
  Implement the method shown below which computes the factorial of n if n belongs to the interval [0,12], and throws a RuntimeException with message "Number must not be negative" if n is negative, and throws a RuntimeException with message "Number must not be greater than 12" if n is greater than 12. For example, factorial(4) should return 24. <br/>
  public static int factorial(int n)<br/>
  Question 6:<br/>
  Implement the following method which takes two int parameters a and b and returns the number of perfect squares in [a,b]. A perfect square is an integer whose square root is also an integer. For example, calc(4,15) should return 2 because there are two integers in the [4,15] interval that are perfect squares (4 and 9).The method should throw a RuntimeException with an appropriate message if a > b and with a different appropriate message if both a and b are negative.<br/>
    public int calc(int a, int b)<br/>
  Question 8:<br/>
  Given two integers, if n <= m then return the sum of the reciprocals of all integers from n to m (inclusive) rounded to 2           decimals. Otherwise, return n/m (this is real division) also rounded to 2 decimals. <br/>
    public static double reciprocalSum(int n, int m)<br/>
Chapter 4:<br/>
  Question 1:<br/>
  Implement the method shown below which takes a real number and returns the sum of the digits in it with any non-digits (such as the sign and decimal point) ignored. For example, digitSum(-12.25) should return 10 because the 1+2+2+5= 10.<br/>
    public int digitSum(double x)<br/>
  Question 4:<br/>
  Implement the method shown below which validates a given DNA sequence (a string):<br/>
    public boolean isValidDNA(String DNA)<br/>
  The sequence is represented by a string of letters each of which represents a nucleotide. To be valid, the sequene must:<br/>
    a. be made up exclusively of the capital letters: A, C, G, and T <br/>
    b. start with the amino acid "ATG", and<br/>
    c. have a nucleotide count that is divisible by 3<br/>
  Question 6:<br/>
  Implement the method below which takes a string and return a count of the telephone numbers embedded in it. <br/>
  A telephone number consists of a three-digit area code followed by a dash or a space, followed by three digits, followed by a dash or a space, followed by four digits. <br/>
  Note that the two spereators need not be the same; i.e. it could be dash/dash, dash/space, space/space, or space/dash<br/>
    public int telCount(String s)<br/>
  Quesion 7:<br/>
  Implement the method shown below which receives a non-empty string str; extracts the computing courses in it; and returns the sum of their credit counts. if the recieved string has no computing course in it then the method returns 0:<br/>
    public static int totalCredit(String str)<br/>
  A computing course is recognized by the prefix EECS or CSE (in upper or lower case) followed by four digits, followed by one or more periods, followed by the credit count, which can be optionally bracketed. The credit count of a course is a single digit. Here are four examples of valid computing courses:<br/>
    EECS1022.3, cse4413..[4], eecs4141....[6], CSE3481..3<br/>
  For example, if str is the string:<br/>
    "Course EECS1022..3 and cse1020.[4] with CSE3421 or CSE6215...8"<br/>
   then the return should be 15.<br/>
 Question 9:<br/>
 Given a non-empty string, this method locates the Canadian postal code embedded in it and returns the sum of the digits in that postal code.<br/>
 If no postal code is found then return -1 and if more than one is found then locate the one that occurs last in the string.
 A Canadian postal code consists of a letter-digit-letter sequence followed optionally by one space and then followed by a digit-letter-digit sequence:<br/>
  public static int postalDigitSum(String str)<br/>
 For example, if str is the string:<br/>
  "Try M3J1P3 or m5s 2W8 and m3:9j4"<br/>
 then the return should be the integer:<br/>
  15<br/>
 Note that the letters in the postal code could be in lower, upper, or mixed case (some upper, some lower).
   
