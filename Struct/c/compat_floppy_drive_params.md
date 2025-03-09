# Struct: <code>compat_floppy_drive_params</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct compat_floppy_drive_params {
    char cmos;
    compat_ulong_t max_dtr;
    compat_ulong_t hlt;
    compat_ulong_t hut;
    compat_ulong_t srt;
    compat_ulong_t spinup;
    compat_ulong_t spindown;
    unsigned char spindown_offset;
    unsigned char select_delay;
    unsigned char rps;
    unsigned char tracks;
    compat_ulong_t timeout;
    unsigned char interleave_sect;
    struct floppy_max_errors max_errors;
    char flags;
    char read_track;
    short int[8] autodetect;
    compat_int_t checkfreq;
    compat_int_t native_format;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct compat_floppy_drive_params {
    char cmos;
    compat_ulong_t max_dtr;
    compat_ulong_t hlt;
    compat_ulong_t hut;
    compat_ulong_t srt;
    compat_ulong_t spinup;
    compat_ulong_t spindown;
    unsigned char spindown_offset;
    unsigned char select_delay;
    unsigned char rps;
    unsigned char tracks;
    compat_ulong_t timeout;
    unsigned char interleave_sect;
    struct floppy_max_errors max_errors;
    char flags;
    char read_track;
    short int[8] autodetect;
    compat_int_t checkfreq;
    compat_int_t native_format;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct compat_floppy_drive_params {
    char cmos;
    compat_ulong_t max_dtr;
    compat_ulong_t hlt;
    compat_ulong_t hut;
    compat_ulong_t srt;
    compat_ulong_t spinup;
    compat_ulong_t spindown;
    unsigned char spindown_offset;
    unsigned char select_delay;
    unsigned char rps;
    unsigned char tracks;
    compat_ulong_t timeout;
    unsigned char interleave_sect;
    struct floppy_max_errors max_errors;
    char flags;
    char read_track;
    short int[8] autodetect;
    compat_int_t checkfreq;
    compat_int_t native_format;
}
```
</details>
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
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
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct compat_floppy_drive_params {
    char cmos;
    compat_ulong_t max_dtr;
    compat_ulong_t hlt;
    compat_ulong_t hut;
    compat_ulong_t srt;
    compat_ulong_t spinup;
    compat_ulong_t spindown;
    unsigned char spindown_offset;
    unsigned char select_delay;
    unsigned char rps;
    unsigned char tracks;
    compat_ulong_t timeout;
    unsigned char interleave_sect;
    struct floppy_max_errors max_errors;
    char flags;
    char read_track;
    short int[8] autodetect;
    compat_int_t checkfreq;
    compat_int_t native_format;
}
```
</details>
</li>
</ul>
