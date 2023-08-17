<h1 align=center>
	<b>get_next_line</b>
	 
  <i>42cursus' project #4</i>
</h2>
May it be a file, stdin, or even later a network connection, you will always need a way to read content line by line. It is time to start working on this function, which will be essential for your future projects. In this repo you will find all the files regarding the implementations of the <b>get_next_line</b> functions.
  <h1 align=center>

![get_next_linee](https://github.com/spnzed/get_next_line/assets/95354392/dbf1d6c4-108f-462b-b890-f8d3240f2cc4)


---

<h3 align=center>
Mandatory
</h3>

> <i>Calling the function `get_next_line` in a loop will then allow the user to read the text available on the file descriptor one line at a time until the end of it. It has to behave well both on external files and standard input. The function should return the line that has just been read. If there is nothing else to read or if an error has occurred it should return NULL. The <b>mandatory</b> part must deal with at least one file descriptor at a time, and can have more than one static variable.</i>

---

<h2>
The project
</h2>

### Mandatory implementation

- [`header file`](get_next_line.h)
- [`get_next_line`](get_next_line.c)	- the main function and its additionals
- [`get_next_line_utils`](get_next_line_utils.c)	- additional functions from [`libft`](https://github.com/caroldaniel/42sp-cursus-libft)

---
<h2>
Usage
</h2>

### Instructions

When compiling `get_next_line`, be sure to include the following flags

```sh
$> gcc -Wall -Wextra -Werror -D BUFFER_SIZE=xxx <files>.c.
```

Where the `xxx` can be substituted by the number of bytes read at a time into the buffer for the `read` function. 
