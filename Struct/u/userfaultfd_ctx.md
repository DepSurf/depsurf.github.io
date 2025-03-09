# Struct: <code>userfaultfd_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    struct seqcount refile_seq;
    atomic_t refcount;
    unsigned int flags;
    enum userfaultfd_state state;
    bool released;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    struct seqcount refile_seq;
    atomic_t refcount;
    unsigned int flags;
    enum userfaultfd_state state;
    bool released;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    struct seqcount refile_seq;
    atomic_t refcount;
    unsigned int flags;
    enum userfaultfd_state state;
    bool released;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    struct seqcount refile_seq;
    atomic_t refcount;
    unsigned int flags;
    unsigned int features;
    enum userfaultfd_state state;
    bool released;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    struct seqcount refile_seq;
    atomic_t refcount;
    unsigned int flags;
    unsigned int features;
    enum userfaultfd_state state;
    bool released;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    struct seqcount refile_seq;
    atomic_t refcount;
    unsigned int flags;
    unsigned int features;
    enum userfaultfd_state state;
    bool released;
    bool mmap_changing;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    struct seqcount refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    enum userfaultfd_state state;
    bool released;
    bool mmap_changing;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    struct seqcount refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    enum userfaultfd_state state;
    bool released;
    bool mmap_changing;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    struct seqcount refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    enum userfaultfd_state state;
    bool released;
    bool mmap_changing;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    struct seqcount refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    enum userfaultfd_state state;
    bool released;
    bool mmap_changing;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    seqcount_spinlock_t refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    enum userfaultfd_state state;
    bool released;
    bool mmap_changing;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    seqcount_spinlock_t refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    enum userfaultfd_state state;
    bool released;
    bool mmap_changing;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    seqcount_spinlock_t refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    bool released;
    atomic_t mmap_changing;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    seqcount_spinlock_t refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    bool released;
    atomic_t mmap_changing;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    seqcount_spinlock_t refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    bool released;
    atomic_t mmap_changing;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    seqcount_spinlock_t refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    bool released;
    atomic_t mmap_changing;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    seqcount_spinlock_t refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    bool released;
    atomic_t mmap_changing;
    struct mm_struct * mm;
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
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    struct seqcount refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    enum userfaultfd_state state;
    bool released;
    bool mmap_changing;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    struct seqcount refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    enum userfaultfd_state state;
    bool released;
    bool mmap_changing;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    struct seqcount refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    enum userfaultfd_state state;
    bool released;
    bool mmap_changing;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    struct seqcount refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    enum userfaultfd_state state;
    bool released;
    bool mmap_changing;
    struct mm_struct * mm;
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
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    struct seqcount refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    enum userfaultfd_state state;
    bool released;
    bool mmap_changing;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    struct seqcount refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    enum userfaultfd_state state;
    bool released;
    bool mmap_changing;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    struct seqcount refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    enum userfaultfd_state state;
    bool released;
    bool mmap_changing;
    struct mm_struct * mm;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct userfaultfd_ctx {
    wait_queue_head_t fault_pending_wqh;
    wait_queue_head_t fault_wqh;
    wait_queue_head_t fd_wqh;
    wait_queue_head_t event_wqh;
    struct seqcount refile_seq;
    refcount_t refcount;
    unsigned int flags;
    unsigned int features;
    enum userfaultfd_state state;
    bool released;
    bool mmap_changing;
    struct mm_struct * mm;
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
<b>Field added. </b>
<code>wait_queue_head_t event_wqh</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int features</code>
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
<code>bool mmap_changing</code>
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
<code>atomic_t refcount</code> ➡️ <code>refcount_t refcount</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct seqcount refile_seq</code> ➡️ <code>seqcount_spinlock_t refile_seq</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>enum userfaultfd_state state</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool mmap_changing</code> ➡️ <code>atomic_t mmap_changing</code>
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
