# Struct: <code>cgroup_bpf</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog *[3] prog;
    struct bpf_prog *[3] effective;
    bool[3] disallow_override;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog *[4] prog;
    struct bpf_prog *[4] effective;
    bool[4] disallow_override;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[7] effective;
    struct list_head[7] progs;
    u32[7] flags;
    struct bpf_prog_array * inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[17] effective;
    struct list_head[17] progs;
    u32[17] flags;
    struct bpf_prog_array * inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[18] effective;
    struct list_head[18] progs;
    u32[18] flags;
    struct bpf_prog_array * inactive;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[23] effective;
    struct list_head[23] progs;
    u32[23] flags;
    struct bpf_prog_array * inactive;
    struct percpu_ref refcnt;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[23] effective;
    struct list_head[23] progs;
    u32[23] flags;
    struct bpf_prog_array * inactive;
    struct percpu_ref refcnt;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[34] effective;
    struct list_head[34] progs;
    u32[34] flags;
    struct bpf_prog_array * inactive;
    struct percpu_ref refcnt;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[38] effective;
    struct list_head[38] progs;
    u32[38] flags;
    struct list_head storages;
    struct bpf_prog_array * inactive;
    struct percpu_ref refcnt;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[39] effective;
    struct list_head[39] progs;
    u32[39] flags;
    struct list_head storages;
    struct bpf_prog_array * inactive;
    struct percpu_ref refcnt;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[23] effective;
    struct list_head[23] progs;
    u32[23] flags;
    struct list_head storages;
    struct bpf_prog_array * inactive;
    struct percpu_ref refcnt;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[23] effective;
    struct list_head[23] progs;
    u32[23] flags;
    struct list_head storages;
    struct bpf_prog_array * inactive;
    struct percpu_ref refcnt;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[33] effective;
    struct hlist_head[33] progs;
    u8[33] flags;
    struct list_head storages;
    struct bpf_prog_array * inactive;
    struct percpu_ref refcnt;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[33] effective;
    struct hlist_head[33] progs;
    u8[33] flags;
    struct list_head storages;
    struct bpf_prog_array * inactive;
    struct percpu_ref refcnt;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[38] effective;
    struct hlist_head[38] progs;
    u8[38] flags;
    struct list_head storages;
    struct bpf_prog_array * inactive;
    struct percpu_ref refcnt;
    struct work_struct release_work;
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
struct cgroup_bpf {
    struct bpf_prog_array *[23] effective;
    struct list_head[23] progs;
    u32[23] flags;
    struct bpf_prog_array * inactive;
    struct percpu_ref refcnt;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[23] effective;
    struct list_head[23] progs;
    u32[23] flags;
    struct bpf_prog_array * inactive;
    struct percpu_ref refcnt;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[23] effective;
    struct list_head[23] progs;
    u32[23] flags;
    struct bpf_prog_array * inactive;
    struct percpu_ref refcnt;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[23] effective;
    struct list_head[23] progs;
    u32[23] flags;
    struct bpf_prog_array * inactive;
    struct percpu_ref refcnt;
    struct work_struct release_work;
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
struct cgroup_bpf {
    struct bpf_prog_array *[23] effective;
    struct list_head[23] progs;
    u32[23] flags;
    struct bpf_prog_array * inactive;
    struct percpu_ref refcnt;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[23] effective;
    struct list_head[23] progs;
    u32[23] flags;
    struct bpf_prog_array * inactive;
    struct percpu_ref refcnt;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[23] effective;
    struct list_head[23] progs;
    u32[23] flags;
    struct bpf_prog_array * inactive;
    struct percpu_ref refcnt;
    struct work_struct release_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cgroup_bpf {
    struct bpf_prog_array *[23] effective;
    struct list_head[23] progs;
    u32[23] flags;
    struct bpf_prog_array * inactive;
    struct percpu_ref refcnt;
    struct work_struct release_work;
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct cgroup_bpf {
    struct bpf_prog *[3] prog;
    struct bpf_prog *[3] effective;
    bool[3] disallow_override;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct bpf_prog *[3] prog</code> ➡️ <code>struct bpf_prog *[4] prog</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct bpf_prog *[3] effective</code> ➡️ <code>struct bpf_prog *[4] effective</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool[3] disallow_override</code> ➡️ <code>bool[4] disallow_override</code>
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
<code>struct list_head[7] progs</code>
</li>
<li>
<b>Field added. </b>
<code>u32[7] flags</code>
</li>
<li>
<b>Field added. </b>
<code>struct bpf_prog_array * inactive</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bpf_prog *[4] prog</code>
</li>
<li>
<b>Field removed. </b>
<code>bool[4] disallow_override</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct bpf_prog *[4] effective</code> ➡️ <code>struct bpf_prog_array *[7] effective</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct bpf_prog_array *[7] effective</code> ➡️ <code>struct bpf_prog_array *[17] effective</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head[7] progs</code> ➡️ <code>struct list_head[17] progs</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32[7] flags</code> ➡️ <code>u32[17] flags</code>
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
<code>struct bpf_prog_array *[17] effective</code> ➡️ <code>struct bpf_prog_array *[18] effective</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head[17] progs</code> ➡️ <code>struct list_head[18] progs</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32[17] flags</code> ➡️ <code>u32[18] flags</code>
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
<code>struct percpu_ref refcnt</code>
</li>
<li>
<b>Field added. </b>
<code>struct work_struct release_work</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct bpf_prog_array *[18] effective</code> ➡️ <code>struct bpf_prog_array *[23] effective</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head[18] progs</code> ➡️ <code>struct list_head[23] progs</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32[18] flags</code> ➡️ <code>u32[23] flags</code>
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
<b>Field type changed. </b>
<code>struct bpf_prog_array *[23] effective</code> ➡️ <code>struct bpf_prog_array *[34] effective</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head[23] progs</code> ➡️ <code>struct list_head[34] progs</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32[23] flags</code> ➡️ <code>u32[34] flags</code>
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
<code>struct list_head storages</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct bpf_prog_array *[34] effective</code> ➡️ <code>struct bpf_prog_array *[38] effective</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head[34] progs</code> ➡️ <code>struct list_head[38] progs</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32[34] flags</code> ➡️ <code>u32[38] flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct bpf_prog_array *[38] effective</code> ➡️ <code>struct bpf_prog_array *[39] effective</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head[38] progs</code> ➡️ <code>struct list_head[39] progs</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32[38] flags</code> ➡️ <code>u32[39] flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct bpf_prog_array *[39] effective</code> ➡️ <code>struct bpf_prog_array *[23] effective</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head[39] progs</code> ➡️ <code>struct list_head[23] progs</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32[39] flags</code> ➡️ <code>u32[23] flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct bpf_prog_array *[23] effective</code> ➡️ <code>struct bpf_prog_array *[33] effective</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct list_head[23] progs</code> ➡️ <code>struct hlist_head[33] progs</code>
</li>
<li>
<b>Field type changed. </b>
<code>u32[23] flags</code> ➡️ <code>u8[33] flags</code>
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
<b>Field type changed. </b>
<code>struct bpf_prog_array *[33] effective</code> ➡️ <code>struct bpf_prog_array *[38] effective</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct hlist_head[33] progs</code> ➡️ <code>struct hlist_head[38] progs</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8[33] flags</code> ➡️ <code>u8[38] flags</code>
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
