# Struct: <code>mdp_superblock_1</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
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
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
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
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mdp_superblock_1 {
    __le32 magic;
    __le32 major_version;
    __le32 feature_map;
    __le32 pad0;
    __u8[16] set_uuid;
    char[32] set_name;
    __le64 ctime;
    __le32 level;
    __le32 layout;
    __le64 size;
    __le32 chunksize;
    __le32 raid_disks;
    __le32 bitmap_offset;
    struct (anon) ppl;
    __le32 new_level;
    __le64 reshape_position;
    __le32 delta_disks;
    __le32 new_layout;
    __le32 new_chunk;
    __le32 new_offset;
    __le64 data_offset;
    __le64 data_size;
    __le64 super_offset;
    __le64 recovery_offset;
    __le64 journal_tail;
    __le32 dev_number;
    __le32 cnt_corrected_read;
    __u8[16] device_uuid;
    __u8 devflags;
    __u8 bblog_shift;
    __le16 bblog_size;
    __le32 bblog_offset;
    __le64 utime;
    __le64 events;
    __le64 resync_offset;
    __le32 sb_csum;
    __le32 max_dev;
    __u8[32] pad3;
    __le16[0] dev_roles;
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct (anon) ppl</code>
</li>
</ul>
</details>
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
