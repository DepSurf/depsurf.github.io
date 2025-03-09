# Struct: <code>rpc_task</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    int tk_rpc_status;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    int tk_rpc_status;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    int tk_rpc_status;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    int tk_rpc_status;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    int tk_rpc_status;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    int tk_rpc_status;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    int tk_rpc_status;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    int tk_rpc_status;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    int tk_rpc_status;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    int tk_rpc_status;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    int tk_rpc_status;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    int tk_rpc_status;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    int tk_rpc_status;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    int tk_rpc_status;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    int tk_rpc_status;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    int tk_rpc_status;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct rpc_cred * tk_op_cred</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int tk_rpc_status</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    int tk_rpc_status;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct rpc_task {
    atomic_t tk_count;
    int tk_status;
    struct list_head tk_task;
    void (*)(struct rpc_task *) tk_callback;
    void (*)(struct rpc_task *) tk_action;
    long unsigned int tk_timeout;
    long unsigned int tk_runstate;
    struct rpc_wait_queue * tk_waitqueue;
    union (anon) u;
    int tk_rpc_status;
    struct rpc_message tk_msg;
    void * tk_calldata;
    const struct rpc_call_ops * tk_ops;
    struct rpc_clnt * tk_client;
    struct rpc_xprt * tk_xprt;
    struct rpc_cred * tk_op_cred;
    struct rpc_rqst * tk_rqstp;
    struct workqueue_struct * tk_workqueue;
    ktime_t tk_start;
    pid_t tk_owner;
    short unsigned int tk_flags;
    short unsigned int tk_timeouts;
    short unsigned int tk_pid;
    unsigned char tk_priority;
    unsigned char tk_garb_retry;
    unsigned char tk_cred_retry;
    unsigned char tk_rebind_retry;
}
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned char tk_rebind_retry</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
