# Struct: <code>iomap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct iomap {
    sector_t blkno;
    loff_t offset;
    u64 length;
    int type;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct iomap {
    sector_t blkno;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct iomap {
    sector_t blkno;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct iomap {
    sector_t blkno;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    void (*)(struct inode *, loff_t, unsigned int, struct page *, struct iomap *) page_done;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    const struct iomap_page_ops * page_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    const struct iomap_page_ops * page_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    const struct iomap_page_ops * page_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    const struct iomap_page_ops * page_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    const struct iomap_page_ops * page_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    const struct iomap_page_ops * page_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    const struct iomap_page_ops * page_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    const struct iomap_page_ops * page_ops;
    u64 validity_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    const struct iomap_folio_ops * folio_ops;
    u64 validity_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    const struct iomap_folio_ops * folio_ops;
    u64 validity_cookie;
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
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    const struct iomap_page_ops * page_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    const struct iomap_page_ops * page_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    const struct iomap_page_ops * page_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    const struct iomap_page_ops * page_ops;
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
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    const struct iomap_page_ops * page_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    const struct iomap_page_ops * page_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    const struct iomap_page_ops * page_ops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct iomap {
    u64 addr;
    loff_t offset;
    u64 length;
    u16 type;
    u16 flags;
    struct block_device * bdev;
    struct dax_device * dax_dev;
    void * inline_data;
    void * private;
    const struct iomap_page_ops * page_ops;
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
<code>u16 flags</code>
</li>
<li>
<b>Field added. </b>
<code>struct block_device * bdev</code>
</li>
<li>
<b>Field type changed. </b>
<code>int type</code> ➡️ <code>u16 type</code>
</li>
</ul>
</details>
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
<code>struct dax_device * dax_dev</code>
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
<code>u64 addr</code>
</li>
<li>
<b>Field removed. </b>
<code>sector_t blkno</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>void * inline_data</code>
</li>
<li>
<b>Field added. </b>
<code>void * private</code>
</li>
<li>
<b>Field added. </b>
<code>void (*)(struct inode *, loff_t, unsigned int, struct page *, struct iomap *) page_done</code>
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
<code>const struct iomap_page_ops * page_ops</code>
</li>
<li>
<b>Field removed. </b>
<code>void (*)(struct inode *, loff_t, unsigned int, struct page *, struct iomap *) page_done</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 validity_cookie</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct iomap_folio_ops * folio_ops</code>
</li>
<li>
<b>Field removed. </b>
<code>const struct iomap_page_ops * page_ops</code>
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
