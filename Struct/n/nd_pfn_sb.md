# Struct: <code>nd_pfn_sb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    u8[4012] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    u8[4000] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    u8[4000] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    u8[4000] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    u8[4000] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    u8[4000] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    u8[4000] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    u8[4000] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    __le32 page_size;
    __le16 page_struct_size;
    u8[3994] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    __le32 page_size;
    __le16 page_struct_size;
    u8[3994] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    __le32 page_size;
    __le16 page_struct_size;
    u8[3994] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    __le32 page_size;
    __le16 page_struct_size;
    u8[3994] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    __le32 page_size;
    __le16 page_struct_size;
    u8[3994] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    __le32 page_size;
    __le16 page_struct_size;
    u8[3994] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    __le32 page_size;
    __le16 page_struct_size;
    u8[3994] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    __le32 page_size;
    __le16 page_struct_size;
    u8[3994] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    __le32 page_size;
    __le16 page_struct_size;
    u8[3994] padding;
    __le64 checksum;
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
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    __le32 page_size;
    __le16 page_struct_size;
    u8[3994] padding;
    __le64 checksum;
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
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    __le32 page_size;
    __le16 page_struct_size;
    u8[3994] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    __le32 page_size;
    __le16 page_struct_size;
    u8[3994] padding;
    __le64 checksum;
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
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    __le32 page_size;
    __le16 page_struct_size;
    u8[3994] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    __le32 page_size;
    __le16 page_struct_size;
    u8[3994] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    __le32 page_size;
    __le16 page_struct_size;
    u8[3994] padding;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    __le32 page_size;
    __le16 page_struct_size;
    u8[3994] padding;
    __le64 checksum;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__le32 start_pad</code>
</li>
<li>
<b>Field added. </b>
<code>__le32 end_trunc</code>
</li>
<li>
<b>Field added. </b>
<code>__le32 align</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8[4012] padding</code> ➡️ <code>u8[4000] padding</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>__le32 page_size</code>
</li>
<li>
<b>Field added. </b>
<code>__le16 page_struct_size</code>
</li>
<li>
<b>Field type changed. </b>
<code>u8[4000] padding</code> ➡️ <code>u8[3994] padding</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct nd_pfn_sb {
    u8[16] signature;
    u8[16] uuid;
    u8[16] parent_uuid;
    __le32 flags;
    __le16 version_major;
    __le16 version_minor;
    __le64 dataoff;
    __le64 npfns;
    __le32 mode;
    __le32 start_pad;
    __le32 end_trunc;
    __le32 align;
    __le32 page_size;
    __le16 page_struct_size;
    u8[3994] padding;
    __le64 checksum;
}
```
</details>
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
