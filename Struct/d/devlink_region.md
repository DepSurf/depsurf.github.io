# Struct: <code>devlink_region</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct devlink_region {
    struct devlink * devlink;
    struct list_head list;
    const char * name;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct devlink_region {
    struct devlink * devlink;
    struct list_head list;
    const char * name;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct devlink_region {
    struct devlink * devlink;
    struct list_head list;
    const struct devlink_region_ops * ops;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct devlink_region {
    struct devlink * devlink;
    struct devlink_port * port;
    struct list_head list;
    const struct devlink_region_ops * ops;
    const struct devlink_port_region_ops * port_ops;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct devlink_region {
    struct devlink * devlink;
    struct devlink_port * port;
    struct list_head list;
    const struct devlink_region_ops * ops;
    const struct devlink_port_region_ops * port_ops;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct devlink_region {
    struct devlink * devlink;
    struct devlink_port * port;
    struct list_head list;
    const struct devlink_region_ops * ops;
    const struct devlink_port_region_ops * port_ops;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct devlink_region {
    struct devlink * devlink;
    struct devlink_port * port;
    struct list_head list;
    const struct devlink_region_ops * ops;
    const struct devlink_port_region_ops * port_ops;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct devlink_region {
    struct devlink * devlink;
    struct devlink_port * port;
    struct list_head list;
    const struct devlink_region_ops * ops;
    const struct devlink_port_region_ops * port_ops;
    struct mutex snapshot_lock;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct devlink_region {
    struct devlink * devlink;
    struct devlink_port * port;
    struct list_head list;
    const struct devlink_region_ops * ops;
    const struct devlink_port_region_ops * port_ops;
    struct mutex snapshot_lock;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct devlink_region {
    struct devlink * devlink;
    struct devlink_port * port;
    struct list_head list;
    const struct devlink_region_ops * ops;
    const struct devlink_port_region_ops * port_ops;
    struct mutex snapshot_lock;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
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
struct devlink_region {
    struct devlink * devlink;
    struct list_head list;
    const char * name;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct devlink_region {
    struct devlink * devlink;
    struct list_head list;
    const char * name;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct devlink_region {
    struct devlink * devlink;
    struct list_head list;
    const char * name;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct devlink_region {
    struct devlink * devlink;
    struct list_head list;
    const char * name;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
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
struct devlink_region {
    struct devlink * devlink;
    struct list_head list;
    const char * name;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct devlink_region {
    struct devlink * devlink;
    struct list_head list;
    const char * name;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct devlink_region {
    struct devlink * devlink;
    struct list_head list;
    const char * name;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct devlink_region {
    struct devlink * devlink;
    struct list_head list;
    const char * name;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct devlink_region {
    struct devlink * devlink;
    struct list_head list;
    const char * name;
    struct list_head snapshot_list;
    u32 max_snapshots;
    u32 cur_snapshots;
    u64 size;
}
```
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
<code>const struct devlink_region_ops * ops</code>
</li>
<li>
<b>Field removed. </b>
<code>const char * name</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct devlink_port * port</code>
</li>
<li>
<b>Field added. </b>
<code>const struct devlink_port_region_ops * port_ops</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mutex snapshot_lock</code>
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
