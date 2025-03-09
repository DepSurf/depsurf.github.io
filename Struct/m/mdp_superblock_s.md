# Struct: <code>mdp_superblock_s</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
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
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
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
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mdp_superblock_s {
    __u32 md_magic;
    __u32 major_version;
    __u32 minor_version;
    __u32 patch_version;
    __u32 gvalid_words;
    __u32 set_uuid0;
    __u32 ctime;
    __u32 level;
    __u32 size;
    __u32 nr_disks;
    __u32 raid_disks;
    __u32 md_minor;
    __u32 not_persistent;
    __u32 set_uuid1;
    __u32 set_uuid2;
    __u32 set_uuid3;
    __u32[16] gstate_creserved;
    __u32 utime;
    __u32 state;
    __u32 active_disks;
    __u32 working_disks;
    __u32 failed_disks;
    __u32 spare_disks;
    __u32 sb_csum;
    __u32 events_lo;
    __u32 events_hi;
    __u32 cp_events_lo;
    __u32 cp_events_hi;
    __u32 recovery_cp;
    __u64 reshape_position;
    __u32 new_level;
    __u32 delta_disks;
    __u32 new_layout;
    __u32 new_chunk;
    __u32[14] gstate_sreserved;
    __u32 layout;
    __u32 chunk_size;
    __u32 root_pv;
    __u32 root_block;
    __u32[60] pstate_reserved;
    mdp_disk_t[27] disks;
    __u32[0] reserved;
    mdp_disk_t this_disk;
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
