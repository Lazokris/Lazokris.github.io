---
layout: essay
type: essay
title: A tool for better programing
# All dates must be YYYY-MM-DD format!
date: 2021-09-23
labels:
- Software Engineering
- Learning
- Coding Standards
---

## What is Coding Standards
Coding standards are rules and guidelines that define how programmers should write a program. For example, in JavaScript Primitive Data Type, the use of var is to be avoided; this is because var is a global Data Type meaning its value can be reassigned, leading to bugs in your program. Instead, the use of const and let is referred to because of their local scope.

```
    // bad
    var a = 1;
    var b = 2;
    // good 
    const a = 1;
    const b = 2;
    /* from https://github.com/airbnb/javascript */
```


## Why is Coding Standards important
Coding Standards are essential in ensuring a common look at how to write a program. It detects and removes coding mistakes that are associated with a language to ensure coding quality. Having well-defined Coding Standards can easily help detect errors and bugs that can be hard to manage once a code is written in the thousand.


## How to Implement Coding Standards
Implementing a Coding Standard can be impossible without the help of automated tools. Tools like EsLint for JavaScript or Checkstyle for Java automatically error check codes in runtime. Every or most Tech firm requires coding standards because it makes the maintenance of codes much easier.

```
JAVA checkstlyle
[ERROR] LinkedList.java:166:7: Unused @param tag for 'T'. [JavadocMethod]
[ERROR] LinkedList.java:169:26: Expected @param tag for 'item'. [JavadocMethod]
[ERROR] LinkedList.java:169:31: '{' is not preceded with whitespace. [WhitespaceAround]
JavaScript ESLint
ESLint: Too many blank lines at the end of file. Max of 0 allowed. (no-multiple-empty-lines)
ESLint: Requires a space before '}'. (block-spacing)
```

## Main aspects of Coding Standard
Some of the aspects of a Coding Standard are listed.  Naming a variable must be in a camelCase form. If the Data Type variable is two syllables (i.e., getting total array), you could name the variable totalArr, tArr, or totalArray. Indentation is another Coding Standard that is widely enforced. As well as having Comments to explain how your code is written. Having standard indentation and explanatory comments can help with the readability of your code, which can then help others to debug them.

```
 /**
 * A generic list of linked nodes.
 * Also has a driver main method.
 * @param <T> the type of object list holds.
 * @author Kristian Lazo
 * @since 10/1/2020
 */
public class LinkedList<T> implements ListInterface<T> {

	/** reference to first node in the linked list (linked nodes). */
   protected Node<T> head = null;
	/**Total number of items, used
	*for error checking and node removal.*/
   protected Integer size = new Integer(0);

	/** Constructor with no parameters. */
   public LinkedList() {
   	// no code, because data fields already initialized
   }

```
