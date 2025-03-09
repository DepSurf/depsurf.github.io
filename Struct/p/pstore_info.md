# Struct: <code>pstore_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    char * name;
    spinlock_t buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(u64 *, enum pstore_type_id *, int *, struct timespec *, char * *, bool *, struct pstore_info *) read;
    int (*)(enum pstore_type_id, enum kmsg_dump_reason, u64 *, unsigned int, int, bool, size_t, struct pstore_info *) write;
    int (*)(enum pstore_type_id, enum kmsg_dump_reason, u64 *, unsigned int, const char *, bool, size_t, struct pstore_info *) write_buf;
    int (*)(enum pstore_type_id, u64, int, struct timespec, struct pstore_info *) erase;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    char * name;
    spinlock_t buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(u64 *, enum pstore_type_id *, int *, struct timespec *, char * *, bool *, ssize_t *, struct pstore_info *) read;
    int (*)(enum pstore_type_id, enum kmsg_dump_reason, u64 *, unsigned int, int, bool, size_t, struct pstore_info *) write;
    int (*)(enum pstore_type_id, enum kmsg_dump_reason, u64 *, unsigned int, const char *, bool, size_t, struct pstore_info *) write_buf;
    int (*)(enum pstore_type_id, u64, int, struct timespec, struct pstore_info *) erase;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    char * name;
    spinlock_t buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(u64 *, enum pstore_type_id *, int *, struct timespec *, char * *, bool *, ssize_t *, struct pstore_info *) read;
    int (*)(enum pstore_type_id, enum kmsg_dump_reason, u64 *, unsigned int, int, bool, size_t, struct pstore_info *) write;
    int (*)(enum pstore_type_id, enum kmsg_dump_reason, u64 *, unsigned int, const char *, bool, size_t, struct pstore_info *) write_buf;
    int (*)(enum pstore_type_id, enum kmsg_dump_reason, u64 *, unsigned int, const char *, bool, size_t, struct pstore_info *) write_buf_user;
    int (*)(enum pstore_type_id, u64, int, struct timespec, struct pstore_info *) erase;
    void * data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    char * name;
    spinlock_t buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    char * name;
    spinlock_t buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    char * name;
    spinlock_t buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    char * name;
    struct semaphore buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    char * name;
    struct semaphore buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    char * name;
    struct semaphore buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    const char * name;
    struct semaphore buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    int max_reason;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    const char * name;
    struct semaphore buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    int max_reason;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    const char * name;
    struct semaphore buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    int max_reason;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    const char * name;
    struct semaphore buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    int max_reason;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    const char * name;
    spinlock_t buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    int max_reason;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    const char * name;
    spinlock_t buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    int max_reason;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    const char * name;
    spinlock_t buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    int max_reason;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    const char * name;
    spinlock_t buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    int max_reason;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
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
struct pstore_info {
    struct module * owner;
    char * name;
    struct semaphore buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    char * name;
    struct semaphore buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    char * name;
    struct semaphore buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    char * name;
    struct semaphore buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
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
struct pstore_info {
    struct module * owner;
    char * name;
    struct semaphore buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    char * name;
    struct semaphore buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    char * name;
    struct semaphore buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pstore_info {
    struct module * owner;
    char * name;
    struct semaphore buf_lock;
    char * buf;
    size_t bufsize;
    struct mutex read_mutex;
    int flags;
    void * data;
    int (*)(struct pstore_info *) open;
    int (*)(struct pstore_info *) close;
    ssize_t (*)(struct pstore_record *) read;
    int (*)(struct pstore_record *) write;
    int (*)(struct pstore_record *, const char *) write_user;
    int (*)(struct pstore_record *) erase;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>ssize_t (*)(u64 *, enum pstore_type_id *, int *, struct timespec *, char * *, bool *, struct pstore_info *) read</code> ➡️ <code>ssize_t (*)(u64 *, enum pstore_type_id *, int *, struct timespec *, char * *, bool *, ssize_t *, struct pstore_info *) read</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(enum pstore_type_id, enum kmsg_dump_reason, u64 *, unsigned int, const char *, bool, size_t, struct pstore_info *) write_buf_user</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct pstore_record *, const char *) write_user</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(enum pstore_type_id, enum kmsg_dump_reason, u64 *, unsigned int, const char *, bool, size_t, struct pstore_info *) write_buf</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(enum pstore_type_id, enum kmsg_dump_reason, u64 *, unsigned int, const char *, bool, size_t, struct pstore_info *) write_buf_user</code>
</li>
<li>
<b>Field type changed. </b>
<code>ssize_t (*)(u64 *, enum pstore_type_id *, int *, struct timespec *, char * *, bool *, ssize_t *, struct pstore_info *) read</code> ➡️ <code>ssize_t (*)(struct pstore_record *) read</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(enum pstore_type_id, enum kmsg_dump_reason, u64 *, unsigned int, int, bool, size_t, struct pstore_info *) write</code> ➡️ <code>int (*)(struct pstore_record *) write</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(enum pstore_type_id, u64, int, struct timespec, struct pstore_info *) erase</code> ➡️ <code>int (*)(struct pstore_record *) erase</code>
</li>
</ul>
</details>
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
<b>Field type changed. </b>
<code>spinlock_t buf_lock</code> ➡️ <code>struct semaphore buf_lock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<code>int max_reason</code>
</li>
<li>
<b>Field type changed. </b>
<code>char * name</code> ➡️ <code>const char * name</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct semaphore buf_lock</code> ➡️ <code>spinlock_t buf_lock</code>
</li>
</ul>
</details>
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
