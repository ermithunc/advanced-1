\# Docker Learnings



\## How do I know whether I am inside or outside the Docker container?



\### Outside the container

I am working on my local Windows machine.



Example:

D:\\advanced\\advanced-1



PowerShell prompt:

PS D:\\advanced\\advanced-1>



\### Inside the container

The commands are being executed by GitHub Actions inside the Docker container.



A useful check is:



```bash

cat /etc/os-release

