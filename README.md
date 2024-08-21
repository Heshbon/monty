# C - Stacks, Queues - LIFO, FIFO

This project focuses on implementing and understanding two fundamental data structures in C: Stacks and Queues. In this project, I learned about the concepts of Last In, First Out (LIFO) and First In, First Out (FIFO) and how to apply these concepts to practical programming problems.

## Learning Objectives

By the end of this project, I was able to:

- Explain LIFO (Last In, First Out) and FIFO (First In, First Out) data structures.
- Describe what a stack is and identify scenarios where it is useful.
- Describe what a queue is and identify scenarios where it is useful.
- Understand common implementations of stacks and queues.
- Identify and apply common use cases for stacks and queues.
- Use global variables appropriately and understand the implications.

## How to Contribute

- Fork the repository and make your changes on a separate branch.
- Ensure your code adheres to the Betty style.
- Submit a pull request with a clear description of your changes.

## Submission

- Ensure all code is complete and adheres to the requirements.
- Push your final changes to your repository.
- Make sure all files are included, and the header file is present and correct.

## 🔧 Monty Opcodes

 - push

	- Usage: push <int>
	- Pushes an element to the stack.
	- The parameter <int> must be an integer.

 - pall

	- Prints all values in the stack/queue, starting from the top.

 - pint

	- Prints the top value of the stack/queue.

 - pop

	- Removes the top element of the stack/queue.

 - swap

	- Swaps the top two elements of the stack/queue.

 - add

	- Adds the top two elements of the stack/queue.

	- The result is stored in the second element from the top and the top element is popped.

 - nop

        - Does not do anything.

 - sub

	- Subtracts the top element of the stack/queue from the second element from the top.

	- The result is stored in the second element from the top and the top element is removed.


 - div

        - Divides the second element from the top of the stack/queue by the top element.

        - The result is stored in the second element from the top and the top element is removed.

 - mul

	- Multiplies the top two elements of the stack/queue.

	- The result is stored in the second element from the top and the top element is removed.

 - mod

	- Computes the modulus of the second element from the top of the stack/queue divided by the top element.

	- The result is stored in the second element from the top and the top element is removed.

 - pchar

	- Prints the character value of the top element of the stack/queue.

	- The integer at the top is treated as an ASCII value.

 - pstr

	- Prints the string contained in the stack/queue.

	- Prints characters element by element until the stack/queue is empty, a value is 0, or an error occurs.

 - rotl

	- Rotates the top element of the stack/queue to the bottom.
 - rotr

	- Rotates the bottom element of the stack/queue to the top.

 - stack

	- Switches a queue to stack mode.
 - queue

	- Switches a stack to queue mode.

## 📘 Authors

  - Hesbon Kipchirchir <u>[Heshbon](https://github.com/Heshbon)</u>.

## 🔍 License

  - This project is licensed under the MIT License - see the <[LICENSE.md](https://github.com/Heshbon/monty/blob/master/LICENSE.md) file for details

## 📣 Acknowledgments

  - ALX Africa(providing guidance)
