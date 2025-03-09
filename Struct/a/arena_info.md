# Struct: <code>arena_info</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct arena_info {
    u64 size;
    u64 external_lba_start;
    u32 internal_nlba;
    u32 internal_lbasize;
    u32 external_nlba;
    u32 external_lbasize;
    u32 nfree;
    u16 version_major;
    u16 version_minor;
    u32 sector_size;
    u64 nextoff;
    u64 infooff;
    u64 dataoff;
    u64 mapoff;
    u64 logoff;
    u64 info2off;
    struct free_entry * freelist;
    u32 * rtt;
    struct aligned_lock * map_locks;
    struct nd_btt * nd_btt;
    struct list_head list;
    struct dentry * debugfs_dir;
    u32 flags;
    struct mutex err_lock;
    int[2] log_index;
}
```
</details>
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
struct arena_info {
    u64 size;
    u64 external_lba_start;
    u32 internal_nlba;
    u32 internal_lbasize;
    u32 external_nlba;
    u32 external_lbasize;
    u32 nfree;
    u16 version_major;
    u16 version_minor;
    u32 sector_size;
    u64 nextoff;
    u64 infooff;
    u64 dataoff;
    u64 mapoff;
    u64 logoff;
    u64 info2off;
    struct free_entry * freelist;
    u32 * rtt;
    struct aligned_lock * map_locks;
    struct nd_btt * nd_btt;
    struct list_head list;
    struct dentry * debugfs_dir;
    u32 flags;
    struct mutex err_lock;
    int[2] log_index;
}
```
</details>
</li>
</ul>
