# Struct: <code>dm_target_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    unsigned int magic;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    bool inside_dm_io;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    unsigned int magic;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    bool inside_dm_io;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    unsigned int magic;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    bool inside_dm_io;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    unsigned int magic;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    bool inside_dm_io;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    unsigned int magic;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    bool inside_dm_io;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    unsigned int magic;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    bool inside_dm_io;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    unsigned int magic;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    bool inside_dm_io;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    unsigned int magic;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    bool inside_dm_io;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    short unsigned int magic;
    blk_short_t flags;
    unsigned int target_bio_nr;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int * len_ptr;
    sector_t old_sector;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    short unsigned int magic;
    blk_short_t flags;
    unsigned int target_bio_nr;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int * len_ptr;
    sector_t old_sector;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    short unsigned int magic;
    blk_short_t flags;
    unsigned int target_bio_nr;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int * len_ptr;
    sector_t old_sector;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    short unsigned int magic;
    blk_short_t flags;
    unsigned int target_bio_nr;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int * len_ptr;
    sector_t old_sector;
    struct bio clone;
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
struct dm_target_io {
    unsigned int magic;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    bool inside_dm_io;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dm_target_io {
    unsigned int magic;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    bool inside_dm_io;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dm_target_io {
    unsigned int magic;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    bool inside_dm_io;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dm_target_io {
    unsigned int magic;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    bool inside_dm_io;
    struct bio clone;
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
struct dm_target_io {
    unsigned int magic;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    bool inside_dm_io;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    unsigned int magic;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    bool inside_dm_io;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    unsigned int magic;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    bool inside_dm_io;
    struct bio clone;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dm_target_io {
    unsigned int magic;
    struct dm_io * io;
    struct dm_target * ti;
    unsigned int target_bio_nr;
    unsigned int * len_ptr;
    bool inside_dm_io;
    struct bio clone;
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int magic</code>
</li>
<li>
<b>Field added. </b>
<code>bool inside_dm_io</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>blk_short_t flags</code>
</li>
<li>
<b>Field added. </b>
<code>sector_t old_sector</code>
</li>
<li>
<b>Field removed. </b>
<code>bool inside_dm_io</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int magic</code> ➡️ <code>short unsigned int magic</code>
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
