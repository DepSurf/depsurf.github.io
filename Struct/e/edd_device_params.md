# Struct: <code>edd_device_params</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct edd_device_params {
    __u16 length;
    __u16 info_flags;
    __u32 num_default_cylinders;
    __u32 num_default_heads;
    __u32 sectors_per_track;
    __u64 number_of_sectors;
    __u16 bytes_per_sector;
    __u32 dpte_ptr;
    __u16 key;
    __u8 device_path_info_length;
    __u8 reserved2;
    __u16 reserved3;
    __u8[4] host_bus_type;
    __u8[8] interface_type;
    union (anon) interface_path;
    union (anon) device_path;
    __u8 reserved4;
    __u8 checksum;
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
