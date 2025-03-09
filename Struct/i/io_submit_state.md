# Struct: <code>io_submit_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct io_submit_state {
    struct blk_plug plug;
    void *[8] reqs;
    unsigned int free_reqs;
    unsigned int cur_req;
    struct file * file;
    unsigned int fd;
    unsigned int has_refs;
    unsigned int used_refs;
    unsigned int ios_left;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct io_submit_state {
    struct blk_plug plug;
    void *[8] reqs;
    unsigned int free_reqs;
    unsigned int cur_req;
    struct file * file;
    unsigned int fd;
    unsigned int has_refs;
    unsigned int used_refs;
    unsigned int ios_left;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_submit_state {
    struct blk_plug plug;
    void *[8] reqs;
    unsigned int free_reqs;
    struct file * file;
    unsigned int fd;
    unsigned int has_refs;
    unsigned int used_refs;
    unsigned int ios_left;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct io_submit_state {
    struct blk_plug plug;
    void *[8] reqs;
    unsigned int free_reqs;
    bool plug_started;
    struct io_comp_state comp;
    struct file * file;
    unsigned int fd;
    unsigned int file_refs;
    unsigned int ios_left;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct io_submit_state {
    struct blk_plug plug;
    struct io_submit_link link;
    void *[32] reqs;
    unsigned int free_reqs;
    bool plug_started;
    struct io_comp_state comp;
    struct file * file;
    unsigned int fd;
    unsigned int file_refs;
    unsigned int ios_left;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_submit_state {
    struct blk_plug plug;
    struct io_submit_link link;
    void *[32] reqs;
    unsigned int free_reqs;
    bool plug_started;
    struct io_kiocb *[32] compl_reqs;
    unsigned int compl_nr;
    struct list_head free_list;
    unsigned int ios_left;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct io_submit_state {
    struct io_wq_work_node free_list;
    struct io_wq_work_list compl_reqs;
    struct io_submit_link link;
    bool plug_started;
    bool need_plug;
    bool flush_cqes;
    short unsigned int submit_nr;
    struct blk_plug plug;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct io_submit_state {
    struct io_wq_work_node free_list;
    struct io_wq_work_list compl_reqs;
    struct io_submit_link link;
    bool plug_started;
    bool need_plug;
    short unsigned int submit_nr;
    unsigned int cqes_count;
    struct blk_plug plug;
    struct io_uring_cqe[16] cqes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct io_submit_state {
    struct io_wq_work_node free_list;
    struct io_wq_work_list compl_reqs;
    struct io_submit_link link;
    bool plug_started;
    bool need_plug;
    short unsigned int submit_nr;
    unsigned int cqes_count;
    struct blk_plug plug;
    struct io_uring_cqe[16] cqes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct io_submit_state {
    struct io_wq_work_node free_list;
    struct io_wq_work_list compl_reqs;
    struct io_submit_link link;
    bool plug_started;
    bool need_plug;
    short unsigned int submit_nr;
    unsigned int cqes_count;
    struct blk_plug plug;
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
struct io_submit_state {
    struct blk_plug plug;
    void *[8] reqs;
    unsigned int free_reqs;
    unsigned int cur_req;
    struct file * file;
    unsigned int fd;
    unsigned int has_refs;
    unsigned int used_refs;
    unsigned int ios_left;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct io_submit_state {
    struct blk_plug plug;
    void *[8] reqs;
    unsigned int free_reqs;
    unsigned int cur_req;
    struct file * file;
    unsigned int fd;
    unsigned int has_refs;
    unsigned int used_refs;
    unsigned int ios_left;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct io_submit_state {
    struct blk_plug plug;
    void *[8] reqs;
    unsigned int free_reqs;
    unsigned int cur_req;
    struct file * file;
    unsigned int fd;
    unsigned int has_refs;
    unsigned int used_refs;
    unsigned int ios_left;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct io_submit_state {
    struct blk_plug plug;
    void *[8] reqs;
    unsigned int free_reqs;
    unsigned int cur_req;
    struct file * file;
    unsigned int fd;
    unsigned int has_refs;
    unsigned int used_refs;
    unsigned int ios_left;
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
struct io_submit_state {
    struct blk_plug plug;
    void *[8] reqs;
    unsigned int free_reqs;
    unsigned int cur_req;
    struct file * file;
    unsigned int fd;
    unsigned int has_refs;
    unsigned int used_refs;
    unsigned int ios_left;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct io_submit_state {
    struct blk_plug plug;
    void *[8] reqs;
    unsigned int free_reqs;
    unsigned int cur_req;
    struct file * file;
    unsigned int fd;
    unsigned int has_refs;
    unsigned int used_refs;
    unsigned int ios_left;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct io_submit_state {
    struct blk_plug plug;
    void *[8] reqs;
    unsigned int free_reqs;
    unsigned int cur_req;
    struct file * file;
    unsigned int fd;
    unsigned int has_refs;
    unsigned int used_refs;
    unsigned int ios_left;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct io_submit_state {
    struct blk_plug plug;
    void *[8] reqs;
    unsigned int free_reqs;
    unsigned int cur_req;
    struct file * file;
    unsigned int fd;
    unsigned int has_refs;
    unsigned int used_refs;
    unsigned int ios_left;
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct io_submit_state {
    struct blk_plug plug;
    void *[8] reqs;
    unsigned int free_reqs;
    unsigned int cur_req;
    struct file * file;
    unsigned int fd;
    unsigned int has_refs;
    unsigned int used_refs;
    unsigned int ios_left;
}
```
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
<b>Field removed. </b>
<code>unsigned int cur_req</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool plug_started</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_comp_state comp</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int file_refs</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int has_refs</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int used_refs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct io_submit_link link</code>
</li>
<li>
<b>Field type changed. </b>
<code>void *[8] reqs</code> ➡️ <code>void *[32] reqs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct io_kiocb *[32] compl_reqs</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int compl_nr</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head free_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_comp_state comp</code>
</li>
<li>
<b>Field removed. </b>
<code>struct file * file</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int fd</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int file_refs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool need_plug</code>
</li>
<li>
<b>Field added. </b>
<code>bool flush_cqes</code>
</li>
<li>
<b>Field added. </b>
<code>short unsigned int submit_nr</code>
</li>
<li>
<b>Field removed. </b>
<code>void *[32] reqs</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int free_reqs</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int compl_nr</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int ios_left</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct io_kiocb *[32] compl_reqs</code> ➡️ <code>struct io_wq_work_list compl_reqs</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head free_list</code> ➡️ <code>struct io_wq_work_node free_list</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int cqes_count</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_uring_cqe[16] cqes</code>
</li>
<li>
<b>Field removed. </b>
<code>bool flush_cqes</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct io_uring_cqe[16] cqes</code>
</li>
</ul>
</details>
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
