# Struct: <code>io_rsrc_node</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct io_rsrc_node {
    struct percpu_ref refs;
    struct list_head node;
    struct list_head rsrc_list;
    struct io_rsrc_data * rsrc_data;
    struct llist_node llist;
    bool done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct io_rsrc_node {
    struct percpu_ref refs;
    struct list_head node;
    struct list_head rsrc_list;
    struct io_rsrc_data * rsrc_data;
    struct llist_node llist;
    bool done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct io_rsrc_node {
    struct percpu_ref refs;
    struct list_head node;
    struct list_head rsrc_list;
    struct io_rsrc_data * rsrc_data;
    struct llist_node llist;
    bool done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct io_rsrc_node {
    struct percpu_ref refs;
    struct list_head node;
    struct list_head rsrc_list;
    struct io_rsrc_data * rsrc_data;
    struct llist_node llist;
    bool done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct io_rsrc_node {
    struct io_cache_entry cache;
    struct io_ring_ctx * ctx;
    int refs;
    bool empty;
    u16 type;
    struct list_head node;
    struct io_rsrc_put item;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct io_rsrc_node {
    struct io_cache_entry cache;
    struct io_ring_ctx * ctx;
    int refs;
    bool empty;
    u16 type;
    struct list_head node;
    struct io_rsrc_put item;
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct io_rsrc_node {
    struct percpu_ref refs;
    struct list_head node;
    struct list_head rsrc_list;
    struct io_rsrc_data * rsrc_data;
    struct llist_node llist;
    bool done;
}
```
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct io_cache_entry cache</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_ring_ctx * ctx</code>
</li>
<li>
<b>Field added. </b>
<code>bool empty</code>
</li>
<li>
<b>Field added. </b>
<code>u16 type</code>
</li>
<li>
<b>Field added. </b>
<code>struct io_rsrc_put item</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head rsrc_list</code>
</li>
<li>
<b>Field removed. </b>
<code>struct io_rsrc_data * rsrc_data</code>
</li>
<li>
<b>Field removed. </b>
<code>struct llist_node llist</code>
</li>
<li>
<b>Field removed. </b>
<code>bool done</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct percpu_ref refs</code> ➡️ <code>int refs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
