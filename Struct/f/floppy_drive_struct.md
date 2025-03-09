# Struct: <code>floppy_drive_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct floppy_drive_struct {
    long unsigned int flags;
    long unsigned int spinup_date;
    long unsigned int select_date;
    long unsigned int first_read_date;
    short int probed_format;
    short int track;
    short int maxblock;
    short int maxtrack;
    int generation;
    int keep_data;
    int fd_ref;
    int fd_device;
    long unsigned int last_checked;
    char * dmabuf;
    int bufblocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct floppy_drive_struct {
    long unsigned int flags;
    long unsigned int spinup_date;
    long unsigned int select_date;
    long unsigned int first_read_date;
    short int probed_format;
    short int track;
    short int maxblock;
    short int maxtrack;
    int generation;
    int keep_data;
    int fd_ref;
    int fd_device;
    long unsigned int last_checked;
    char * dmabuf;
    int bufblocks;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct floppy_drive_struct {
    long unsigned int flags;
    long unsigned int spinup_date;
    long unsigned int select_date;
    long unsigned int first_read_date;
    short int probed_format;
    short int track;
    short int maxblock;
    short int maxtrack;
    int generation;
    int keep_data;
    int fd_ref;
    int fd_device;
    long unsigned int last_checked;
    char * dmabuf;
    int bufblocks;
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
struct floppy_drive_struct {
    long unsigned int flags;
    long unsigned int spinup_date;
    long unsigned int select_date;
    long unsigned int first_read_date;
    short int probed_format;
    short int track;
    short int maxblock;
    short int maxtrack;
    int generation;
    int keep_data;
    int fd_ref;
    int fd_device;
    long unsigned int last_checked;
    char * dmabuf;
    int bufblocks;
}
```
</details>
</li>
</ul>
