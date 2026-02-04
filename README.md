# common_decoraters
A lightweight collection of commonly used Python decorators, created primarily for learning and experimentation. While existing libraries such as logging, functools.wraps, Loguru, and structlog provide far more advanced and production-ready solutions, this repository serves as an educational reference for understanding how decorators work under the hood.

The goal of this project is to provide clear, self-written examples that help build intuition about decorator patterns, enable the creation of project-specific decorators, and offer a space to collect useful decorator ideas that are not available in standard libraries. It also reflects a preference for transparent, locally maintained code where appropriate, rather than relying solely on external dependencies.


________________________________________________________________________________________________________________________________________________________________

# How to use
Its adviced to trie out the diffrent decoraters and see which properties each decorater has. 
Here is a simple example of how a function could be used:
<img width="1138" height="786" alt="docorater1" src="https://github.com/user-attachments/assets/1b53d61c-f72a-4cf9-a1fd-93c6a6af2477" />

Get familiar with the filename and the decorator function, expecially the filename and location is relevant for the Import.
Use the decorator like shown below or use "import common_decorater.wrapper_of_func" and "@wrapper_of_func", should work either way:
<img width="1138" height="634" alt="docorater1_used" src="https://github.com/user-attachments/assets/f1f60e9b-e3e8-4775-a56a-1ea285c253f1" />

Output looks like this:

<img width="766" height="127" alt="image" src="https://github.com/user-attachments/assets/8b09ee71-9f61-47c6-a8b9-27b7c481c7b9" />


Tip: Feel free to play around see what happens with diffrent properties. Maybe delete the "*args, **kwargs" from the code and see what happens if you pass in a function with one or several arguments, like func(4, 5). 
__________________________________________________________________________________________________________________________________________________________________





