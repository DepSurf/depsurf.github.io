# Struct: <code>_kdbtab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
    struct list_head list_node;
    bool is_dynamic;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * name;
    kdb_func_t func;
    char * usage;
    char * help;
    short int minlen;
    kdb_cmdflags_t flags;
    struct list_head list_node;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * name;
    kdb_func_t func;
    char * usage;
    char * help;
    short int minlen;
    kdb_cmdflags_t flags;
    struct list_head list_node;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * name;
    kdb_func_t func;
    char * usage;
    char * help;
    short int minlen;
    kdb_cmdflags_t flags;
    struct list_head list_node;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * name;
    kdb_func_t func;
    char * usage;
    char * help;
    short int minlen;
    kdb_cmdflags_t flags;
    struct list_head list_node;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * name;
    kdb_func_t func;
    char * usage;
    char * help;
    short int minlen;
    kdb_cmdflags_t flags;
    struct list_head list_node;
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
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
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
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct list_head list_node</code>
</li>
<li>
<b>Field added. </b>
<code>bool is_dynamic</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>char * name</code>
</li>
<li>
<b>Field added. </b>
<code>kdb_func_t func</code>
</li>
<li>
<b>Field added. </b>
<code>char * usage</code>
</li>
<li>
<b>Field added. </b>
<code>char * help</code>
</li>
<li>
<b>Field added. </b>
<code>short int minlen</code>
</li>
<li>
<b>Field added. </b>
<code>kdb_cmdflags_t flags</code>
</li>
<li>
<b>Field removed. </b>
<code>char * cmd_name</code>
</li>
<li>
<b>Field removed. </b>
<code>kdb_func_t cmd_func</code>
</li>
<li>
<b>Field removed. </b>
<code>char * cmd_usage</code>
</li>
<li>
<b>Field removed. </b>
<code>char * cmd_help</code>
</li>
<li>
<b>Field removed. </b>
<code>short int cmd_minlen</code>
</li>
<li>
<b>Field removed. </b>
<code>kdb_cmdflags_t cmd_flags</code>
</li>
<li>
<b>Field removed. </b>
<code>bool is_dynamic</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct _kdbtab {
    char * cmd_name;
    kdb_func_t cmd_func;
    char * cmd_usage;
    char * cmd_help;
    short int cmd_minlen;
    kdb_cmdflags_t cmd_flags;
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
