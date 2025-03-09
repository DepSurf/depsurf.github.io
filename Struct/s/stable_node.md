# Struct: <code>stable_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    int nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    int nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    int nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
    int nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
    int nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
    int nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
    int nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
    int nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
    int nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
    int nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
    int nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
    int nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
    int nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
    int nid;
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
    int nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
    int nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
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
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
    int nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
    int nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
    int nid;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
    int nid;
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
<code>struct hlist_node hlist_dup</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int chain_prune_time</code>
</li>
<li>
<b>Field added. </b>
<code>int rmap_hlist_len</code>
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct stable_node {
    struct rb_node node;
    struct list_head * head;
    struct hlist_node hlist_dup;
    struct list_head list;
    struct hlist_head hlist;
    long unsigned int kpfn;
    long unsigned int chain_prune_time;
    int rmap_hlist_len;
    int nid;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int nid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int nid</code>
</li>
</ul>
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
