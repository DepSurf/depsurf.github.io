# Struct: <code>htab_elem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_node hash_node;
    struct callback_head rcu;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_node hash_node;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct callback_head rcu;
    enum extra_elem_state state;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_node hash_node;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct callback_head rcu;
    enum extra_elem_state state;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct htab_elem * batch_flink;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct htab_elem * batch_flink;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct htab_elem * batch_flink;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct htab_elem * batch_flink;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct htab_elem * batch_flink;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct pcpu_freelist_node fnode;
    struct htab_elem * batch_flink;
    void * ptr_to_pptr;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct pcpu_freelist_node fnode;
    struct htab_elem * batch_flink;
    void * ptr_to_pptr;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct pcpu_freelist_node fnode;
    struct htab_elem * batch_flink;
    void * ptr_to_pptr;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
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
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
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
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct htab_elem {
    struct hlist_nulls_node hash_node;
    void * padding;
    struct bpf_htab * htab;
    struct pcpu_freelist_node fnode;
    struct callback_head rcu;
    struct bpf_lru_node lru_node;
    u32 hash;
    char[0] key;
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
<b>Field added. </b>
<code>struct bpf_htab * htab</code>
</li>
<li>
<b>Field added. </b>
<code>struct pcpu_freelist_node fnode</code>
</li>
<li>
<b>Field added. </b>
<code>enum extra_elem_state state</code>
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
<code>struct bpf_lru_node lru_node</code>
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
<code>void * padding</code>
</li>
<li>
<b>Field removed. </b>
<code>enum extra_elem_state state</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct hlist_node hash_node</code> ➡️ <code>struct hlist_nulls_node hash_node</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct htab_elem * batch_flink</code>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * ptr_to_pptr</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bpf_htab * htab</code>
</li>
<li>
<b>Field removed. </b>
<code>struct callback_head rcu</code>
</li>
</ul>
</details>
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
