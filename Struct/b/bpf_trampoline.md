# Struct: <code>bpf_trampoline</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_trampoline {
    struct hlist_node hlist;
    struct mutex mutex;
    refcount_t refcnt;
    u64 key;
    struct (anon) func;
    struct bpf_prog * extension_prog;
    struct hlist_head[3] progs_hlist;
    int[3] progs_cnt;
    void * image;
    u64 selector;
    struct bpf_ksym ksym;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_trampoline {
    struct hlist_node hlist;
    struct mutex mutex;
    refcount_t refcnt;
    u64 key;
    struct (anon) func;
    struct bpf_prog * extension_prog;
    struct hlist_head[3] progs_hlist;
    int[3] progs_cnt;
    struct bpf_tramp_image * cur_image;
    u64 selector;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_trampoline {
    struct hlist_node hlist;
    struct mutex mutex;
    refcount_t refcnt;
    u64 key;
    struct (anon) func;
    struct bpf_prog * extension_prog;
    struct hlist_head[3] progs_hlist;
    int[3] progs_cnt;
    struct bpf_tramp_image * cur_image;
    u64 selector;
    struct module * mod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_trampoline {
    struct hlist_node hlist;
    struct mutex mutex;
    refcount_t refcnt;
    u64 key;
    struct (anon) func;
    struct bpf_prog * extension_prog;
    struct hlist_head[3] progs_hlist;
    int[3] progs_cnt;
    struct bpf_tramp_image * cur_image;
    u64 selector;
    struct module * mod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_trampoline {
    struct hlist_node hlist;
    struct mutex mutex;
    refcount_t refcnt;
    u64 key;
    struct (anon) func;
    struct bpf_prog * extension_prog;
    struct hlist_head[3] progs_hlist;
    int[3] progs_cnt;
    struct bpf_tramp_image * cur_image;
    u64 selector;
    struct module * mod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_trampoline {
    struct hlist_node hlist;
    struct ftrace_ops * fops;
    struct mutex mutex;
    refcount_t refcnt;
    u32 flags;
    u64 key;
    struct (anon) func;
    struct bpf_prog * extension_prog;
    struct hlist_head[3] progs_hlist;
    int[3] progs_cnt;
    struct bpf_tramp_image * cur_image;
    u64 selector;
    struct module * mod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_trampoline {
    struct hlist_node hlist;
    struct ftrace_ops * fops;
    struct mutex mutex;
    refcount_t refcnt;
    u32 flags;
    u64 key;
    struct (anon) func;
    struct bpf_prog * extension_prog;
    struct hlist_head[3] progs_hlist;
    int[3] progs_cnt;
    struct bpf_tramp_image * cur_image;
    struct module * mod;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_trampoline {
    struct hlist_node hlist;
    struct ftrace_ops * fops;
    struct mutex mutex;
    refcount_t refcnt;
    u32 flags;
    u64 key;
    struct (anon) func;
    struct bpf_prog * extension_prog;
    struct hlist_head[3] progs_hlist;
    int[3] progs_cnt;
    struct bpf_tramp_image * cur_image;
    struct module * mod;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct bpf_trampoline {
    struct hlist_node hlist;
    struct mutex mutex;
    refcount_t refcnt;
    u64 key;
    struct (anon) func;
    struct bpf_prog * extension_prog;
    struct hlist_head[3] progs_hlist;
    int[3] progs_cnt;
    void * image;
    u64 selector;
    struct bpf_ksym ksym;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct bpf_tramp_image * cur_image</code>
</li>
<li>
<b>Field removed. </b>
<code>void * image</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bpf_ksym ksym</code>
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
<code>struct module * mod</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct ftrace_ops * fops</code>
</li>
<li>
<b>Field added. </b>
<code>u32 flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>u64 selector</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
