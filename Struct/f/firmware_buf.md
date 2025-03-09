# Struct: <code>firmware_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct firmware_buf {
    struct kref ref;
    struct list_head list;
    struct completion completion;
    struct firmware_cache * fwc;
    long unsigned int status;
    void * data;
    size_t size;
    bool is_paged_buf;
    bool need_uevent;
    struct page * * pages;
    int nr_pages;
    int page_array_size;
    struct list_head pending_list;
    const char * fw_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct firmware_buf {
    struct kref ref;
    struct list_head list;
    struct completion completion;
    struct firmware_cache * fwc;
    long unsigned int status;
    void * data;
    size_t size;
    size_t allocated_size;
    bool is_paged_buf;
    bool need_uevent;
    struct page * * pages;
    int nr_pages;
    int page_array_size;
    struct list_head pending_list;
    const char * fw_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct firmware_buf {
    struct kref ref;
    struct list_head list;
    struct firmware_cache * fwc;
    struct fw_state fw_st;
    void * data;
    size_t size;
    size_t allocated_size;
    bool is_paged_buf;
    bool need_uevent;
    struct page * * pages;
    int nr_pages;
    int page_array_size;
    struct list_head pending_list;
    const char * fw_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct firmware_buf {
    struct kref ref;
    struct list_head list;
    struct firmware_cache * fwc;
    struct fw_state fw_st;
    void * data;
    size_t size;
    size_t allocated_size;
    bool is_paged_buf;
    bool need_uevent;
    struct page * * pages;
    int nr_pages;
    int page_array_size;
    struct list_head pending_list;
    const char * fw_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct firmware_buf {
    struct kref ref;
    struct list_head list;
    struct firmware_cache * fwc;
    struct fw_state fw_st;
    void * data;
    size_t size;
    size_t allocated_size;
    bool is_paged_buf;
    bool need_uevent;
    struct page * * pages;
    int nr_pages;
    int page_array_size;
    struct list_head pending_list;
    const char * fw_id;
}
```
</details>
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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>size_t allocated_size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct fw_state fw_st</code>
</li>
<li>
<b>Field removed. </b>
<code>struct completion completion</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int status</code>
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
struct firmware_buf {
    struct kref ref;
    struct list_head list;
    struct firmware_cache * fwc;
    struct fw_state fw_st;
    void * data;
    size_t size;
    size_t allocated_size;
    bool is_paged_buf;
    bool need_uevent;
    struct page * * pages;
    int nr_pages;
    int page_array_size;
    struct list_head pending_list;
    const char * fw_id;
}
```
</details>
</li>
</ul>
