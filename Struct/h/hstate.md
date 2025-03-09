# Struct: <code>hstate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct hstate {
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[64] hugepage_freelists;
    unsigned int[64] nr_huge_pages_node;
    unsigned int[64] free_huge_pages_node;
    unsigned int[64] surplus_huge_pages_node;
    struct cftype[5] cgroup_files;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct hstate {
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[64] hugepage_freelists;
    unsigned int[64] nr_huge_pages_node;
    unsigned int[64] free_huge_pages_node;
    unsigned int[64] surplus_huge_pages_node;
    struct cftype[5] cgroup_files;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct hstate {
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    struct cftype[5] cgroup_files;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct hstate {
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    struct cftype[5] cgroup_files;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct hstate {
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    struct cftype[5] cgroup_files;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct hstate {
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    struct cftype[5] cgroup_files;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct hstate {
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    struct cftype[5] cgroup_files;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct hstate {
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    struct cftype[5] cgroup_files;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct hstate {
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    struct cftype[5] cgroup_files;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct hstate {
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    struct cftype[7] cgroup_files_dfl;
    struct cftype[9] cgroup_files_legacy;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct hstate {
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    struct cftype[7] cgroup_files_dfl;
    struct cftype[9] cgroup_files_legacy;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct hstate {
    struct mutex resize_lock;
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    struct cftype[7] cgroup_files_dfl;
    struct cftype[9] cgroup_files_legacy;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct hstate {
    struct mutex resize_lock;
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    unsigned int nr_free_vmemmap_pages;
    struct cftype[7] cgroup_files_dfl;
    struct cftype[9] cgroup_files_legacy;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct hstate {
    struct mutex resize_lock;
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    unsigned int demote_order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] max_huge_pages_node;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    unsigned int optimize_vmemmap_pages;
    struct cftype[8] cgroup_files_dfl;
    struct cftype[10] cgroup_files_legacy;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct hstate {
    struct mutex resize_lock;
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    unsigned int demote_order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] max_huge_pages_node;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    struct cftype[8] cgroup_files_dfl;
    struct cftype[10] cgroup_files_legacy;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct hstate {
    struct mutex resize_lock;
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    unsigned int demote_order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] max_huge_pages_node;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    struct cftype[8] cgroup_files_dfl;
    struct cftype[10] cgroup_files_legacy;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct hstate {
    struct mutex resize_lock;
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    unsigned int demote_order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] max_huge_pages_node;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    struct cftype[8] cgroup_files_dfl;
    struct cftype[10] cgroup_files_legacy;
    char[32] name;
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
struct hstate {
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[64] hugepage_freelists;
    unsigned int[64] nr_huge_pages_node;
    unsigned int[64] free_huge_pages_node;
    unsigned int[64] surplus_huge_pages_node;
    struct cftype[5] cgroup_files;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct hstate {
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct hstate {
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[256] hugepage_freelists;
    unsigned int[256] nr_huge_pages_node;
    unsigned int[256] free_huge_pages_node;
    unsigned int[256] surplus_huge_pages_node;
    struct cftype[5] cgroup_files;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct hstate {
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1] hugepage_freelists;
    unsigned int[1] nr_huge_pages_node;
    unsigned int[1] free_huge_pages_node;
    unsigned int[1] surplus_huge_pages_node;
    struct cftype[5] cgroup_files;
    char[32] name;
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
struct hstate {
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    struct cftype[5] cgroup_files;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct hstate {
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    struct cftype[5] cgroup_files;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct hstate {
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    struct cftype[5] cgroup_files;
    char[32] name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct hstate {
    int next_nid_to_alloc;
    int next_nid_to_free;
    unsigned int order;
    long unsigned int mask;
    long unsigned int max_huge_pages;
    long unsigned int nr_huge_pages;
    long unsigned int free_huge_pages;
    long unsigned int resv_huge_pages;
    long unsigned int surplus_huge_pages;
    long unsigned int nr_overcommit_huge_pages;
    struct list_head hugepage_activelist;
    struct list_head[1024] hugepage_freelists;
    unsigned int[1024] nr_huge_pages_node;
    unsigned int[1024] free_huge_pages_node;
    unsigned int[1024] surplus_huge_pages_node;
    struct cftype[5] cgroup_files;
    char[32] name;
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
<code>struct list_head[64] hugepage_freelists</code> ➡️ <code>struct list_head[1024] hugepage_freelists</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int[64] nr_huge_pages_node</code> ➡️ <code>unsigned int[1024] nr_huge_pages_node</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int[64] free_huge_pages_node</code> ➡️ <code>unsigned int[1024] free_huge_pages_node</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int[64] surplus_huge_pages_node</code> ➡️ <code>unsigned int[1024] surplus_huge_pages_node</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct cftype[7] cgroup_files_dfl</code>
</li>
<li>
<b>Field added. </b>
<code>struct cftype[9] cgroup_files_legacy</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cftype[5] cgroup_files</code>
</li>
</ul>
</details>
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
<code>struct mutex resize_lock</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int nr_free_vmemmap_pages</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int demote_order</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int[1024] max_huge_pages_node</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int optimize_vmemmap_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int nr_free_vmemmap_pages</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct cftype[7] cgroup_files_dfl</code> ➡️ <code>struct cftype[8] cgroup_files_dfl</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct cftype[9] cgroup_files_legacy</code> ➡️ <code>struct cftype[10] cgroup_files_legacy</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int optimize_vmemmap_pages</code>
</li>
</ul>
</details>
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
<code>struct list_head[1024] hugepage_freelists</code> ➡️ <code>struct list_head[64] hugepage_freelists</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int[1024] nr_huge_pages_node</code> ➡️ <code>unsigned int[64] nr_huge_pages_node</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int[1024] free_huge_pages_node</code> ➡️ <code>unsigned int[64] free_huge_pages_node</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int[1024] surplus_huge_pages_node</code> ➡️ <code>unsigned int[64] surplus_huge_pages_node</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int next_nid_to_alloc</code>
</li>
<li>
<b>Field removed. </b>
<code>int next_nid_to_free</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int order</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int mask</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int max_huge_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int nr_huge_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int free_huge_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int resv_huge_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int surplus_huge_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int nr_overcommit_huge_pages</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head hugepage_activelist</code>
</li>
<li>
<b>Field removed. </b>
<code>struct list_head[1024] hugepage_freelists</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int[1024] nr_huge_pages_node</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int[1024] free_huge_pages_node</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int[1024] surplus_huge_pages_node</code>
</li>
<li>
<b>Field removed. </b>
<code>struct cftype[5] cgroup_files</code>
</li>
<li>
<b>Field removed. </b>
<code>char[32] name</code>
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
<code>struct list_head[1024] hugepage_freelists</code> ➡️ <code>struct list_head[256] hugepage_freelists</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int[1024] nr_huge_pages_node</code> ➡️ <code>unsigned int[256] nr_huge_pages_node</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int[1024] free_huge_pages_node</code> ➡️ <code>unsigned int[256] free_huge_pages_node</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int[1024] surplus_huge_pages_node</code> ➡️ <code>unsigned int[256] surplus_huge_pages_node</code>
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
<code>struct list_head[1024] hugepage_freelists</code> ➡️ <code>struct list_head[1] hugepage_freelists</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int[1024] nr_huge_pages_node</code> ➡️ <code>unsigned int[1] nr_huge_pages_node</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int[1024] free_huge_pages_node</code> ➡️ <code>unsigned int[1] free_huge_pages_node</code>
</li>
<li>
<b>Field type changed. </b>
<code>unsigned int[1024] surplus_huge_pages_node</code> ➡️ <code>unsigned int[1] surplus_huge_pages_node</code>
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
