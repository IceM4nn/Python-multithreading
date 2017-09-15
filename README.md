# Python mutithreading
Simple Python threading implementation.

```
usage: multithreading [-h] [-s] [-d DELAY] thread count

Multi-threading counter. By IceM4nn

positional arguments:
  thread                State the number of concurrent thread.
  count                 State the number count value for the thread. The
                        number in count will decrement until it reaches 0.

optional arguments:
  -h, --help            show this help message and exit
  -s, --synchronize     Run the thread with synchronize. Default is false
  -d DELAY, --delay DELAY
                        Give a delay to threads in seconds. Default is 2

```

Sample output
```
$ ./multithreading 2 3 --synchronize
[i] You have specify 2 number of thread(s).
[i] Every thread will count 3 concurrently until it reaches 0.
[i] Synchronize is set to True
[i] Delay value is 2 seconds

[+] Starting Thread-1
[+] Starting Thread-2
Thread-1: Fri Sep 15 18:51:56 2017
Thread-2: Fri Sep 15 18:51:56 2017
Thread-1: Fri Sep 15 18:51:58 2017
Thread-2: Fri Sep 15 18:51:58 2017
Thread-1: Fri Sep 15 18:52:00 2017
Thread-2: Fri Sep 15 18:52:00 2017
Done. Exiting Main Thread
```
