### Half coverage
if(a) 
	x();
else
	y();
if(b)
	v();
else
	w();
### Test driven development
someone said that you should write the unit test before the actual code. 
so the question is 
#### can I write the unit teting before code for the white box( or black boxes)
Yes, you can
In order to do that, we need to know
	-1) specification for methods
		-( method headers, API)
	test first, code second
		-benefits:
			- brainstorm the implementation
			- clear direction + specification
			- testing more edge cases

## Criteria to evaluate the quality insurance: lets evalue Unit testing.
	-Cost----->time of dev writing unit testing, running the test, mantaining them.
note: writting unit testing is sunk cost, and running and maintaining are recurring cost.
	-Bugs Found----> logical errors, comptability, missing functionality
	-Bugs Missed-----> usability bugs, nondeterministic, missed feature, scalability/Performance
	-Technique Overlap
	-Cost of Fix---> the cost is pretty low
	-Lifecycle----> right before, right after
	-Stopping point----> Diminishing return, and coverage(% coverage),Business driver.


## Test Plan

How are we goint to test
	-who
	-what
	-when
	-how
	-why
dogfood problem: you have to eat your own dogfood to make it better and make it ok for human to eat

## Bug Priority

    ####Priority	Severity
	   1              Blocker
	   2		  Critical
	   3		  Major
	   4		  Minor
	   5		  Trivial
	Priority 1 and priority 2 that are must be fixed

## Status and Resolution
	-New
	|
	|
	|
	|
	|
	-Assigned-----------Resolved<===========>reopened
				/
			       /
			      /
			    Verified
				\		
				 \
				  \
			           Closed


####	-Status of the Bug
		-Works for me
		-fixed
		-wont fix
		-invalid
		-duplicated
	
