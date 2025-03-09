# Struct: <code>ib_mr</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    enum ib_mr_type type;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct ib_sig_attrs * sig_attrs;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    enum ib_mr_type type;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct ib_sig_attrs * sig_attrs;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    enum ib_mr_type type;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct ib_sig_attrs * sig_attrs;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    enum ib_mr_type type;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct ib_sig_attrs * sig_attrs;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    enum ib_mr_type type;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct ib_sig_attrs * sig_attrs;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    enum ib_mr_type type;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct ib_sig_attrs * sig_attrs;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    enum ib_mr_type type;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct ib_sig_attrs * sig_attrs;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    enum ib_mr_type type;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct ib_sig_attrs * sig_attrs;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    enum ib_mr_type type;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct ib_sig_attrs * sig_attrs;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    enum ib_mr_type type;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct ib_sig_attrs * sig_attrs;
    struct rdma_restrack_entry res;
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
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    enum ib_mr_type type;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct ib_sig_attrs * sig_attrs;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    enum ib_mr_type type;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct ib_sig_attrs * sig_attrs;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    enum ib_mr_type type;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct ib_sig_attrs * sig_attrs;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    enum ib_mr_type type;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct ib_sig_attrs * sig_attrs;
    struct rdma_restrack_entry res;
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
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    enum ib_mr_type type;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct ib_sig_attrs * sig_attrs;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    enum ib_mr_type type;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct ib_sig_attrs * sig_attrs;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    enum ib_mr_type type;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct ib_sig_attrs * sig_attrs;
    struct rdma_restrack_entry res;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    enum ib_mr_type type;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
    struct ib_dm * dm;
    struct ib_sig_attrs * sig_attrs;
    struct rdma_restrack_entry res;
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
struct ib_mr {
    struct ib_device * device;
    struct ib_pd * pd;
    u32 lkey;
    u32 rkey;
    u64 iova;
    u64 length;
    unsigned int page_size;
    bool need_inval;
    struct ib_uobject * uobject;
    struct list_head qp_entry;
}
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct ib_dm * dm</code>
</li>
<li>
<b>Field added. </b>
<code>struct rdma_restrack_entry res</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum ib_mr_type type</code>
</li>
<li>
<b>Field added. </b>
<code>struct ib_sig_attrs * sig_attrs</code>
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
