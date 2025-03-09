# Struct: <code>kretprobe_instance</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct hlist_node hlist;
    struct kretprobe * rp;
    kprobe_opcode_t * ret_addr;
    struct task_struct * task;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct hlist_node hlist;
    struct kretprobe * rp;
    kprobe_opcode_t * ret_addr;
    struct task_struct * task;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct hlist_node hlist;
    struct kretprobe * rp;
    kprobe_opcode_t * ret_addr;
    struct task_struct * task;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct hlist_node hlist;
    struct kretprobe * rp;
    kprobe_opcode_t * ret_addr;
    struct task_struct * task;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct hlist_node hlist;
    struct kretprobe * rp;
    kprobe_opcode_t * ret_addr;
    struct task_struct * task;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct hlist_node hlist;
    struct kretprobe * rp;
    kprobe_opcode_t * ret_addr;
    struct task_struct * task;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct hlist_node hlist;
    struct kretprobe * rp;
    kprobe_opcode_t * ret_addr;
    struct task_struct * task;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct hlist_node hlist;
    struct kretprobe * rp;
    kprobe_opcode_t * ret_addr;
    struct task_struct * task;
    void * fp;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct hlist_node hlist;
    struct kretprobe * rp;
    kprobe_opcode_t * ret_addr;
    struct task_struct * task;
    void * fp;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct hlist_node hlist;
    struct kretprobe * rp;
    kprobe_opcode_t * ret_addr;
    struct task_struct * task;
    void * fp;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct freelist_node freelist;
    struct callback_head rcu;
    struct llist_node llist;
    struct kretprobe_holder * rph;
    kprobe_opcode_t * ret_addr;
    void * fp;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct freelist_node freelist;
    struct callback_head rcu;
    struct llist_node llist;
    struct kretprobe_holder * rph;
    kprobe_opcode_t * ret_addr;
    void * fp;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct freelist_node freelist;
    struct callback_head rcu;
    struct llist_node llist;
    struct kretprobe_holder * rph;
    kprobe_opcode_t * ret_addr;
    void * fp;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct rethook_node node;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct rethook_node node;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct rethook_node node;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct rethook_node node;
    char[0] data;
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
struct kretprobe_instance {
    struct hlist_node hlist;
    struct kretprobe * rp;
    kprobe_opcode_t * ret_addr;
    struct task_struct * task;
    void * fp;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct hlist_node hlist;
    struct kretprobe * rp;
    kprobe_opcode_t * ret_addr;
    struct task_struct * task;
    void * fp;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct hlist_node hlist;
    struct kretprobe * rp;
    kprobe_opcode_t * ret_addr;
    struct task_struct * task;
    void * fp;
    char[0] data;
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct hlist_node hlist;
    struct kretprobe * rp;
    kprobe_opcode_t * ret_addr;
    struct task_struct * task;
    void * fp;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct hlist_node hlist;
    struct kretprobe * rp;
    kprobe_opcode_t * ret_addr;
    struct task_struct * task;
    void * fp;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct hlist_node hlist;
    struct kretprobe * rp;
    kprobe_opcode_t * ret_addr;
    struct task_struct * task;
    void * fp;
    char[0] data;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct kretprobe_instance {
    struct hlist_node hlist;
    struct kretprobe * rp;
    kprobe_opcode_t * ret_addr;
    struct task_struct * task;
    void * fp;
    char[0] data;
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * fp</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>struct freelist_node freelist</code>
</li>
<li>
<b>Field added. </b>
<code>struct callback_head rcu</code>
</li>
<li>
<b>Field added. </b>
<code>struct llist_node llist</code>
</li>
<li>
<b>Field added. </b>
<code>struct kretprobe_holder * rph</code>
</li>
<li>
<b>Field removed. </b>
<code>struct hlist_node hlist</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kretprobe * rp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct task_struct * task</code>
</li>
</ul>
</details>
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
<b>Field added. </b>
<code>struct rethook_node node</code>
</li>
<li>
<b>Field removed. </b>
<code>struct freelist_node freelist</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head rcu</code>
</li>
<li>
<b>Field removed. </b>
<code>struct llist_node llist</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kretprobe_holder * rph</code>
</li>
<li>
<b>Field removed. </b>
<code>kprobe_opcode_t * ret_addr</code>
</li>
<li>
<b>Field removed. </b>
<code>void * fp</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct kretprobe_instance {
    struct hlist_node hlist;
    struct kretprobe * rp;
    kprobe_opcode_t * ret_addr;
    struct task_struct * task;
    void * fp;
    char[0] data;
}
```
</details>
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
