# Struct: <code>vm_operations_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *) mremap;
    int (*)(struct vm_area_struct *, struct vm_fault *) fault;
    int (*)(struct vm_area_struct *, long unsigned int, pmd_t *, unsigned int) pmd_fault;
    void (*)(struct vm_area_struct *, struct vm_fault *) map_pages;
    int (*)(struct vm_area_struct *, struct vm_fault *) page_mkwrite;
    int (*)(struct vm_area_struct *, struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *) mremap;
    int (*)(struct vm_area_struct *, struct vm_fault *) fault;
    int (*)(struct vm_area_struct *, long unsigned int, pmd_t *, unsigned int) pmd_fault;
    void (*)(struct fault_env *, long unsigned int, long unsigned int) map_pages;
    int (*)(struct vm_area_struct *, struct vm_fault *) page_mkwrite;
    int (*)(struct vm_area_struct *, struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *) mremap;
    int (*)(struct vm_area_struct *, struct vm_fault *) fault;
    int (*)(struct vm_area_struct *, long unsigned int, pmd_t *, unsigned int) pmd_fault;
    void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    int (*)(struct vm_area_struct *, struct vm_fault *) page_mkwrite;
    int (*)(struct vm_area_struct *, struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *) mremap;
    int (*)(struct vm_fault *) fault;
    int (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    int (*)(struct vm_fault *) page_mkwrite;
    int (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) split;
    int (*)(struct vm_area_struct *) mremap;
    int (*)(struct vm_fault *) fault;
    int (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    int (*)(struct vm_fault *) page_mkwrite;
    int (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) split;
    int (*)(struct vm_area_struct *) mremap;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) split;
    int (*)(struct vm_area_struct *) mremap;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) split;
    int (*)(struct vm_area_struct *) mremap;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) split;
    int (*)(struct vm_area_struct *) mremap;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) split;
    int (*)(struct vm_area_struct *) mremap;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) may_split;
    int (*)(struct vm_area_struct *, long unsigned int) mremap;
    int (*)(struct vm_area_struct *, long unsigned int, long unsigned int, long unsigned int) mprotect;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) may_split;
    int (*)(struct vm_area_struct *) mremap;
    int (*)(struct vm_area_struct *, long unsigned int, long unsigned int, long unsigned int) mprotect;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    vm_fault_t (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) may_split;
    int (*)(struct vm_area_struct *) mremap;
    int (*)(struct vm_area_struct *, long unsigned int, long unsigned int, long unsigned int) mprotect;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    vm_fault_t (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) may_split;
    int (*)(struct vm_area_struct *) mremap;
    int (*)(struct vm_area_struct *, long unsigned int, long unsigned int, long unsigned int) mprotect;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    vm_fault_t (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) may_split;
    int (*)(struct vm_area_struct *) mremap;
    int (*)(struct vm_area_struct *, long unsigned int, long unsigned int, long unsigned int) mprotect;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    vm_fault_t (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) may_split;
    int (*)(struct vm_area_struct *) mremap;
    int (*)(struct vm_area_struct *, long unsigned int, long unsigned int, long unsigned int) mprotect;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    vm_fault_t (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) may_split;
    int (*)(struct vm_area_struct *) mremap;
    int (*)(struct vm_area_struct *, long unsigned int, long unsigned int, long unsigned int) mprotect;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, unsigned int) huge_fault;
    vm_fault_t (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int, long unsigned int *) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
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
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) split;
    int (*)(struct vm_area_struct *) mremap;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) split;
    int (*)(struct vm_area_struct *) mremap;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) split;
    int (*)(struct vm_area_struct *) mremap;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) split;
    int (*)(struct vm_area_struct *) mremap;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
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
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) split;
    int (*)(struct vm_area_struct *) mremap;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) split;
    int (*)(struct vm_area_struct *) mremap;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) split;
    int (*)(struct vm_area_struct *) mremap;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct vm_operations_struct {
    void (*)(struct vm_area_struct *) open;
    void (*)(struct vm_area_struct *) close;
    int (*)(struct vm_area_struct *, long unsigned int) split;
    int (*)(struct vm_area_struct *) mremap;
    vm_fault_t (*)(struct vm_fault *) fault;
    vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault;
    void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages;
    long unsigned int (*)(struct vm_area_struct *) pagesize;
    vm_fault_t (*)(struct vm_fault *) page_mkwrite;
    vm_fault_t (*)(struct vm_fault *) pfn_mkwrite;
    int (*)(struct vm_area_struct *, long unsigned int, void *, int, int) access;
    const char * (*)(struct vm_area_struct *) name;
    int (*)(struct vm_area_struct *, struct mempolicy *) set_policy;
    struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy;
    struct page * (*)(struct vm_area_struct *, long unsigned int) find_special_page;
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
<b>Field type changed. </b>
<code>void (*)(struct vm_area_struct *, struct vm_fault *) map_pages</code> ➡️ <code>void (*)(struct fault_env *, long unsigned int, long unsigned int) map_pages</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>void (*)(struct fault_env *, long unsigned int, long unsigned int) map_pages</code> ➡️ <code>void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct vm_fault *, enum page_entry_size) huge_fault</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct vm_area_struct *, long unsigned int, pmd_t *, unsigned int) pmd_fault</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct vm_area_struct *, struct vm_fault *) fault</code> ➡️ <code>int (*)(struct vm_fault *) fault</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct vm_area_struct *, struct vm_fault *) page_mkwrite</code> ➡️ <code>int (*)(struct vm_fault *) page_mkwrite</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct vm_area_struct *, struct vm_fault *) pfn_mkwrite</code> ➡️ <code>int (*)(struct vm_fault *) pfn_mkwrite</code>
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
<code>int (*)(struct vm_area_struct *, long unsigned int) split</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int (*)(struct vm_area_struct *) pagesize</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct vm_fault *) fault</code> ➡️ <code>vm_fault_t (*)(struct vm_fault *) fault</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct vm_fault *, enum page_entry_size) huge_fault</code> ➡️ <code>vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct vm_fault *) page_mkwrite</code> ➡️ <code>vm_fault_t (*)(struct vm_fault *) page_mkwrite</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct vm_fault *) pfn_mkwrite</code> ➡️ <code>vm_fault_t (*)(struct vm_fault *) pfn_mkwrite</code>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct vm_area_struct *, long unsigned int) may_split</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct vm_area_struct *, long unsigned int, long unsigned int, long unsigned int) mprotect</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct vm_area_struct *, long unsigned int) split</code>
</li>
<li>
<b>Field type changed. </b>
<code>int (*)(struct vm_area_struct *) mremap</code> ➡️ <code>int (*)(struct vm_area_struct *, long unsigned int) mremap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int (*)(struct vm_area_struct *, long unsigned int) mremap</code> ➡️ <code>int (*)(struct vm_area_struct *) mremap</code>
</li>
<li>
<b>Field type changed. </b>
<code>void (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages</code> ➡️ <code>vm_fault_t (*)(struct vm_fault *, long unsigned int, long unsigned int) map_pages</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>vm_fault_t (*)(struct vm_fault *, enum page_entry_size) huge_fault</code> ➡️ <code>vm_fault_t (*)(struct vm_fault *, unsigned int) huge_fault</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy</code> ➡️ <code>struct mempolicy * (*)(struct vm_area_struct *, long unsigned int, long unsigned int *) get_policy</code>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct vm_area_struct *, struct mempolicy *) set_policy</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct vm_area_struct *, struct mempolicy *) set_policy</code>
</li>
<li>
<b>Field removed. </b>
<code>struct mempolicy * (*)(struct vm_area_struct *, long unsigned int) get_policy</code>
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
