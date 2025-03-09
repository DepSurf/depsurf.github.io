# Struct: <code>squashfs_super_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
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
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
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
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct squashfs_super_block {
    __le32 s_magic;
    __le32 inodes;
    __le32 mkfs_time;
    __le32 block_size;
    __le32 fragments;
    __le16 compression;
    __le16 block_log;
    __le16 flags;
    __le16 no_ids;
    __le16 s_major;
    __le16 s_minor;
    __le64 root_inode;
    __le64 bytes_used;
    __le64 id_table_start;
    __le64 xattr_id_table_start;
    __le64 inode_table_start;
    __le64 directory_table_start;
    __le64 fragment_table_start;
    __le64 lookup_table_start;
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
