# Struct: <code>bpf_redirect_info</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_redirect_info {
    u32 ifindex;
    u32 flags;
    struct bpf_map * map;
    struct bpf_map * map_to_flush;
    u32 kern_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bpf_redirect_info {
    u32 flags;
    u32 tgt_index;
    void * tgt_value;
    struct bpf_map * map;
    struct bpf_map * map_to_flush;
    u32 kern_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_redirect_info {
    u32 flags;
    u32 tgt_index;
    void * tgt_value;
    struct bpf_map * map;
    struct bpf_map * map_to_flush;
    u32 kern_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_redirect_info {
    u32 flags;
    u32 tgt_index;
    void * tgt_value;
    struct bpf_map * map;
    u32 kern_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_redirect_info {
    u32 flags;
    u32 tgt_index;
    void * tgt_value;
    struct bpf_map * map;
    u32 kern_flags;
    struct bpf_nh_params nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct bpf_redirect_info {
    u32 flags;
    u32 tgt_index;
    void * tgt_value;
    u32 map_id;
    enum bpf_map_type map_type;
    u32 kern_flags;
    struct bpf_nh_params nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_redirect_info {
    u32 flags;
    u32 tgt_index;
    void * tgt_value;
    struct bpf_map * map;
    u32 map_id;
    enum bpf_map_type map_type;
    u32 kern_flags;
    struct bpf_nh_params nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct bpf_redirect_info {
    u32 flags;
    u32 tgt_index;
    void * tgt_value;
    struct bpf_map * map;
    u32 map_id;
    enum bpf_map_type map_type;
    u32 kern_flags;
    struct bpf_nh_params nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_redirect_info {
    u64 tgt_index;
    void * tgt_value;
    struct bpf_map * map;
    u32 flags;
    u32 kern_flags;
    u32 map_id;
    enum bpf_map_type map_type;
    struct bpf_nh_params nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct bpf_redirect_info {
    u64 tgt_index;
    void * tgt_value;
    struct bpf_map * map;
    u32 flags;
    u32 kern_flags;
    u32 map_id;
    enum bpf_map_type map_type;
    struct bpf_nh_params nh;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct bpf_redirect_info {
    u64 tgt_index;
    void * tgt_value;
    struct bpf_map * map;
    u32 flags;
    u32 kern_flags;
    u32 map_id;
    enum bpf_map_type map_type;
    struct bpf_nh_params nh;
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
struct bpf_redirect_info {
    u32 flags;
    u32 tgt_index;
    void * tgt_value;
    struct bpf_map * map;
    struct bpf_map * map_to_flush;
    u32 kern_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bpf_redirect_info {
    u32 flags;
    u32 tgt_index;
    void * tgt_value;
    struct bpf_map * map;
    struct bpf_map * map_to_flush;
    u32 kern_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bpf_redirect_info {
    u32 flags;
    u32 tgt_index;
    void * tgt_value;
    struct bpf_map * map;
    struct bpf_map * map_to_flush;
    u32 kern_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bpf_redirect_info {
    u32 flags;
    u32 tgt_index;
    void * tgt_value;
    struct bpf_map * map;
    struct bpf_map * map_to_flush;
    u32 kern_flags;
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
struct bpf_redirect_info {
    u32 flags;
    u32 tgt_index;
    void * tgt_value;
    struct bpf_map * map;
    struct bpf_map * map_to_flush;
    u32 kern_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bpf_redirect_info {
    u32 flags;
    u32 tgt_index;
    void * tgt_value;
    struct bpf_map * map;
    struct bpf_map * map_to_flush;
    u32 kern_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bpf_redirect_info {
    u32 flags;
    u32 tgt_index;
    void * tgt_value;
    struct bpf_map * map;
    struct bpf_map * map_to_flush;
    u32 kern_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bpf_redirect_info {
    u32 flags;
    u32 tgt_index;
    void * tgt_value;
    struct bpf_map * map;
    struct bpf_map * map_to_flush;
    u32 kern_flags;
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct bpf_redirect_info {
    u32 ifindex;
    u32 flags;
    struct bpf_map * map;
    struct bpf_map * map_to_flush;
    u32 kern_flags;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u32 tgt_index</code>
</li>
<li>
<b>Field added. </b>
<code>void * tgt_value</code>
</li>
<li>
<b>Field removed. </b>
<code>u32 ifindex</code>
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
<b>Field removed. </b>
<code>struct bpf_map * map_to_flush</code>
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
<code>struct bpf_nh_params nh</code>
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
<code>u32 map_id</code>
</li>
<li>
<b>Field added. </b>
<code>enum bpf_map_type map_type</code>
</li>
<li>
<b>Field removed. </b>
<code>struct bpf_map * map</code>
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
<code>struct bpf_map * map</code>
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
<code>u32 tgt_index</code> ➡️ <code>u64 tgt_index</code>
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
