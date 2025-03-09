# Struct: <code>hist_field</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int size;
    unsigned int offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int size;
    unsigned int offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int size;
    unsigned int offset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    struct hist_field *[2] operands;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_idx;
    unsigned int var_ref_idx;
    bool read_once;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int ref;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int ref;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int ref;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
    unsigned int var_str_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int ref;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
    unsigned int var_str_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int ref;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    long unsigned int buckets;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
    unsigned int var_str_idx;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int ref;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    long unsigned int buckets;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
    unsigned int var_str_idx;
    u64 constant;
    u64 div_multiplier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    long unsigned int buckets;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    enum hist_field_fn fn_num;
    unsigned int ref;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
    unsigned int var_str_idx;
    u64 constant;
    u64 div_multiplier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    long unsigned int buckets;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    enum hist_field_fn fn_num;
    unsigned int ref;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
    unsigned int var_str_idx;
    u64 constant;
    u64 div_multiplier;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    long unsigned int buckets;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    enum hist_field_fn fn_num;
    unsigned int ref;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
    unsigned int var_str_idx;
    u64 constant;
    u64 div_multiplier;
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
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int ref;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
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
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int ref;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
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
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int ref;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int ref;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int ref;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int ref;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int size;
    unsigned int offset;
}
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int is_signed</code>
</li>
<li>
<b>Field added. </b>
<code>struct hist_field *[2] operands</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const char * type</code>
</li>
<li>
<b>Field added. </b>
<code>struct hist_trigger_data * hist_data</code>
</li>
<li>
<b>Field added. </b>
<code>struct hist_var var</code>
</li>
<li>
<b>Field added. </b>
<code>enum field_op_id operator</code>
</li>
<li>
<b>Field added. </b>
<code>char * system</code>
</li>
<li>
<b>Field added. </b>
<code>char * event_name</code>
</li>
<li>
<b>Field added. </b>
<code>char * name</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int var_idx</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int var_ref_idx</code>
</li>
<li>
<b>Field added. </b>
<code>bool read_once</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>unsigned int var_idx</code>
</li>
</ul>
</details>
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
<code>unsigned int ref</code>
</li>
</ul>
</details>
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
<code>unsigned int var_str_idx</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int buckets</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u64 constant</code>
</li>
<li>
<b>Field added. </b>
<code>u64 div_multiplier</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>enum hist_field_fn fn_num</code>
</li>
<li>
<b>Field removed. </b>
<code>hist_field_fn_t fn</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int ref;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
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
struct hist_field {
    struct ftrace_event_field * field;
    long unsigned int flags;
    hist_field_fn_t fn;
    unsigned int ref;
    unsigned int size;
    unsigned int offset;
    unsigned int is_signed;
    const char * type;
    struct hist_field *[2] operands;
    struct hist_trigger_data * hist_data;
    struct hist_var var;
    enum field_op_id operator;
    char * system;
    char * event_name;
    char * name;
    unsigned int var_ref_idx;
    bool read_once;
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
