# Struct: <code>mem_size_stats</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int anonymous_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 swap_pss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 swap_pss;
    bool check_shmem_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 swap_pss;
    bool check_shmem_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 swap_pss;
    bool check_shmem_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    bool first;
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    long unsigned int first_vma_start;
    u64 pss;
    u64 pss_locked;
    u64 swap_pss;
    bool check_shmem_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    bool first;
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    long unsigned int first_vma_start;
    u64 pss;
    u64 pss_locked;
    u64 swap_pss;
    bool check_shmem_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 pss_locked;
    u64 swap_pss;
    bool check_shmem_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 pss_anon;
    u64 pss_file;
    u64 pss_shmem;
    u64 pss_locked;
    u64 swap_pss;
    bool check_shmem_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int file_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 pss_anon;
    u64 pss_file;
    u64 pss_shmem;
    u64 pss_locked;
    u64 swap_pss;
    bool check_shmem_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int file_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 pss_anon;
    u64 pss_file;
    u64 pss_shmem;
    u64 pss_locked;
    u64 swap_pss;
    bool check_shmem_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int file_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 pss_anon;
    u64 pss_file;
    u64 pss_shmem;
    u64 pss_locked;
    u64 swap_pss;
    bool check_shmem_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int file_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 pss_anon;
    u64 pss_file;
    u64 pss_shmem;
    u64 pss_locked;
    u64 swap_pss;
    bool check_shmem_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int file_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 pss_anon;
    u64 pss_file;
    u64 pss_shmem;
    u64 pss_locked;
    u64 swap_pss;
    bool check_shmem_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int file_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 pss_anon;
    u64 pss_file;
    u64 pss_shmem;
    u64 pss_locked;
    u64 swap_pss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int file_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 pss_anon;
    u64 pss_file;
    u64 pss_shmem;
    u64 pss_dirty;
    u64 pss_locked;
    u64 swap_pss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int file_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 pss_anon;
    u64 pss_file;
    u64 pss_shmem;
    u64 pss_dirty;
    u64 pss_locked;
    u64 swap_pss;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int file_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    long unsigned int ksm;
    u64 pss;
    u64 pss_anon;
    u64 pss_file;
    u64 pss_shmem;
    u64 pss_dirty;
    u64 pss_locked;
    u64 swap_pss;
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
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int file_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 pss_anon;
    u64 pss_file;
    u64 pss_shmem;
    u64 pss_locked;
    u64 swap_pss;
    bool check_shmem_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int file_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 pss_anon;
    u64 pss_file;
    u64 pss_shmem;
    u64 pss_locked;
    u64 swap_pss;
    bool check_shmem_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int file_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 pss_anon;
    u64 pss_file;
    u64 pss_shmem;
    u64 pss_locked;
    u64 swap_pss;
    bool check_shmem_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int file_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 pss_anon;
    u64 pss_file;
    u64 pss_shmem;
    u64 pss_locked;
    u64 swap_pss;
    bool check_shmem_swap;
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
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int file_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 pss_anon;
    u64 pss_file;
    u64 pss_shmem;
    u64 pss_locked;
    u64 swap_pss;
    bool check_shmem_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int file_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 pss_anon;
    u64 pss_file;
    u64 pss_shmem;
    u64 pss_locked;
    u64 swap_pss;
    bool check_shmem_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int file_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 pss_anon;
    u64 pss_file;
    u64 pss_shmem;
    u64 pss_locked;
    u64 swap_pss;
    bool check_shmem_swap;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mem_size_stats {
    long unsigned int resident;
    long unsigned int shared_clean;
    long unsigned int shared_dirty;
    long unsigned int private_clean;
    long unsigned int private_dirty;
    long unsigned int referenced;
    long unsigned int anonymous;
    long unsigned int lazyfree;
    long unsigned int anonymous_thp;
    long unsigned int shmem_thp;
    long unsigned int file_thp;
    long unsigned int swap;
    long unsigned int shared_hugetlb;
    long unsigned int private_hugetlb;
    u64 pss;
    u64 pss_anon;
    u64 pss_file;
    u64 pss_shmem;
    u64 pss_locked;
    u64 swap_pss;
    bool check_shmem_swap;
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
<code>long unsigned int shmem_thp</code>
</li>
<li>
<b>Field added. </b>
<code>bool check_shmem_swap</code>
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
<code>long unsigned int lazyfree</code>
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
<code>bool first</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int first_vma_start</code>
</li>
<li>
<b>Field added. </b>
<code>u64 pss_locked</code>
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
<b>Field removed. </b>
<code>bool first</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int first_vma_start</code>
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
<code>u64 pss_anon</code>
</li>
<li>
<b>Field added. </b>
<code>u64 pss_file</code>
</li>
<li>
<b>Field added. </b>
<code>u64 pss_shmem</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int file_thp</code>
</li>
</ul>
</details>
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
<b>Field removed. </b>
<code>bool check_shmem_swap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 pss_dirty</code>
</li>
</ul>
</details>
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
<code>long unsigned int ksm</code>
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
