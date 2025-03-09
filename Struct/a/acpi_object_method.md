# Struct: <code>acpi_object_method</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    u8 thread_count;
    acpi_owner_id owner_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    u8 thread_count;
    acpi_owner_id owner_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    u8 thread_count;
    acpi_owner_id owner_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    u8 thread_count;
    acpi_owner_id owner_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    u8 thread_count;
    acpi_owner_id owner_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    u8 thread_count;
    acpi_owner_id owner_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    u8 thread_count;
    acpi_owner_id owner_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    u8 thread_count;
    acpi_owner_id owner_id;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    acpi_owner_id owner_id;
    u8 thread_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    acpi_owner_id owner_id;
    u8 thread_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    acpi_owner_id owner_id;
    u8 thread_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    acpi_owner_id owner_id;
    u8 thread_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    acpi_owner_id owner_id;
    u8 thread_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    acpi_owner_id owner_id;
    u8 thread_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    acpi_owner_id owner_id;
    u8 thread_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    acpi_owner_id owner_id;
    u8 thread_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    acpi_owner_id owner_id;
    u8 thread_count;
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
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    acpi_owner_id owner_id;
    u8 thread_count;
}
```
</details>
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
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    acpi_owner_id owner_id;
    u8 thread_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    acpi_owner_id owner_id;
    u8 thread_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    acpi_owner_id owner_id;
    u8 thread_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    acpi_owner_id owner_id;
    u8 thread_count;
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    acpi_owner_id owner_id;
    u8 thread_count;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    acpi_owner_id owner_id;
    u8 thread_count;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct acpi_object_method {
    union acpi_operand_object * next_object;
    u8 descriptor_type;
    u8 type;
    u16 reference_count;
    u8 flags;
    u8 info_flags;
    u8 param_count;
    u8 sync_level;
    union acpi_operand_object * mutex;
    union acpi_operand_object * node;
    u8 * aml_start;
    union (anon) dispatch;
    u32 aml_length;
    acpi_owner_id owner_id;
    u8 thread_count;
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
