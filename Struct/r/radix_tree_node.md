# Struct: <code>radix_tree_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct radix_tree_node {
    unsigned int path;
    unsigned int count;
    struct radix_tree_node * parent;
    void * private_data;
    struct callback_head callback_head;
    struct list_head private_list;
    void *[64] slots;
    long unsigned int[3] tags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct radix_tree_node {
    unsigned char shift;
    unsigned char offset;
    unsigned int count;
    struct radix_tree_node * parent;
    void * private_data;
    struct callback_head callback_head;
    struct list_head private_list;
    void *[64] slots;
    long unsigned int[3] tags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct radix_tree_node {
    unsigned char shift;
    unsigned char offset;
    unsigned char count;
    unsigned char exceptional;
    struct radix_tree_node * parent;
    void * private_data;
    struct list_head private_list;
    struct callback_head callback_head;
    void *[64] slots;
    long unsigned int[3] tags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct radix_tree_node {
    unsigned char shift;
    unsigned char offset;
    unsigned char count;
    unsigned char exceptional;
    struct radix_tree_node * parent;
    struct radix_tree_root * root;
    struct list_head private_list;
    struct callback_head callback_head;
    void *[64] slots;
    long unsigned int[3] tags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct radix_tree_node {
    unsigned char shift;
    unsigned char offset;
    unsigned char count;
    unsigned char exceptional;
    struct radix_tree_node * parent;
    struct radix_tree_root * root;
    struct list_head private_list;
    struct callback_head callback_head;
    void *[64] slots;
    long unsigned int[3] tags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct radix_tree_node {
    unsigned char shift;
    unsigned char offset;
    unsigned char count;
    unsigned char exceptional;
    struct radix_tree_node * parent;
    struct radix_tree_root * root;
    struct list_head private_list;
    struct callback_head callback_head;
    void *[64] slots;
    long unsigned int[3] tags;
}
```
</details>
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned char shift</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned char offset</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int path</code>
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
<code>unsigned char exceptional</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int count</code> ➡️ <code>unsigned char count</code>
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
<code>struct radix_tree_root * root</code>
</li>
<li>
<b>Field removed. </b>
<code>void * private_data</code>
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
struct radix_tree_node {
    unsigned char shift;
    unsigned char offset;
    unsigned char count;
    unsigned char exceptional;
    struct radix_tree_node * parent;
    struct radix_tree_root * root;
    struct list_head private_list;
    struct callback_head callback_head;
    void *[64] slots;
    long unsigned int[3] tags;
}
```
</details>
</li>
</ul>
