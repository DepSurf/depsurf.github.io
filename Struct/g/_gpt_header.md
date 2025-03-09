# Struct: <code>_gpt_header</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
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
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
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
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct _gpt_header {
    __le64 signature;
    __le32 revision;
    __le32 header_size;
    __le32 header_crc32;
    __le32 reserved1;
    __le64 my_lba;
    __le64 alternate_lba;
    __le64 first_usable_lba;
    __le64 last_usable_lba;
    efi_guid_t disk_guid;
    __le64 partition_entry_lba;
    __le32 num_partition_entries;
    __le32 sizeof_partition_entry;
    __le32 partition_entry_array_crc32;
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
