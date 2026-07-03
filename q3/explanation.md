# Question 3 Explanation

This task investigated hard links and symbolic links by creating a regular file, a hard link, and a symbolic link. The inode data showed that the original file and the hard link share the same inode, while the symbolic link uses a separate inode and points to the original path.

Deleting the original file preserved the hard link because both names still refer to the same file data, but the symbolic link broke because it pointed to a path that no longer existed.
