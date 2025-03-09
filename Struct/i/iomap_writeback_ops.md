# Struct: <code>iomap_writeback_ops</code>

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
struct iomap_writeback_ops {
    int (*)(struct iomap_writepage_ctx *, struct inode *, loff_t) map_blocks;
    int (*)(struct iomap_ioend *, int) prepare_ioend;
    void (*)(struct page *) discard_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct iomap_writeback_ops {
    int (*)(struct iomap_writepage_ctx *, struct inode *, loff_t) map_blocks;
    int (*)(struct iomap_ioend *, int) prepare_ioend;
    void (*)(struct page *, loff_t) discard_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct iomap_writeback_ops {
    int (*)(struct iomap_writepage_ctx *, struct inode *, loff_t) map_blocks;
    int (*)(struct iomap_ioend *, int) prepare_ioend;
    void (*)(struct page *, loff_t) discard_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct iomap_writeback_ops {
    int (*)(struct iomap_writepage_ctx *, struct inode *, loff_t) map_blocks;
    int (*)(struct iomap_ioend *, int) prepare_ioend;
    void (*)(struct page *, loff_t) discard_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct iomap_writeback_ops {
    int (*)(struct iomap_writepage_ctx *, struct inode *, loff_t) map_blocks;
    int (*)(struct iomap_ioend *, int) prepare_ioend;
    void (*)(struct folio *, loff_t) discard_folio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct iomap_writeback_ops {
    int (*)(struct iomap_writepage_ctx *, struct inode *, loff_t) map_blocks;
    int (*)(struct iomap_ioend *, int) prepare_ioend;
    void (*)(struct folio *, loff_t) discard_folio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct iomap_writeback_ops {
    int (*)(struct iomap_writepage_ctx *, struct inode *, loff_t) map_blocks;
    int (*)(struct iomap_ioend *, int) prepare_ioend;
    void (*)(struct folio *, loff_t) discard_folio;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct iomap_writeback_ops {
    int (*)(struct iomap_writepage_ctx *, struct inode *, loff_t) map_blocks;
    int (*)(struct iomap_ioend *, int) prepare_ioend;
    void (*)(struct folio *, loff_t) discard_folio;
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
struct iomap_writeback_ops {
    int (*)(struct iomap_writepage_ctx *, struct inode *, loff_t) map_blocks;
    int (*)(struct iomap_ioend *, int) prepare_ioend;
    void (*)(struct page *) discard_page;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(struct page *) discard_page</code> ➡️ <code>void (*)(struct page *, loff_t) discard_page</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void (*)(struct folio *, loff_t) discard_folio</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct page *, loff_t) discard_page</code>
</li>
</ul>
</details>
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
