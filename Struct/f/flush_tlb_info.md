# Struct: <code>flush_tlb_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * flush_mm;
    long unsigned int flush_start;
    long unsigned int flush_end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * flush_mm;
    long unsigned int flush_start;
    long unsigned int flush_end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * flush_mm;
    long unsigned int flush_start;
    long unsigned int flush_end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int stride_shift;
    bool freed_tables;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int stride_shift;
    bool freed_tables;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int stride_shift;
    bool freed_tables;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int stride_shift;
    bool freed_tables;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int stride_shift;
    bool freed_tables;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int initiating_cpu;
    u8 stride_shift;
    u8 freed_tables;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int initiating_cpu;
    u8 stride_shift;
    u8 freed_tables;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int initiating_cpu;
    u8 stride_shift;
    u8 freed_tables;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int initiating_cpu;
    u8 stride_shift;
    u8 freed_tables;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int initiating_cpu;
    u8 stride_shift;
    u8 freed_tables;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int initiating_cpu;
    u8 stride_shift;
    u8 freed_tables;
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int stride_shift;
    bool freed_tables;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int stride_shift;
    bool freed_tables;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int stride_shift;
    bool freed_tables;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int stride_shift;
    bool freed_tables;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mm_struct * mm</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int start</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int end</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mm_struct * flush_mm</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int flush_start</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int flush_end</code>
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
<code>u64 new_tlb_gen</code>
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
<code>unsigned int stride_shift</code>
</li>
<li>
<b>Field added. </b>
<code>bool freed_tables</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int initiating_cpu</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int stride_shift</code> ➡️ <code>u8 stride_shift</code>
</li>
<li>
<b>Field type changed. </b>
<code>bool freed_tables</code> ➡️ <code>u8 freed_tables</code>
</li>
</ul>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int stride_shift;
    bool freed_tables;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int stride_shift;
    bool freed_tables;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int stride_shift;
    bool freed_tables;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct flush_tlb_info {
    struct mm_struct * mm;
    long unsigned int start;
    long unsigned int end;
    u64 new_tlb_gen;
    unsigned int stride_shift;
    bool freed_tables;
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
