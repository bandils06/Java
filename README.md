# Functions:

# STRING FUNCTIONS: 

NOTE:- STRINGS ARE IMUTABLE (It never changes).
	 The original values of string 's1' & 's2' are remains same even after these operations.

- s1.length() --> returns the size of the string 's1'.
- s1.charAt(i) --> returns character at index 'i'.
- s1.replace("abc", "xyz") --> Replace "abc" with "xyz" in string 's1'.
- s1.toLowerCase() --> Convert string 's1' to lower case.
- s1.toUpperCase() --> Convert string 's1' to upper case.
- s1.trim() --> Removes all the spaces Before and After.
- s1.codePointAt(i) --> returns ASCII value of character at index 'i'.
- s1.codePointBefore(i) --> returns ASCII value of character before index 'i'.
- s1.compareTo(s2) OR s1.equals(s2) --> compare both strings 's1' & 's2'. This function is CASE SENSITIVE.
			     			    if same; returns 0.
			     			    else; returns NUMBER OF DIFFERENT CHARACTERS.
- s1.compareToIgnoreCase(s2) OR s1.equalsIgnoreCase(s2) --> Same as "compareTo()" function.
										But, this function is NOT CASE SENSITIVE.
- s1.concat(s2) --> Concat two strings.
- s1.contains(s2) --> Returns "TRUE" if string 's2' contains in 's1'.
			    else Returns "FALSE".
- s1.endsWith("abcxyz") --> Returns "TRUE" if string 's1' ends with "abcxyz".
			          else Returns "FALSE".
- s1.indexOf("abcxyz") --> Returns the starting position of string "abcxyz".
- s1.isEmpty() -- Returns "TRUE" if the string is empty.
			else, Returns "FALSE".
- s1.lastIndexOf("abcxyz") --> Returns the position of last "abcxyz" in the string.
- s1.startsWith("abc") --> Returns "TRUE" if string 's1' starts with "abc".
				   else, Returns "FALSE".

