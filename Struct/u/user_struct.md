# Struct: <code>user_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct user_struct {
    atomic_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t inotify_watches;
    atomic_t inotify_devs;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct key * uid_keyring;
    struct key * session_keyring;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct user_struct {
    atomic_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t inotify_watches;
    atomic_t inotify_devs;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct key * uid_keyring;
    struct key * session_keyring;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct user_struct {
    atomic_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t inotify_watches;
    atomic_t inotify_devs;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct key * uid_keyring;
    struct key * session_keyring;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct user_struct {
    atomic_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct key * uid_keyring;
    struct key * session_keyring;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct user_struct {
    atomic_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct key * uid_keyring;
    struct key * session_keyring;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct user_struct {
    atomic_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct key * uid_keyring;
    struct key * session_keyring;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    struct ratelimit_state ratelimit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct user_struct {
    refcount_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct key * uid_keyring;
    struct key * session_keyring;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    struct ratelimit_state ratelimit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct user_struct {
    refcount_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    struct ratelimit_state ratelimit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct user_struct {
    refcount_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    struct ratelimit_state ratelimit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct user_struct {
    refcount_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    atomic_t nr_watches;
    struct ratelimit_state ratelimit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct user_struct {
    refcount_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    atomic_t nr_watches;
    struct ratelimit_state ratelimit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct user_struct {
    refcount_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    atomic_t nr_watches;
    struct ratelimit_state ratelimit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct user_struct {
    refcount_t __count;
    struct percpu_counter epoll_watches;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    atomic_t nr_watches;
    struct ratelimit_state ratelimit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct user_struct {
    refcount_t __count;
    struct percpu_counter epoll_watches;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    atomic_t nr_watches;
    struct ratelimit_state ratelimit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct user_struct {
    refcount_t __count;
    struct percpu_counter epoll_watches;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    atomic_t nr_watches;
    struct ratelimit_state ratelimit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct user_struct {
    refcount_t __count;
    struct percpu_counter epoll_watches;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    atomic_t nr_watches;
    struct ratelimit_state ratelimit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct user_struct {
    refcount_t __count;
    struct percpu_counter epoll_watches;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    atomic_t nr_watches;
    struct ratelimit_state ratelimit;
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
struct user_struct {
    refcount_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    struct ratelimit_state ratelimit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct user_struct {
    refcount_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    struct ratelimit_state ratelimit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct user_struct {
    refcount_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    struct ratelimit_state ratelimit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct user_struct {
    refcount_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    struct ratelimit_state ratelimit;
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
struct user_struct {
    refcount_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    struct ratelimit_state ratelimit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct user_struct {
    refcount_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    struct ratelimit_state ratelimit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct user_struct {
    refcount_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    struct ratelimit_state ratelimit;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct user_struct {
    refcount_t __count;
    atomic_t processes;
    atomic_t sigpending;
    atomic_t fanotify_listeners;
    atomic_long_t epoll_watches;
    long unsigned int mq_bytes;
    long unsigned int locked_shm;
    long unsigned int unix_inflight;
    atomic_long_t pipe_bufs;
    struct hlist_node uidhash_node;
    kuid_t uid;
    atomic_long_t locked_vm;
    struct ratelimit_state ratelimit;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>atomic_t inotify_watches</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t inotify_devs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct ratelimit_state ratelimit</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>atomic_t __count</code> ➡️ <code>refcount_t __count</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct key * uid_keyring</code>
</li>
<li>
<b>Field removed. </b>
<code>struct key * session_keyring</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>atomic_t nr_watches</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>atomic_t fanotify_listeners</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>atomic_t processes</code>
</li>
<li>
<b>Field removed. </b>
<code>atomic_t sigpending</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int mq_bytes</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int locked_shm</code>
</li>
<li>
<b>Field type changed. </b>
<code>atomic_long_t epoll_watches</code> ➡️ <code>struct percpu_counter epoll_watches</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
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
