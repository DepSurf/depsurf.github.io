# Struct: <code>ftrace_iterator</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    int hidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    int hidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    int hidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
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
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
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
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct ftrace_iterator {
    loff_t pos;
    loff_t func_pos;
    loff_t mod_pos;
    struct ftrace_page * pg;
    struct dyn_ftrace * func;
    struct ftrace_func_probe * probe;
    struct ftrace_func_entry * probe_entry;
    struct trace_parser parser;
    struct ftrace_hash * hash;
    struct ftrace_ops * ops;
    struct trace_array * tr;
    struct list_head * mod_list;
    int pidx;
    int idx;
    unsigned int flags;
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
<code>loff_t mod_pos</code>
</li>
<li>
<b>Field added. </b>
<code>struct ftrace_func_entry * probe_entry</code>
</li>
<li>
<b>Field added. </b>
<code>struct trace_array * tr</code>
</li>
<li>
<b>Field added. </b>
<code>struct list_head * mod_list</code>
</li>
<li>
<b>Field added. </b>
<code>int pidx</code>
</li>
<li>
<b>Field removed. </b>
<code>int hidx</code>
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
