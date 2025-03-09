# Struct: <code>writeback_control</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    unsigned int no_cgroup_owner;
    unsigned int punt_to_cgroup;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    unsigned int no_cgroup_owner;
    unsigned int punt_to_cgroup;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    unsigned int no_cgroup_owner;
    unsigned int punt_to_cgroup;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    unsigned int no_cgroup_owner;
    unsigned int punt_to_cgroup;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    unsigned int no_cgroup_owner;
    unsigned int punt_to_cgroup;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    unsigned int no_cgroup_owner;
    unsigned int punt_to_cgroup;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    unsigned int unpinned_fscache_wb;
    unsigned int no_cgroup_owner;
    unsigned int punt_to_cgroup;
    struct swap_iocb * * swap_plug;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    unsigned int unpinned_fscache_wb;
    unsigned int no_cgroup_owner;
    unsigned int punt_to_cgroup;
    struct swap_iocb * * swap_plug;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    unsigned int unpinned_fscache_wb;
    unsigned int no_cgroup_owner;
    struct swap_iocb * * swap_plug;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    unsigned int unpinned_netfs_wb;
    unsigned int no_cgroup_owner;
    struct swap_iocb * * swap_plug;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
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
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    unsigned int no_cgroup_owner;
    unsigned int punt_to_cgroup;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    unsigned int no_cgroup_owner;
    unsigned int punt_to_cgroup;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    unsigned int no_cgroup_owner;
    unsigned int punt_to_cgroup;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    unsigned int no_cgroup_owner;
    unsigned int punt_to_cgroup;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
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
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    unsigned int no_cgroup_owner;
    unsigned int punt_to_cgroup;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    unsigned int no_cgroup_owner;
    unsigned int punt_to_cgroup;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    unsigned int no_cgroup_owner;
    unsigned int punt_to_cgroup;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct writeback_control {
    long int nr_to_write;
    long int pages_skipped;
    loff_t range_start;
    loff_t range_end;
    enum writeback_sync_modes sync_mode;
    unsigned int for_kupdate;
    unsigned int for_background;
    unsigned int tagged_writepages;
    unsigned int for_reclaim;
    unsigned int range_cyclic;
    unsigned int for_sync;
    unsigned int no_cgroup_owner;
    unsigned int punt_to_cgroup;
    struct bdi_writeback * wb;
    struct inode * inode;
    int wb_id;
    int wb_lcand_id;
    int wb_tcand_id;
    size_t wb_bytes;
    size_t wb_lcand_bytes;
    size_t wb_tcand_bytes;
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
<b>Field added. </b>
<code>unsigned int no_cgroup_owner</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int punt_to_cgroup</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int unpinned_fscache_wb</code>
</li>
<li>
<b>Field added. </b>
<code>struct swap_iocb * * swap_plug</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int punt_to_cgroup</code>
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
<code>unsigned int unpinned_netfs_wb</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int unpinned_fscache_wb</code>
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
