# Struct: <code>compat_cdrom_generic_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t[1] reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t[1] reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t[1] reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t[1] reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t[1] reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t[1] reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t[1] reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t[1] reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t[1] reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t[1] reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    unsigned char[3] pad;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    unsigned char[3] pad;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    unsigned char[3] pad;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    unsigned char[3] pad;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    unsigned char[3] pad;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    unsigned char[3] pad;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    unsigned char[3] pad;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t unused;
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
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t[1] reserved;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t[1] reserved;
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t[1] reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t[1] reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t[1] reserved;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t[1] reserved;
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
<code>unsigned char[3] pad</code>
</li>
<li>
<b>Field added. </b>
<code>compat_caddr_t unused</code>
</li>
<li>
<b>Field removed. </b>
<code>compat_caddr_t[1] reserved</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t[1] reserved;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct compat_cdrom_generic_command {
    unsigned char[12] cmd;
    compat_caddr_t buffer;
    compat_uint_t buflen;
    compat_int_t stat;
    compat_caddr_t sense;
    unsigned char data_direction;
    compat_int_t quiet;
    compat_int_t timeout;
    compat_caddr_t[1] reserved;
}
```
</details>
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
