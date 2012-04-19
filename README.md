js-math-expression-evaluation
=============================

Evaluate complex math string expressions without doing any string parsing


Parse complex math (or any) string expressions using javascript without doing any string parsing, instead using native
javascript language capabilities. 

eg 

  “(SUM(4 + 5) * 10) + 100”
  DIFF ( SUM ( SUM ( g1,  SUM( val2,  PRODUCT (2 , 2) ),  6),  5),  40)

Use Rhino (http://www.mozilla.org/rhino/) to run this script in server side java