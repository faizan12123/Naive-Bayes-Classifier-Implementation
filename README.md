# Naive-Bayes Classifier Implementation
The objective of this project was to implement a Naive-Bayes classifier algorithm to train two different cases:


## Case 1

The	toy	examples	have	two	features	including	color	=	{‘blue’,	
‘green’,	‘red’,	‘yellow’}	and	shape	=	{‘circle’,	‘square’}	and	two	labels	including	
‘+’	and	‘–’.		
I used the	examples	below	and	built	three	lists	for	the	training	data	set:

![image](https://user-images.githubusercontent.com/20651843/170394083-25e25e90-e424-4d98-9ced-ca76703803f8.png)


Once	my  model	was	trained,	I showed	if	the	following	two test	cases, {blue,	
square}	and	{yellow,	square}	is	 ‘+’	or	‘–’	from	my	classifier.


## Case 2

![image](https://user-images.githubusercontent.com/20651843/170394231-3793301a-3279-421e-bd3f-aefccf3345c9.png)


I trained	my	classifier	with	weather	samples	that	have	two	features (outlook,	
temperature) and	one	label	(decision).	I then predicted	a	weather	that	has	
{outlook=‘overcast’	and	temperature=‘mild’}	from	my	classifier	program.


## Results

For case 1: 

```
Case 1: {blue, square}
Prediction: ['plus']
Case 1: {yellow, square}
Prediction: ['plus']
```

For case 2:

```
Case 2: {outlook=‘overcast’ and temperature=‘mild’}
Decision: ['Yes']
```
