# Plain Language Edits
[Style Guide](https://docs.google.com/document/d/1fFmIACgZe-kc9oVUfONt0GdFEgyLtVnKEoH2X4nF8uY/edit?usp=sharing)

## Document Revision Summary
We edited, revised, and redesigned our documents. 

- Simplified language and action verbs to be more straightforward
- Removed unecessary information
- Parsed down long-winded paragraphs/steps
- Edited for reuse in some topics (see conref elements)
- Used active voice when possible

## Examples

### Stain Removal

The original stain task topic was super long, so we [divided](https://github.com/ENG517/Topic-Model-8/commit/7ca0a5143877d0dd25d0b74939155d88a283f07d) it in two for simplicity. 

The original ```<shortdesc>``` lacked specificity about the task or purpose of the instructions.

The new version of ```<shortdesc>``` narrows the focus, making the description more task-oriented and actionable.
![Image 1 - Shortdesc comparison](assets/images/Screenshot%202024-12-10%20164033.png)

The original paragraph ```<prereq>``` has also been edited to get straight to the point

![Image 2 - The original and revised `<p>` comparison](assets/images/Screenshot%202024-12-10%20164846.png)

We simplified a lot of steps to make it easier for users to read and follow. For example the following ``` <choice> ``` statements were cut down, but sitll follow a similar structure. This improves the overall readability and cohesion of the list.

![Image 3 - The original and revised `<choice>` comparison](assets/images/Screenshot%202024-12-10%20165135.png)

### Drying Clothes in University Laundry Machines
- Commands like "Load wet clothes into the dryer drum" and "Close the dryer door" are concise and direct, following the plain language principle of focusing on the main action.
- Notes like "Check the lint trap to ensure it is clean" provide essential safety information without overloading the main instruction.
- The file avoids deixis (e.g., "as described above") and relies on explicit commands, which improves clarity and reusability.
- Added ```<id>``` and ```<conref>``` elements to topics to reuse similar elements ex. both laundry topics could use the same steps, but needed different introductions. Therefore, we used a conref element to use the exact same steps in both task topics. This improves cohesion (and makes future edits easier)
- Elements like ```<shortdesc>``` and ```<postreq>``` use conref elements to link to reusable content.
- [Drying clothes commit](https://github.com/ENG517/Topic-Model-8/pull/24/commits/e43c4e13574ea1ae2540d09d884051fc62d89b4a)

### Dita Maps
- All three ditamaps follow a similar logical structure that should follow a reader's train-of-throughout
- Ex. the communal map starts with broad information about clothing care, then washing information, and finally topics related to drying clothes.
- Maps needs to be [updated](https://github.com/ENG517/Topic-Model-8/pull/34/commits/fb24aea0bf26c0784bc52e6324c214857a3ce133) to account for new files and logic