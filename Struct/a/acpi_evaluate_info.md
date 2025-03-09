# Struct: <code>acpi_evaluate_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u8 pass_number;
    u8 return_object_type;
    u8 node_flags;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u8 pass_number;
    u8 return_object_type;
    u8 node_flags;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u8 pass_number;
    u8 return_object_type;
    u8 node_flags;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u8 pass_number;
    u8 return_object_type;
    u8 node_flags;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u8 pass_number;
    u8 return_object_type;
    u8 node_flags;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u8 pass_number;
    u8 return_object_type;
    u8 node_flags;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u8 pass_number;
    u8 return_object_type;
    u8 node_flags;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u8 pass_number;
    u8 return_object_type;
    u8 node_flags;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u16 node_flags;
    u8 pass_number;
    u8 return_object_type;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u16 node_flags;
    u8 pass_number;
    u8 return_object_type;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u16 node_flags;
    u8 pass_number;
    u8 return_object_type;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u16 node_flags;
    u8 pass_number;
    u8 return_object_type;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u16 node_flags;
    u8 pass_number;
    u8 return_object_type;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u16 node_flags;
    u8 pass_number;
    u8 return_object_type;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u16 node_flags;
    u8 pass_number;
    u8 return_object_type;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u16 node_flags;
    u8 pass_number;
    u8 return_object_type;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u16 node_flags;
    u8 pass_number;
    u8 return_object_type;
    u8 flags;
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
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u16 node_flags;
    u8 pass_number;
    u8 return_object_type;
    u8 flags;
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
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u16 node_flags;
    u8 pass_number;
    u8 return_object_type;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u16 node_flags;
    u8 pass_number;
    u8 return_object_type;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u16 node_flags;
    u8 pass_number;
    u8 return_object_type;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u16 node_flags;
    u8 pass_number;
    u8 return_object_type;
    u8 flags;
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
<b>Field type changed. </b>
<code>char * relative_pathname</code> ➡️ <code>const char * relative_pathname</code>
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
<b>Field type changed. </b>
<code>u8 node_flags</code> ➡️ <code>u16 node_flags</code>
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
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u16 node_flags;
    u8 pass_number;
    u8 return_object_type;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u16 node_flags;
    u8 pass_number;
    u8 return_object_type;
    u8 flags;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct acpi_evaluate_info {
    struct acpi_namespace_node * prefix_node;
    const char * relative_pathname;
    union acpi_operand_object * * parameters;
    struct acpi_namespace_node * node;
    union acpi_operand_object * obj_desc;
    char * full_pathname;
    const union acpi_predefined_info * predefined;
    union acpi_operand_object * return_object;
    union acpi_operand_object * parent_package;
    u32 return_flags;
    u32 return_btype;
    u16 param_count;
    u16 node_flags;
    u8 pass_number;
    u8 return_object_type;
    u8 flags;
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
