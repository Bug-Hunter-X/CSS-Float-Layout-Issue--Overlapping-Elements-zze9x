# CSS Float Layout Issue: Overlapping Elements

This repository demonstrates a common issue in CSS layout related to floating elements and how to fix it using a clearfix.

The problem: Floating elements without a proper clearfix can lead to unexpected layout issues, where elements overlap or the parent container doesn't collapse to the correct height.

The solution:  Use a clearfix technique (such as the one provided in `bugSolution.css`) to ensure that the parent container properly wraps around the floated elements.