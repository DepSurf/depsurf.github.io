# Struct: <code>rand_data</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int stuck;
    unsigned int osr;
    unsigned int stir;
    unsigned int disable_unbias;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int stuck;
    unsigned int osr;
    unsigned int stir;
    unsigned int disable_unbias;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int stuck;
    unsigned int osr;
    unsigned int stir;
    unsigned int disable_unbias;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int stuck;
    unsigned int osr;
    unsigned int stir;
    unsigned int disable_unbias;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int stuck;
    unsigned int osr;
    unsigned int stir;
    unsigned int disable_unbias;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int stuck;
    unsigned int osr;
    unsigned int stir;
    unsigned int disable_unbias;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int osr;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int osr;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int osr;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
    int rct_count;
    unsigned int apt_observations;
    unsigned int apt_count;
    unsigned int apt_base;
    unsigned int apt_base_set;
    unsigned int health_failure;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int osr;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
    int rct_count;
    unsigned int apt_observations;
    unsigned int apt_count;
    unsigned int apt_base;
    unsigned int apt_base_set;
    unsigned int health_failure;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int osr;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
    int rct_count;
    unsigned int apt_observations;
    unsigned int apt_count;
    unsigned int apt_base;
    unsigned int apt_base_set;
    unsigned int health_failure;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int osr;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
    int rct_count;
    unsigned int apt_observations;
    unsigned int apt_count;
    unsigned int apt_base;
    unsigned int apt_base_set;
    unsigned int health_failure;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int osr;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
    int rct_count;
    unsigned int apt_observations;
    unsigned int apt_count;
    unsigned int apt_base;
    unsigned int apt_base_set;
    unsigned int health_failure;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int osr;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
    int rct_count;
    unsigned int apt_observations;
    unsigned int apt_count;
    unsigned int apt_base;
    unsigned int apt_base_set;
    unsigned int health_failure;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct rand_data {
    void * hash_state;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int osr;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
    unsigned int rct_count;
    unsigned int apt_observations;
    unsigned int apt_count;
    unsigned int apt_base;
    unsigned int apt_base_set;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct rand_data {
    void * hash_state;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int flags;
    unsigned int osr;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
    unsigned int rct_count;
    unsigned int apt_cutoff;
    unsigned int apt_cutoff_permanent;
    unsigned int apt_observations;
    unsigned int apt_count;
    unsigned int apt_base;
    unsigned int health_failure;
    unsigned int apt_base_set;
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
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int osr;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int osr;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int osr;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int osr;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
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
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int osr;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int osr;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int osr;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int osr;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct rand_data {
    __u64 data;
    __u64 old_data;
    __u64 prev_time;
    __u64 last_delta;
    __s64 last_delta2;
    unsigned int stuck;
    unsigned int osr;
    unsigned int stir;
    unsigned int disable_unbias;
    unsigned char * mem;
    unsigned int memlocation;
    unsigned int memblocks;
    unsigned int memblocksize;
    unsigned int memaccessloops;
}
```
</details>
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int stuck</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int stir</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int disable_unbias</code>
</li>
</ul>
</details>
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
<code>int rct_count</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int apt_observations</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int apt_count</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int apt_base</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int apt_base_set</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int health_failure</code>
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
<b>Field added. </b>
<code>void * hash_state</code>
</li>
<li>
<b>Field removed. </b>
<code>__u64 data</code>
</li>
<li>
<b>Field removed. </b>
<code>__u64 old_data</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int health_failure</code>
</li>
<li>
<b>Field type changed. </b>
<code>int rct_count</code> ➡️ <code>unsigned int rct_count</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int apt_cutoff</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int apt_cutoff_permanent</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int health_failure</code>
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
