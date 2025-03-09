# Struct: <code>efi_dev_path</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct efi_dev_path {
    u8 type;
    u8 sub_type;
    u16 length;
    struct (anon) acpi;
    struct (anon) pci;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct efi_dev_path {
    u8 type;
    u8 sub_type;
    u16 length;
    struct (anon) acpi;
    struct (anon) pci;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct efi_dev_path {
    u8 type;
    u8 sub_type;
    u16 length;
    struct (anon) acpi;
    struct (anon) pci;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct efi_dev_path {
    u8 type;
    u8 sub_type;
    u16 length;
    struct (anon) acpi;
    struct (anon) pci;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct efi_dev_path {
    u8 type;
    u8 sub_type;
    u16 length;
    struct (anon) acpi;
    struct (anon) pci;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct efi_dev_path {
    u8 type;
    u8 sub_type;
    u16 length;
    struct (anon) acpi;
    struct (anon) pci;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct efi_dev_path {
    u8 type;
    u8 sub_type;
    u16 length;
    struct (anon) acpi;
    struct (anon) pci;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct efi_dev_path {
    struct efi_generic_dev_path header;
    struct efi_acpi_dev_path acpi;
    struct efi_pci_dev_path pci;
    struct efi_vendor_dev_path vendor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct efi_dev_path {
    struct efi_generic_dev_path header;
    struct efi_acpi_dev_path acpi;
    struct efi_pci_dev_path pci;
    struct efi_vendor_dev_path vendor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct efi_dev_path {
    struct efi_generic_dev_path header;
    struct efi_acpi_dev_path acpi;
    struct efi_pci_dev_path pci;
    struct efi_vendor_dev_path vendor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct efi_dev_path {
    struct efi_generic_dev_path header;
    struct efi_acpi_dev_path acpi;
    struct efi_pci_dev_path pci;
    struct efi_vendor_dev_path vendor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct efi_dev_path {
    struct efi_generic_dev_path header;
    struct efi_acpi_dev_path acpi;
    struct efi_pci_dev_path pci;
    struct efi_vendor_dev_path vendor;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct efi_dev_path {
    struct efi_generic_dev_path header;
    struct efi_acpi_dev_path acpi;
    struct efi_pci_dev_path pci;
    struct efi_vendor_dev_path vendor;
    struct efi_rel_offset_dev_path rel_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct efi_dev_path {
    struct efi_generic_dev_path header;
    struct efi_acpi_dev_path acpi;
    struct efi_pci_dev_path pci;
    struct efi_vendor_dev_path vendor;
    struct efi_rel_offset_dev_path rel_offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct efi_dev_path {
    struct efi_generic_dev_path header;
    struct efi_acpi_dev_path acpi;
    struct efi_pci_dev_path pci;
    struct efi_vendor_dev_path vendor;
    struct efi_rel_offset_dev_path rel_offset;
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
struct efi_dev_path {
    u8 type;
    u8 sub_type;
    u16 length;
    struct (anon) acpi;
    struct (anon) pci;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct efi_dev_path {
    u8 type;
    u8 sub_type;
    u16 length;
    struct (anon) acpi;
    struct (anon) pci;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct efi_dev_path {
    u8 type;
    u8 sub_type;
    u16 length;
    struct (anon) acpi;
    struct (anon) pci;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct efi_dev_path {
    u8 type;
    u8 sub_type;
    u16 length;
    struct (anon) acpi;
    struct (anon) pci;
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct efi_dev_path {
    u8 type;
    u8 sub_type;
    u16 length;
    struct (anon) acpi;
    struct (anon) pci;
}
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct efi_generic_dev_path header</code>
</li>
<li>
<b>Field added. </b>
<code>struct efi_vendor_dev_path vendor</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 type</code>
</li>
<li>
<b>Field removed. </b>
<code>u8 sub_type</code>
</li>
<li>
<b>Field removed. </b>
<code>u16 length</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct (anon) acpi</code> ➡️ <code>struct efi_acpi_dev_path acpi</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct (anon) pci</code> ➡️ <code>struct efi_pci_dev_path pci</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct efi_rel_offset_dev_path rel_offset</code>
</li>
</ul>
</details>
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
struct efi_dev_path {
    u8 type;
    u8 sub_type;
    u16 length;
    struct (anon) acpi;
    struct (anon) pci;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct efi_dev_path {
    u8 type;
    u8 sub_type;
    u16 length;
    struct (anon) acpi;
    struct (anon) pci;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct efi_dev_path {
    u8 type;
    u8 sub_type;
    u16 length;
    struct (anon) acpi;
    struct (anon) pci;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct efi_dev_path {
    u8 type;
    u8 sub_type;
    u16 length;
    struct (anon) acpi;
    struct (anon) pci;
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
