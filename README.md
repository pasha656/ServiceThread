## Service & Thread

Examples of using Service and Thread:

**Service**
- BroadcastReceiver - Send data between Activity and Service using BroadcastReceiver
- PendingIntentService - Send data between Activity and Service using PendingIntent
- LocalBindingService - Send data between Activity and Service using LocalBinding
- AidlService - Send data between Activity and Service using AIDL **(differents processes)**
- MessengerService - Send data between Activity and Service using Messenger **(differents processes)**

**Thread**
- SerialTaskThread - Serial tasks, combining tasks into a chain
- ParallelTaskThread - Concurrency execution of several independent tasks **(but general result)**
- SingleThreadExecutor - Single thread for a long task (using ExecutorService)
- CallableTaskExecutor - Executor with Callable and result from Future