 **Multi-threading** | **Multi-tasking(Async)**
 --------------- | -------------
 Multi-threading is thread-based multitasking. | Multi-tasking is logical extention to multi-programming.
 Multi-threaded programming engages multiple threads | Async programming is single threaded but performing multiple operations on a single thread.
 We face 2 overheads in Multi-threading,which are: <br/> 1. Switching, data sharing <br/> 2. Using some of the resources when sitting idle. | To overcome those overheads we use Asynchronous programming(Multi-tasking).
 In Rust, As multithreading causes different threads work at the same time, therefore a thread safety and memory safety catered by borrwing n ownership feature. | In Rust, async fn creates an asynchronous function which returns a Future.
 I don't get the connection bewteen Fearless concurrency n multithreaidng | Future needs to be run on an Executor, so that a task get done.
 We use multithreading when thread is CPU intensive | We use mutitasking when thread is I/O intensive.
 
