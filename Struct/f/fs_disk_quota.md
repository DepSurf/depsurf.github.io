# Struct: <code>fs_disk_quota</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s32 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s32 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s32 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s32 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s32 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s32 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s32 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s32 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s32 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s32 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s8 d_itimer_hi;
    __s8 d_btimer_hi;
    __s8 d_rtbtimer_hi;
    __s8 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s8 d_itimer_hi;
    __s8 d_btimer_hi;
    __s8 d_rtbtimer_hi;
    __s8 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s8 d_itimer_hi;
    __s8 d_btimer_hi;
    __s8 d_rtbtimer_hi;
    __s8 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s8 d_itimer_hi;
    __s8 d_btimer_hi;
    __s8 d_rtbtimer_hi;
    __s8 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s8 d_itimer_hi;
    __s8 d_btimer_hi;
    __s8 d_rtbtimer_hi;
    __s8 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s8 d_itimer_hi;
    __s8 d_btimer_hi;
    __s8 d_rtbtimer_hi;
    __s8 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s8 d_itimer_hi;
    __s8 d_btimer_hi;
    __s8 d_rtbtimer_hi;
    __s8 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
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
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s32 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s32 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s32 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s32 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
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
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s32 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s32 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s32 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fs_disk_quota {
    __s8 d_version;
    __s8 d_flags;
    __u16 d_fieldmask;
    __u32 d_id;
    __u64 d_blk_hardlimit;
    __u64 d_blk_softlimit;
    __u64 d_ino_hardlimit;
    __u64 d_ino_softlimit;
    __u64 d_bcount;
    __u64 d_icount;
    __s32 d_itimer;
    __s32 d_btimer;
    __u16 d_iwarns;
    __u16 d_bwarns;
    __s32 d_padding2;
    __u64 d_rtb_hardlimit;
    __u64 d_rtb_softlimit;
    __u64 d_rtbcount;
    __s32 d_rtbtimer;
    __u16 d_rtbwarns;
    __s16 d_padding3;
    char[8] d_padding4;
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
<code>__s8 d_itimer_hi</code>
</li>
<li>
<b>Field added. </b>
<code>__s8 d_btimer_hi</code>
</li>
<li>
<b>Field added. </b>
<code>__s8 d_rtbtimer_hi</code>
</li>
<li>
<b>Field type changed. </b>
<code>__s32 d_padding2</code> ➡️ <code>__s8 d_padding2</code>
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
