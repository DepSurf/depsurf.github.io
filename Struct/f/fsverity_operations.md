# Struct: <code>fsverity_operations</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fsverity_operations {
    int (*)(struct file *) begin_enable_verity;
    int (*)(struct file *, const void *, size_t, u64) end_enable_verity;
    int (*)(struct inode *, void *, size_t) get_verity_descriptor;
    struct page * (*)(struct inode *, long unsigned int) read_merkle_tree_page;
    int (*)(struct inode *, const void *, u64, int) write_merkle_tree_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fsverity_operations {
    int (*)(struct file *) begin_enable_verity;
    int (*)(struct file *, const void *, size_t, u64) end_enable_verity;
    int (*)(struct inode *, void *, size_t) get_verity_descriptor;
    struct page * (*)(struct inode *, long unsigned int, long unsigned int) read_merkle_tree_page;
    int (*)(struct inode *, const void *, u64, int) write_merkle_tree_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fsverity_operations {
    int (*)(struct file *) begin_enable_verity;
    int (*)(struct file *, const void *, size_t, u64) end_enable_verity;
    int (*)(struct inode *, void *, size_t) get_verity_descriptor;
    struct page * (*)(struct inode *, long unsigned int, long unsigned int) read_merkle_tree_page;
    int (*)(struct inode *, const void *, u64, int) write_merkle_tree_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fsverity_operations {
    int (*)(struct file *) begin_enable_verity;
    int (*)(struct file *, const void *, size_t, u64) end_enable_verity;
    int (*)(struct inode *, void *, size_t) get_verity_descriptor;
    struct page * (*)(struct inode *, long unsigned int, long unsigned int) read_merkle_tree_page;
    int (*)(struct inode *, const void *, u64, int) write_merkle_tree_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fsverity_operations {
    int (*)(struct file *) begin_enable_verity;
    int (*)(struct file *, const void *, size_t, u64) end_enable_verity;
    int (*)(struct inode *, void *, size_t) get_verity_descriptor;
    struct page * (*)(struct inode *, long unsigned int, long unsigned int) read_merkle_tree_page;
    int (*)(struct inode *, const void *, u64, int) write_merkle_tree_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fsverity_operations {
    int (*)(struct file *) begin_enable_verity;
    int (*)(struct file *, const void *, size_t, u64) end_enable_verity;
    int (*)(struct inode *, void *, size_t) get_verity_descriptor;
    struct page * (*)(struct inode *, long unsigned int, long unsigned int) read_merkle_tree_page;
    int (*)(struct inode *, const void *, u64, int) write_merkle_tree_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fsverity_operations {
    int (*)(struct file *) begin_enable_verity;
    int (*)(struct file *, const void *, size_t, u64) end_enable_verity;
    int (*)(struct inode *, void *, size_t) get_verity_descriptor;
    struct page * (*)(struct inode *, long unsigned int, long unsigned int) read_merkle_tree_page;
    int (*)(struct inode *, const void *, u64, int) write_merkle_tree_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fsverity_operations {
    int (*)(struct file *) begin_enable_verity;
    int (*)(struct file *, const void *, size_t, u64) end_enable_verity;
    int (*)(struct inode *, void *, size_t) get_verity_descriptor;
    struct page * (*)(struct inode *, long unsigned int, long unsigned int) read_merkle_tree_page;
    int (*)(struct inode *, const void *, u64, unsigned int) write_merkle_tree_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fsverity_operations {
    int (*)(struct file *) begin_enable_verity;
    int (*)(struct file *, const void *, size_t, u64) end_enable_verity;
    int (*)(struct inode *, void *, size_t) get_verity_descriptor;
    struct page * (*)(struct inode *, long unsigned int, long unsigned int) read_merkle_tree_page;
    int (*)(struct inode *, const void *, u64, unsigned int) write_merkle_tree_block;
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
struct fsverity_operations {
    int (*)(struct file *) begin_enable_verity;
    int (*)(struct file *, const void *, size_t, u64) end_enable_verity;
    int (*)(struct inode *, void *, size_t) get_verity_descriptor;
    struct page * (*)(struct inode *, long unsigned int) read_merkle_tree_page;
    int (*)(struct inode *, const void *, u64, int) write_merkle_tree_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fsverity_operations {
    int (*)(struct file *) begin_enable_verity;
    int (*)(struct file *, const void *, size_t, u64) end_enable_verity;
    int (*)(struct inode *, void *, size_t) get_verity_descriptor;
    struct page * (*)(struct inode *, long unsigned int) read_merkle_tree_page;
    int (*)(struct inode *, const void *, u64, int) write_merkle_tree_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fsverity_operations {
    int (*)(struct file *) begin_enable_verity;
    int (*)(struct file *, const void *, size_t, u64) end_enable_verity;
    int (*)(struct inode *, void *, size_t) get_verity_descriptor;
    struct page * (*)(struct inode *, long unsigned int) read_merkle_tree_page;
    int (*)(struct inode *, const void *, u64, int) write_merkle_tree_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fsverity_operations {
    int (*)(struct file *) begin_enable_verity;
    int (*)(struct file *, const void *, size_t, u64) end_enable_verity;
    int (*)(struct inode *, void *, size_t) get_verity_descriptor;
    struct page * (*)(struct inode *, long unsigned int) read_merkle_tree_page;
    int (*)(struct inode *, const void *, u64, int) write_merkle_tree_block;
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
struct fsverity_operations {
    int (*)(struct file *) begin_enable_verity;
    int (*)(struct file *, const void *, size_t, u64) end_enable_verity;
    int (*)(struct inode *, void *, size_t) get_verity_descriptor;
    struct page * (*)(struct inode *, long unsigned int) read_merkle_tree_page;
    int (*)(struct inode *, const void *, u64, int) write_merkle_tree_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fsverity_operations {
    int (*)(struct file *) begin_enable_verity;
    int (*)(struct file *, const void *, size_t, u64) end_enable_verity;
    int (*)(struct inode *, void *, size_t) get_verity_descriptor;
    struct page * (*)(struct inode *, long unsigned int) read_merkle_tree_page;
    int (*)(struct inode *, const void *, u64, int) write_merkle_tree_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fsverity_operations {
    int (*)(struct file *) begin_enable_verity;
    int (*)(struct file *, const void *, size_t, u64) end_enable_verity;
    int (*)(struct inode *, void *, size_t) get_verity_descriptor;
    struct page * (*)(struct inode *, long unsigned int) read_merkle_tree_page;
    int (*)(struct inode *, const void *, u64, int) write_merkle_tree_block;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fsverity_operations {
    int (*)(struct file *) begin_enable_verity;
    int (*)(struct file *, const void *, size_t, u64) end_enable_verity;
    int (*)(struct inode *, void *, size_t) get_verity_descriptor;
    struct page * (*)(struct inode *, long unsigned int) read_merkle_tree_page;
    int (*)(struct inode *, const void *, u64, int) write_merkle_tree_block;
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct fsverity_operations {
    int (*)(struct file *) begin_enable_verity;
    int (*)(struct file *, const void *, size_t, u64) end_enable_verity;
    int (*)(struct inode *, void *, size_t) get_verity_descriptor;
    struct page * (*)(struct inode *, long unsigned int) read_merkle_tree_page;
    int (*)(struct inode *, const void *, u64, int) write_merkle_tree_block;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct page * (*)(struct inode *, long unsigned int) read_merkle_tree_page</code> ➡️ <code>struct page * (*)(struct inode *, long unsigned int, long unsigned int) read_merkle_tree_page</code>
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct inode *, const void *, u64, int) write_merkle_tree_block</code> ➡️ <code>int (*)(struct inode *, const void *, u64, unsigned int) write_merkle_tree_block</code>
</li>
</ul>
</details>
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
