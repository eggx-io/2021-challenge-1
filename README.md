# eggX 2021 Challenge 1

Hello! 👋 This is the 1st of 2 challenges eggX will be putting out (think of a challenge like an extended hackathon with a specific focus).

You'll get to work on a theme (say design, algorithms, project management) for a couple weeks & get to present it at the end! 😎

## Dates

Start: 4th October

End: 31st October

## Details

Your challenge is to write a function (or several) that will process 4GB of random textual data. You can build the algorithm in whatever language you like.

### Objectives

* Generate a 4GB (4 * 10^9 bytes) file containing random text
  * only alphanumeric charaters and spaces are allowed
* Sort the character in your file
  * in order of ASCII code number
* Compress your file
  * using character-based lossless compression
  * the compressed file must only contain ASCII characters
* Overwrite the original file with the compressed output
  * you may use temporary files if needed

### Rubric

> To fully understand this rubric, you must first get acquainted with [Big Oh Notation](https://cglab.ca/~discmath/growth-of-functions.html) (which is something you're gonna need to know a lot about, so best to start early!)

The perfect solution will:

* Generate the original file in O(n) time complexity
* Sort the file in O(n * log(n)) time
* Compress the file in O(n) time
* Overwrite the original file in O(log(n)) time

Your solution will be tested on a virtual machine of the following configuration:

* 2.0 GHz 64-bit dual-core CPU
* 8 GB RAM
* 10 GB SSD
* CentOS Linux 8

Any binaries/executables/programs your function will need must be attached in your solution.

Your function must be able to be run via a single command: `./run`

You must assume that your function will only have access to the files in your solution folder.

### How to win

* Your solution must first meet all the rubric requirements
* Your solution must take the least time to complete
* Your solution must use the least amount of memory
* Your solution must use the least amount of storage

### Tips

To build the perfect solution try and consider these concepts:
* Iteration vs recursion
* sync vs async
* memory efficiency
* effects of accessing IO (files)

The more you know about the above, the more prepared you'll be not just to solve this challenge but to do very well in these Carleton classes:
* COMP 1805
* COMP 2402
* COMP 2804
* COMP 3000
* COMP 3804

... Not to mention the bucket loads of internships that'll be calling your name! 🤯

---

We'll be handing out prizes to 1st, 2nd, & 3rd placers & will make honorable mentions of people with unique solutions 👩‍🔬

This repository will be updated with various solutions once the challenge is over.

Good luck! 😁 🎉
