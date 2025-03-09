# Struct: <code>unixware_disklabel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
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
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
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
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct unixware_disklabel {
    __le32 d_type;
    __le32 d_magic;
    __le32 d_version;
    char[12] d_serial;
    __le32 d_ncylinders;
    __le32 d_ntracks;
    __le32 d_nsectors;
    __le32 d_secsize;
    __le32 d_part_start;
    __le32[12] d_unknown1;
    __le32 d_alt_tbl;
    __le32 d_alt_len;
    __le32 d_phys_cyl;
    __le32 d_phys_trk;
    __le32 d_phys_sec;
    __le32 d_phys_bytes;
    __le32 d_unknown2;
    __le32 d_unknown3;
    __le32[8] d_pad;
    struct unixware_vtoc vtoc;
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
