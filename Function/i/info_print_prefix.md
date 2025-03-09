# Function: <code>info_print_prefix</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t info_print_prefix(const struct printk_info * info, bool syslog, bool time, char * buf)
```

```json
{
  "name": "info_print_prefix",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579991600,
      "name": "info_print_prefix",
      "external": false,
      "loc": "kernel/printk/printk.c:1268",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:record_print_text"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991600,
      "name": "info_print_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
size_t info_print_prefix(const struct printk_info * info, bool syslog, bool time, char * buf)
```

```json
{
  "name": "info_print_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993344,
      "name": "info_print_prefix",
      "external": false,
      "loc": "kernel/printk/printk.c:1284",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:record_print_text"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993344,
      "name": "info_print_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
size_t info_print_prefix(const struct printk_info * info, bool syslog, bool time, char * buf)
```

```json
{
  "name": "info_print_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580125312,
      "name": "info_print_prefix",
      "external": false,
      "loc": "kernel/printk/printk.c:1278",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:record_print_text"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580125312,
      "name": "info_print_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
size_t info_print_prefix(const struct printk_info * info, bool syslog, bool time, char * buf)
```

```json
{
  "name": "info_print_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580267136,
      "name": "info_print_prefix",
      "external": false,
      "loc": "kernel/printk/printk.c:1294",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:record_print_text"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267136,
      "name": "info_print_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
size_t info_print_prefix(const struct printk_info * info, bool syslog, bool time, char * buf)
```

```json
{
  "name": "info_print_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580472960,
      "name": "info_print_prefix",
      "external": false,
      "loc": "kernel/printk/printk.c:1375",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:record_print_text"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580472960,
      "name": "info_print_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
size_t info_print_prefix(const struct printk_info * info, bool syslog, bool time, char * buf)
```

```json
{
  "name": "info_print_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580544544,
      "name": "info_print_prefix",
      "external": false,
      "loc": "kernel/printk/printk.c:1344",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:record_print_text"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580544544,
      "name": "info_print_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
size_t info_print_prefix(const struct printk_info * info, bool syslog, bool time, char * buf)
```

```json
{
  "name": "info_print_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580606224,
      "name": "info_print_prefix",
      "external": false,
      "loc": "kernel/printk/printk.c:1341",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:record_print_text"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580606224,
      "name": "info_print_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    }
  ]
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
size_t info_print_prefix(const struct printk_info * info, bool syslog, bool time, char * buf)
```
</details>
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
