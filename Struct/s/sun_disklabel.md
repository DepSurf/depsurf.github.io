# Struct: <code>sun_disklabel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
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
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
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
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct sun_disklabel {
    unsigned char[128] info;
    struct sun_vtoc vtoc;
    __be32 write_reinstruct;
    __be32 read_reinstruct;
    unsigned char[148] spare;
    __be16 rspeed;
    __be16 pcylcount;
    __be16 sparecyl;
    __be16 obs1;
    __be16 obs2;
    __be16 ilfact;
    __be16 ncyl;
    __be16 nacyl;
    __be16 ntrks;
    __be16 nsect;
    __be16 obs3;
    __be16 obs4;
    struct sun_partition[8] partitions;
    __be16 magic;
    __be16 csum;
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
