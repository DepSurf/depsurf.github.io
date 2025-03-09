# Struct: <code>export_operations</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
    u64 (*)(struct inode *) fetch_iversion;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
    u64 (*)(struct inode *) fetch_iversion;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
    u64 (*)(struct inode *) fetch_iversion;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
    u64 (*)(struct inode *) fetch_iversion;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
    long unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
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
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
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
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct export_operations {
    int (*)(struct inode *, __u32 *, int *, struct inode *) encode_fh;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_dentry;
    struct dentry * (*)(struct super_block *, struct fid *, int, int) fh_to_parent;
    int (*)(struct dentry *, char *, struct dentry *) get_name;
    struct dentry * (*)(struct dentry *) get_parent;
    int (*)(struct inode *) commit_metadata;
    int (*)(struct super_block *, u8 *, u32 *, u64 *) get_uuid;
    int (*)(struct inode *, loff_t, u64, struct iomap *, bool, u32 *) map_blocks;
    int (*)(struct inode *, struct iomap *, int, struct iattr *) commit_blocks;
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
<code>long unsigned int flags</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 (*)(struct inode *) fetch_iversion</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>u64 (*)(struct inode *) fetch_iversion</code>
</li>
</ul>
</details>
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
