# README #

ArrayList vs. LinkedList: in both classes, ArrayList and LinkedList showed similar run time as, but as the size increased, ArrayList implementation became faster and faster. At a input size of 10000, ArrayList implementation completed in 1,951 ms and LinkedList completed in 4,127ms. 

What happens if you try list.remove(77)? It tries to remove the value at index 77 instead of the value containing 77. The program fail because there is no index 77.

list.remove(5); // what does this method do?
//this method removes the element at index 5

list.remove(Integer.valueOf(5)); // what does this one do?
//removes the first occurrence of the integer 5 


