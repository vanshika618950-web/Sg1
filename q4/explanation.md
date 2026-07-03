# Question 4 Explanation

This task explored file access and I/O behavior by opening a file through a file descriptor and then redirecting stdout, stderr, and combined output to files. The investigation showed that file descriptors 0, 1, and 2 represent standard input, output, and error, while the opened log file was assigned descriptor 3.

The output files showed how Linux separates normal output from error output and how shell redirection can combine them into one stream for easier troubleshooting.
