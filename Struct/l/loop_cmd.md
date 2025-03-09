# Struct: <code>loop_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct kthread_work work;
    struct request * rq;
    struct list_head list;
    bool use_aio;
    struct kiocb iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct kthread_work work;
    struct request * rq;
    struct list_head list;
    bool use_aio;
    struct kiocb iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct kthread_work work;
    struct request * rq;
    struct list_head list;
    bool use_aio;
    struct kiocb iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct kthread_work work;
    struct request * rq;
    struct list_head list;
    bool use_aio;
    long int ret;
    struct kiocb iocb;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct kthread_work work;
    struct request * rq;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * css;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct kthread_work work;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * css;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct kthread_work work;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * css;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct kthread_work work;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * css;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct kthread_work work;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * css;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct kthread_work work;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * css;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct kthread_work work;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * css;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct kthread_work work;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * css;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct list_head list_entry;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * blkcg_css;
    struct cgroup_subsys_state * memcg_css;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct list_head list_entry;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * blkcg_css;
    struct cgroup_subsys_state * memcg_css;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct list_head list_entry;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * blkcg_css;
    struct cgroup_subsys_state * memcg_css;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct list_head list_entry;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * blkcg_css;
    struct cgroup_subsys_state * memcg_css;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct list_head list_entry;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * blkcg_css;
    struct cgroup_subsys_state * memcg_css;
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
struct loop_cmd {
    struct kthread_work work;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * css;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct loop_cmd {
    struct kthread_work work;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * css;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct loop_cmd {
    struct kthread_work work;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * css;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct loop_cmd {
    struct kthread_work work;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * css;
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
struct loop_cmd {
    struct kthread_work work;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * css;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct kthread_work work;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * css;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct kthread_work work;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * css;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct loop_cmd {
    struct kthread_work work;
    bool use_aio;
    atomic_t ref;
    long int ret;
    struct kiocb iocb;
    struct bio_vec * bvec;
    struct cgroup_subsys_state * css;
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
<code>long int ret</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>atomic_t ref</code>
</li>
<li>
<b>Field added. </b>
<code>struct bio_vec * bvec</code>
</li>
<li>
<b>Field added. </b>
<code>struct cgroup_subsys_state * css</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head list</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct request * rq</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head list_entry</code>
</li>
<li>
<b>Field added. </b>
<code>struct cgroup_subsys_state * blkcg_css</code>
</li>
<li>
<b>Field added. </b>
<code>struct cgroup_subsys_state * memcg_css</code>
</li>
<li>
<b>Field removed. </b>
<code>struct kthread_work work</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cgroup_subsys_state * css</code>
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
