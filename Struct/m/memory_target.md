# Struct: <code>memory_target</code>

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
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct node_hmem_attrs hmem_attrs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct node_hmem_attrs hmem_attrs;
    struct list_head caches;
    struct node_cache_attrs cache_attrs;
    bool registered;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct resource memregions;
    struct node_hmem_attrs hmem_attrs;
    struct list_head caches;
    struct node_cache_attrs cache_attrs;
    bool registered;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct resource memregions;
    struct node_hmem_attrs[2] hmem_attrs;
    struct list_head caches;
    struct node_cache_attrs cache_attrs;
    bool registered;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct resource memregions;
    struct node_hmem_attrs[2] hmem_attrs;
    struct list_head caches;
    struct node_cache_attrs cache_attrs;
    bool registered;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct resource memregions;
    struct node_hmem_attrs[2] hmem_attrs;
    struct list_head caches;
    struct node_cache_attrs cache_attrs;
    bool registered;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct resource memregions;
    struct node_hmem_attrs[2] hmem_attrs;
    struct list_head caches;
    struct node_cache_attrs cache_attrs;
    bool registered;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct resource memregions;
    struct node_hmem_attrs[2] hmem_attrs;
    struct list_head caches;
    struct node_cache_attrs cache_attrs;
    bool registered;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct resource memregions;
    struct node_hmem_attrs[2] hmem_attrs;
    struct list_head caches;
    struct node_cache_attrs cache_attrs;
    bool registered;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct resource memregions;
    struct access_coordinate[3] coord;
    struct list_head caches;
    struct node_cache_attrs cache_attrs;
    u8[16] gen_port_device_handle;
    bool registered;
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
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct node_hmem_attrs hmem_attrs;
    struct list_head caches;
    struct node_cache_attrs cache_attrs;
    bool registered;
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct node_hmem_attrs hmem_attrs;
    struct list_head caches;
    struct node_cache_attrs cache_attrs;
    bool registered;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct node_hmem_attrs hmem_attrs;
    struct list_head caches;
    struct node_cache_attrs cache_attrs;
    bool registered;
}
```
</details>
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct node_hmem_attrs hmem_attrs;
    struct list_head caches;
    struct node_cache_attrs cache_attrs;
    bool registered;
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
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct node_hmem_attrs hmem_attrs;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head caches</code>
</li>
<li>
<b>Field added. </b>
<code>struct node_cache_attrs cache_attrs</code>
</li>
<li>
<b>Field added. </b>
<code>bool registered</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct resource memregions</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct node_hmem_attrs hmem_attrs</code> ➡️ <code>struct node_hmem_attrs[2] hmem_attrs</code>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct access_coordinate[3] coord</code>
</li>
<li>
<b>Field added. </b>
<code>u8[16] gen_port_device_handle</code>
</li>
<li>
<b>Field removed. </b>
<code>struct node_hmem_attrs[2] hmem_attrs</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct node_hmem_attrs hmem_attrs;
    struct list_head caches;
    struct node_cache_attrs cache_attrs;
    bool registered;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct node_hmem_attrs hmem_attrs;
    struct list_head caches;
    struct node_cache_attrs cache_attrs;
    bool registered;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct node_hmem_attrs hmem_attrs;
    struct list_head caches;
    struct node_cache_attrs cache_attrs;
    bool registered;
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
struct memory_target {
    struct list_head node;
    unsigned int memory_pxm;
    unsigned int processor_pxm;
    struct node_hmem_attrs hmem_attrs;
    struct list_head caches;
    struct node_cache_attrs cache_attrs;
    bool registered;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
