# Struct: <code>nd_namespace_label</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    __le32 unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    __le32 unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    __le32 unused;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    u8 align;
    u8[3] reserved;
    guid_t type_guid;
    guid_t abstraction_guid;
    u8[88] reserved2;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    u8 align;
    u8[3] reserved;
    guid_t type_guid;
    guid_t abstraction_guid;
    u8[88] reserved2;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    u8 align;
    u8[3] reserved;
    guid_t type_guid;
    guid_t abstraction_guid;
    u8[88] reserved2;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    u8 align;
    u8[3] reserved;
    guid_t type_guid;
    guid_t abstraction_guid;
    u8[88] reserved2;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    u8 align;
    u8[3] reserved;
    guid_t type_guid;
    guid_t abstraction_guid;
    u8[88] reserved2;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    u8 align;
    u8[3] reserved;
    guid_t type_guid;
    guid_t abstraction_guid;
    u8[88] reserved2;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    u8 align;
    u8[3] reserved;
    guid_t type_guid;
    guid_t abstraction_guid;
    u8[88] reserved2;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    u8 align;
    u8[3] reserved;
    guid_t type_guid;
    guid_t abstraction_guid;
    u8[88] reserved2;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    u8 align;
    u8[3] reserved;
    guid_t type_guid;
    guid_t abstraction_guid;
    u8[88] reserved2;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    u8 align;
    u8[3] reserved;
    guid_t type_guid;
    guid_t abstraction_guid;
    u8[88] reserved2;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    struct nvdimm_cxl_label cxl;
    struct nvdimm_efi_label efi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    struct nvdimm_cxl_label cxl;
    struct nvdimm_efi_label efi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    struct nvdimm_cxl_label cxl;
    struct nvdimm_efi_label efi;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    struct nvdimm_cxl_label cxl;
    struct nvdimm_efi_label efi;
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
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    u8 align;
    u8[3] reserved;
    guid_t type_guid;
    guid_t abstraction_guid;
    u8[88] reserved2;
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
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    u8 align;
    u8[3] reserved;
    guid_t type_guid;
    guid_t abstraction_guid;
    u8[88] reserved2;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    u8 align;
    u8[3] reserved;
    guid_t type_guid;
    guid_t abstraction_guid;
    u8[88] reserved2;
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
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    u8 align;
    u8[3] reserved;
    guid_t type_guid;
    guid_t abstraction_guid;
    u8[88] reserved2;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    u8 align;
    u8[3] reserved;
    guid_t type_guid;
    guid_t abstraction_guid;
    u8[88] reserved2;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    u8 align;
    u8[3] reserved;
    guid_t type_guid;
    guid_t abstraction_guid;
    u8[88] reserved2;
    __le64 checksum;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    u8 align;
    u8[3] reserved;
    guid_t type_guid;
    guid_t abstraction_guid;
    u8[88] reserved2;
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 align</code>
</li>
<li>
<b>Field added. </b>
<code>u8[3] reserved</code>
</li>
<li>
<b>Field added. </b>
<code>guid_t type_guid</code>
</li>
<li>
<b>Field added. </b>
<code>guid_t abstraction_guid</code>
</li>
<li>
<b>Field added. </b>
<code>u8[88] reserved2</code>
</li>
<li>
<b>Field added. </b>
<code>__le64 checksum</code>
</li>
<li>
<b>Field removed. </b>
<code>__le32 unused</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct nvdimm_cxl_label cxl</code>
</li>
<li>
<b>Field added. </b>
<code>struct nvdimm_efi_label efi</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[16] uuid</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[64] name</code>
</li>
<li>
<b>Field removed. </b>
<code>__le32 flags</code>
</li>
<li>
<b>Field removed. </b>
<code>__le16 nlabel</code>
</li>
<li>
<b>Field removed. </b>
<code>__le16 position</code>
</li>
<li>
<b>Field removed. </b>
<code>__le64 isetcookie</code>
</li>
<li>
<b>Field removed. </b>
<code>__le64 lbasize</code>
</li>
<li>
<b>Field removed. </b>
<code>__le64 dpa</code>
</li>
<li>
<b>Field removed. </b>
<code>__le64 rawsize</code>
</li>
<li>
<b>Field removed. </b>
<code>__le32 slot</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 align</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[3] reserved</code>
</li>
<li>
<b>Field removed. </b>
<code>guid_t type_guid</code>
</li>
<li>
<b>Field removed. </b>
<code>guid_t abstraction_guid</code>
</li>
<li>
<b>Field removed. </b>
<code>u8[88] reserved2</code>
</li>
<li>
<b>Field removed. </b>
<code>__le64 checksum</code>
</li>
</ul>
</details>
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
struct nd_namespace_label {
    u8[16] uuid;
    u8[64] name;
    __le32 flags;
    __le16 nlabel;
    __le16 position;
    __le64 isetcookie;
    __le64 lbasize;
    __le64 dpa;
    __le64 rawsize;
    __le32 slot;
    u8 align;
    u8[3] reserved;
    guid_t type_guid;
    guid_t abstraction_guid;
    u8[88] reserved2;
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
