# Question 2 Explanation

This task created a secure project workspace and applied permissions to protect the stored files. The directory structure was created under q2/secure_workspace with docs, src, and logs, and the permissions were changed from broad 777 access to more restrictive 750 and 640 settings.

The resulting permissions limit access to the owner while keeping the project data safer from unauthorized users. The umask value of 0022 also confirms that newly created files will typically be readable and writable by the owner and readable by others.
