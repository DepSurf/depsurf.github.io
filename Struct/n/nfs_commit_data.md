# Struct: <code>nfs_commit_data</code>

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
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    struct rpc_cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    struct rpc_cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    struct rpc_cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    struct rpc_cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    struct rpc_cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
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
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
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
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
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
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    struct rpc_cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct rpc_cred * cred</code> ➡️ <code>const struct cred * cred</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct nfs_commit_data {
    struct rpc_task task;
    struct inode * inode;
    const struct cred * cred;
    struct nfs_fattr fattr;
    struct nfs_writeverf verf;
    struct list_head pages;
    struct list_head list;
    struct nfs_direct_req * dreq;
    struct nfs_commitargs args;
    struct nfs_commitres res;
    struct nfs_open_context * context;
    struct pnfs_layout_segment * lseg;
    struct nfs_client * ds_clp;
    int ds_commit_index;
    loff_t lwb;
    const struct rpc_call_ops * mds_ops;
    const struct nfs_commit_completion_ops * completion_ops;
    int (*)(struct rpc_task *, struct nfs_commit_data *) commit_done_cb;
    long unsigned int flags;
}
```
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
