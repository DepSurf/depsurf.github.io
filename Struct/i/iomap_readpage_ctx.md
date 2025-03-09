# Struct: <code>iomap_readpage_ctx</code>

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
struct iomap_readpage_ctx {
    struct page * cur_page;
    bool cur_page_in_bio;
    bool is_readahead;
    struct bio * bio;
    struct list_head * pages;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct iomap_readpage_ctx {
    struct page * cur_page;
    bool cur_page_in_bio;
    bool is_readahead;
    struct bio * bio;
    struct list_head * pages;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct iomap_readpage_ctx {
    struct page * cur_page;
    bool cur_page_in_bio;
    bool is_readahead;
    struct bio * bio;
    struct list_head * pages;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct iomap_readpage_ctx {
    struct page * cur_page;
    bool cur_page_in_bio;
    struct bio * bio;
    struct readahead_control * rac;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct iomap_readpage_ctx {
    struct page * cur_page;
    bool cur_page_in_bio;
    struct bio * bio;
    struct readahead_control * rac;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct iomap_readpage_ctx {
    struct page * cur_page;
    bool cur_page_in_bio;
    struct bio * bio;
    struct readahead_control * rac;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct iomap_readpage_ctx {
    struct page * cur_page;
    bool cur_page_in_bio;
    struct bio * bio;
    struct readahead_control * rac;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct iomap_readpage_ctx {
    struct folio * cur_folio;
    bool cur_folio_in_bio;
    struct bio * bio;
    struct readahead_control * rac;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct iomap_readpage_ctx {
    struct folio * cur_folio;
    bool cur_folio_in_bio;
    struct bio * bio;
    struct readahead_control * rac;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct iomap_readpage_ctx {
    struct folio * cur_folio;
    bool cur_folio_in_bio;
    struct bio * bio;
    struct readahead_control * rac;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct iomap_readpage_ctx {
    struct folio * cur_folio;
    bool cur_folio_in_bio;
    struct bio * bio;
    struct readahead_control * rac;
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
struct iomap_readpage_ctx {
    struct page * cur_page;
    bool cur_page_in_bio;
    bool is_readahead;
    struct bio * bio;
    struct list_head * pages;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct iomap_readpage_ctx {
    struct page * cur_page;
    bool cur_page_in_bio;
    bool is_readahead;
    struct bio * bio;
    struct list_head * pages;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct iomap_readpage_ctx {
    struct page * cur_page;
    bool cur_page_in_bio;
    bool is_readahead;
    struct bio * bio;
    struct list_head * pages;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct iomap_readpage_ctx {
    struct page * cur_page;
    bool cur_page_in_bio;
    bool is_readahead;
    struct bio * bio;
    struct list_head * pages;
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
struct iomap_readpage_ctx {
    struct page * cur_page;
    bool cur_page_in_bio;
    bool is_readahead;
    struct bio * bio;
    struct list_head * pages;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct iomap_readpage_ctx {
    struct page * cur_page;
    bool cur_page_in_bio;
    bool is_readahead;
    struct bio * bio;
    struct list_head * pages;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct iomap_readpage_ctx {
    struct page * cur_page;
    bool cur_page_in_bio;
    bool is_readahead;
    struct bio * bio;
    struct list_head * pages;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct iomap_readpage_ctx {
    struct page * cur_page;
    bool cur_page_in_bio;
    bool is_readahead;
    struct bio * bio;
    struct list_head * pages;
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
struct iomap_readpage_ctx {
    struct page * cur_page;
    bool cur_page_in_bio;
    bool is_readahead;
    struct bio * bio;
    struct list_head * pages;
}
```
</details>
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
<code>struct readahead_control * rac</code>
</li>
<li>
<b>Field removed. </b>
<code>bool is_readahead</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head * pages</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct folio * cur_folio</code>
</li>
<li>
<b>Field added. </b>
<code>bool cur_folio_in_bio</code>
</li>
<li>
<b>Field removed. </b>
<code>struct page * cur_page</code>
</li>
<li>
<b>Field removed. </b>
<code>bool cur_page_in_bio</code>
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
