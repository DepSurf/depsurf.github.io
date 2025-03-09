# Struct: <code>dm_stat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[256] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[256] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
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
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[256] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[4] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[2048] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
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
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct dm_stat {
    struct list_head list_entry;
    int id;
    unsigned int stat_flags;
    size_t n_entries;
    sector_t start;
    sector_t end;
    sector_t step;
    unsigned int n_histogram_entries;
    long long unsigned int * histogram_boundaries;
    const char * program_id;
    const char * aux_data;
    struct callback_head callback_head;
    size_t shared_alloc_size;
    size_t percpu_alloc_size;
    size_t histogram_alloc_size;
    struct dm_stat_percpu *[8192] stat_percpu;
    struct dm_stat_shared[0] stat_shared;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct dm_stat_percpu *[256] stat_percpu</code> ➡️ <code>struct dm_stat_percpu *[8192] stat_percpu</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct dm_stat_percpu *[8192] stat_percpu</code> ➡️ <code>struct dm_stat_percpu *[256] stat_percpu</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct dm_stat_percpu *[8192] stat_percpu</code> ➡️ <code>struct dm_stat_percpu *[4] stat_percpu</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct dm_stat_percpu *[8192] stat_percpu</code> ➡️ <code>struct dm_stat_percpu *[2048] stat_percpu</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct dm_stat_percpu *[8192] stat_percpu</code> ➡️ <code>struct dm_stat_percpu *[8] stat_percpu</code>
</li>
</ul>
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
