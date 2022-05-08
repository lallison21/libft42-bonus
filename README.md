<h1 align="center">LIBFT</h1>
<h3 align="center">It's first project in École 42/21 School</h3>

<h4> This project is about coding a own C library. <br>  </h4>

<table align="center">
  <thead>
    <tr> <th> № </th> <th width="250"> Function name </th> <th width="600"> Descriprion </th> </tr>
    <tr> <th colspan="3" align="center"> Mandatory part </th>
  </thead>
  <tbody>
    <tr> <td align="center"> 1 </td> <td align="center"> isalpha :white_check_mark: </td> <td> Checks for an alphabetic character. </td> </tr>
    <tr> <td align="center"> 2 </td> <td align="center"> isdigit :white_check_mark: </td> <td>  Checks for a digit (0 through 9). </td> </tr>
    <tr> <td align="center"> 3 </td> <td align="center"> isalnum :white_check_mark: </td> <td>  Checks for an alphanumeric character; it is equivalent to
              (isalpha || isdigit). </td> </tr>
    <tr> <td align="center"> 4 </td> <td align="center"> isascii :white_check_mark: </td> <td> Checks whether c is a 7-bit unsigned char value that fits
              into the ASCII character set. </td> </tr>
    <tr> <td align="center"> 5 </td> <td align="center"> isprint :white_check_mark: </td> <td> Checks for any printable character including space. </td> </tr>
    <tr> <td align="center"> 6 </td> <td align="center"> strlen :white_check_mark: </td> <td> This function calculates the length of the string pointed
       to by s, excluding the terminating null byte ('\0'). </td> </tr>
    <tr> <td align="center"> 7 </td> <td align="center"> memset :white_check_mark: </td> <td> This function fills the first n bytes of the memory area
       pointed to by s with the constant byte c. </td> </tr>
    <tr> <td align="center"> 8 </td> <td align="center"> bzero :white_check_mark: </td> <td>  This function erases the data in the n bytes of the memory
       starting at the location pointed to by s, by writing zeros (bytes
       containing '\0') to that area. </td> </tr>
    <tr> <td align="center"> 9 </td> <td align="center"> memcpy :white_check_mark: </td> <td> This function copies n bytes from memory area src to
       memory area dest.  The memory areas must not overlap.  Use
       memmove if the memory areas do overlap. </td> </tr>
    <tr> <td align="center"> 10 </td> <td align="center"> memmove :white_check_mark: </td> <td> This function copies n bytes from memory area src to
       memory area dest.  The memory areas may overlap: copying takes
       place as though the bytes in src are first copied into a
       temporary array that does not overlap src or dest, and the bytes
       are then copied from the temporary array to dest. </td> </tr>
    <tr> <td align="center"> 11 </td> <td align="center"> strlcpy :white_check_mark: </td> <td> This functions copy and concatenate strings with
     the same input parameters and output result. They are
     designed to be safer, more consistent, and less error prone replacements
     for the easily misused functions strncpy and strncat. </td> </tr>
    <tr> <td align="center"> 12 </td> <td align="center"> strlcat :white_check_mark: </td> <td> This functions copy and concatenate strings with
     the same input parameters and output result. They are
     designed to be safer, more consistent, and less error prone replacements
     for the easily misused functions strncpy and strncat. </td> </tr>
    <tr> <td align="center"> 13 </td> <td align="center"> toupper :white_check_mark: </td> <td> This function converts a lower-case letter to the corresponding
     upper-case letter. </td> </tr>
    <tr> <td align="center"> 14 </td> <td align="center"> tolower :white_check_mark: </td> <td> This function converts an upper-case letter to the corresponding
     lower-case letter. </td> </tr>
    <tr> <td align="center"> 15 </td> <td align="center"> strchr :white_check_mark: </td> <td> This function locates the first occurrence of c (converted to a
     char) in the string pointed to by s.  The terminating null character is
     considered to be part of the string; therefore if c is `\0', the func-
     tions locate the terminating `\0'. </td> </tr>
    <tr> <td align="center"> 16 </td> <td align="center"> strrchr :white_check_mark: </td> <td> This function is identical to strchr, except it locates the
     last occurrence of c. </td> </tr>
    <tr> <td align="center"> 17 </td> <td align="center"> strncmp :white_check_mark: </td> <td> This function compares not more than n characters.  Because
     strncmp is designed for comparing strings rather than binary data,
     characters that appear after a `\0' character are not compared. </td> </tr>
    <tr> <td align="center"> 18 </td> <td align="center"> memchr :white_check_mark: </td> <td> This function locates the first occurrence of c (converted to an
     unsigned char) in string s. </td> </tr>
    <tr> <td align="center"> 19 </td> <td align="center"> memcmp :white_check_mark: </td> <td> This function compares byte string s1 against byte string s2.
     Both strings are assumed to be n bytes long. </td> </tr>
    <tr> <td align="center"> 20 </td> <td align="center"> strnstr :white_check_mark: </td> <td> This function locates the first occurrence of the null-termi-
     nated string needle in the string haystack, where not more than len char-
     acters are searched.  Characters that appear after a `\0' character are
     not searched. </td> </tr>
    <tr> <td align="center"> 21 </td> <td align="center"> atoi :white_check_mark: </td> <td> This function converts the initial portion of the string pointed to
     by str to int representation. </td> </tr>
    <tr> <td align="center"> 22 </td> <td align="center"> calloc :white_check_mark: </td> <td> This function contiguously allocates enough space for count
     objects that are size bytes of memory each and returns a pointer to the
     allocated memory.  The allocated memory is filled with bytes of value
     zero. </td> </tr>
    <tr> <td align="center"> 23 </td> <td align="center"> strdup :white_check_mark: </td> <td> This function allocates sufficient memory for a copy of the
     string s1, does the copy, and returns a pointer to it. </td> </tr>
    <tr> <td align="center"> 23 </td> <td align="center"> ft_substr :white_check_mark: </td> <td> Allocates (with malloc(3)) and returns a substring from the string ’s’. The substring begins at index ’start’ and is of maximum size ’len’. </td> </tr>
    <tr> <td align="center"> 25 </td> <td align="center"> ft_strjoin :white_check_mark: </td> <td> Allocates (with malloc(3)) and returns a new string, which is the result of the concatenation of ’s1’ and ’s2’. </td> </tr>
    <tr> <td align="center"> 26 </td> <td align="center"> ft_strtrim :white_check_mark: </td> <td> Allocates (with malloc(3)) and returns a copy of ’s1’ with the characters specified in ’set’ removed from the beginning and the end of the string. </td> </tr>
    <tr> <td align="center"> 27 </td> <td align="center"> ft_split :white_check_mark: </td> <td> Allocates (with malloc(3)) and returns an array of strings obtained by splitting ’s’ using the character ’c’ as a delimiter. The array must end with a NULL pointer. </td> </tr>
    <tr> <td align="center"> 28 </td> <td align="center"> ft_itoa :white_check_mark: </td> <td> Allocates (with malloc(3)) and returns a string representing the integer received as an argument. Negative numbers must be handled. </td> </tr>
    <tr> <td align="center"> 29 </td> <td align="center"> ft_strmapi :white_check_mark: </td> <td> Applies the function ’f’ to each character of the string ’s’, and passing its index as first argument to create a new string (with malloc(3)) resulting from successive applications of ’f’. </td> </tr>
    <tr> <td align="center"> 30 </td> <td align="center"> ft_striteri :white_check_mark: </td> <td> Applies the function ’f’ on each character of the string passed as argument, passing its index as first argument. Each character is passed by address to ’f’ to be modified if necessary. </td> </tr>
    <tr> <td align="center"> 31 </td> <td align="center"> ft_putchar_fd :white_check_mark: </td> <td> Outputs the character ’c’ to the given file descriptor. </td> </tr>
    <tr> <td align="center"> 32 </td> <td align="center"> ft_putstr_fd :white_check_mark: </td> <td> Outputs the string ’s’ to the given file descriptor. </td> </tr>
    <tr> <td align="center"> 33 </td> <td align="center"> ft_putendl_fd :white_check_mark: </td> <td> Outputs the string ’s’ to the given file descriptor followed by a newline. </td> </tr>
    <tr> <td align="center"> 34 </td> <td align="center"> ft_putnbr_fd :white_check_mark: </td> <td> Outputs the integer ’n’ to the given file descriptor. </td> </tr>
  </tbody>
  <thead>
    <tr> <th colspan="3" align="center"> Bonus part </th>
  </thead>
  <tbody>
    <tr> <td align="center"> 1 </td> <td align="center"> ft_lstnew :white_check_mark: </td> <td> Allocates (with malloc(3)) and returns a new node. The member variable ’content’ is initialized with the value of the parameter ’content’. The variable ’next’ is initialized to NULL. </td> </tr>
    <tr> <td align="center"> 2 </td> <td align="center"> ft_lstadd_front :white_check_mark: </td> <td> Adds the node ’new’ at the beginning of the list. </td> </tr>
    <tr> <td align="center"> 3 </td> <td align="center"> ft_lstsize :white_check_mark: </td> <td> Counts the number of nodes in a list. </td> </tr>
    <tr> <td align="center"> 4 </td> <td align="center"> ft_lstlast :white_check_mark: </td> <td> Returns the last node of the list. </td> </tr>
    <tr> <td align="center"> 5 </td> <td align="center"> ft_lstadd_back :white_check_mark: </td> <td> Adds the node ’new’ at the end of the list. </td> </tr>
    <tr> <td align="center"> 6 </td> <td align="center"> ft_lstdelone :white_check_mark: </td> <td> Takes as a parameter a node and frees the memory of the node’s content using the function ’del’ given as a parameter and free the node. The memory of ’next’ must not be freed. </td> </tr>
    <tr> <td align="center"> 7 </td> <td align="center"> ft_lstclear :white_check_mark: </td> <td> Deletes and frees the given node and every successor of that node, using the function ’del’ and free(3). Finally, the pointer to the list must be set to NULL. </td> </tr>
    <tr> <td align="center"> 8 </td> <td align="center"> ft_lstiter :white_check_mark: </td> <td> Iterates the list ’lst’ and applies the function ’f’ on the content of each node. </td> </tr>
    <tr> <td align="center"> 9 </td> <td align="center"> ft_lstmap :white_check_mark: </td> <td> Iterates the list ’lst’ and applies the function ’f’ on the content of each node. Creates a new list resulting of the successive applications of the function ’f’. The ’del’ function is used to delete the content of a node if needed. </td> </tr>
  </tbody>
</table>
