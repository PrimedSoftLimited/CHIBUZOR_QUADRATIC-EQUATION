## CHIBUZOR_QUADRATIC-EQUATION
Algorithm to teach a child to solve a quadratic equation

#### Steps (Using the factorization method and assuming a = 1, we show by factors that (x+i)(x+j)=0; where b = i + j and c = i*j):

1.  If both b and c are positive integers, then i and j are positive;
hence;

i. Find two factors of c, i and j;
ii. If b = i + j,
	a. substitute i and j into (x+i)*(x+j)=0;
	b. x = -i or x = -j;
		Else, go back to step i.;

2. If b is negative whereas c is positive, then both i and j are negative;
hence;
  i. Find two factors of c, i and j;
  ii. If b = i + j,
 	a. substitute i and j into (x+i)*(x+j)=0;
	b. x = -i or x = -j;
        Else, go back to step i.;

3. If c is negative, then i and j do not have the same sign (either i is positive and j is negative OR vice versa);
hence;
  i. Find two factors of c, -i and j;
  ii. If b = -i + j,
 	a. substitute -i and j into (x+i)*(x+j)=0;
	b. x = -i or x = -j;
       Else b = i - j,
	a. substitute i and -j into (x+i)*(x+j)=0;
	b. x = -i or x = -j;  

Body: 

A quadratic equation is of the form ax^2 + bx + c = 0, where a, b, c is not equal to zero.
Using the factorization method, we show that the quadratic equation can be of the form  (x+i)*(x+j)=0 where b = i + j and c = i*j. Hence, since both (x+i) and (x+j) are not both zero then either (x+i)=0 or (x+j)=0. Therefore x=-i or x=-j.
