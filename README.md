# xv6Scheduling

This is a small project I did with the xv6 kernel. I changed around the scheduling policies, thus allowing for child processes to finish before their parents. You can choose which policy happens when it runs. I also implemented a stride scheduling policy. There are multiple test files in here to show the reults of my work.

## Usage

:$ make qemu-nox

   This starts up the kernel and takes you to a new screen, from here you can do different system calls or run my test files
   
:$ fork_rc_test 0

    test that shows parent finishing first
:$ fork_rc_test 1

    test that shows child finishing first
:$ schdtest

    shows results of multiple tests involving the stride scheduling policy
:$ shutdown

    turn off xv6
