# Struct: <code>disklabel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
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
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
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
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct disklabel {
    __le32 d_magic;
    __le16 d_type;
    __le16 d_subtype;
    u8[16] d_typename;
    u8[16] d_packname;
    __le32 d_secsize;
    __le32 d_nsectors;
    __le32 d_ntracks;
    __le32 d_ncylinders;
    __le32 d_secpercyl;
    __le32 d_secprtunit;
    __le16 d_sparespertrack;
    __le16 d_sparespercyl;
    __le32 d_acylinders;
    __le16 d_rpm;
    __le16 d_interleave;
    __le16 d_trackskew;
    __le16 d_cylskew;
    __le32 d_headswitch;
    __le32 d_trkseek;
    __le32 d_flags;
    __le32[5] d_drivedata;
    __le32[5] d_spare;
    __le32 d_magic2;
    __le16 d_checksum;
    __le16 d_npartitions;
    __le32 d_bbsize;
    __le32 d_sbsize;
    struct d_partition[18] d_partitions;
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
