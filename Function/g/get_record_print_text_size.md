# Function: <code>get_record_print_text_size</code>

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
size_t get_record_print_text_size(struct printk_info * info, unsigned int line_count, bool syslog, bool time)
```

```json
{
  "name": "get_record_print_text_size",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579999674,
      "name": "get_record_print_text_size",
      "external": false,
      "loc": "kernel/printk/printk.c:1407",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all"
      ],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993760,
      "name": "get_record_print_text_size",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_record_print_text_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579997736,
      "name": "get_record_print_text_size",
      "external": false,
      "loc": "kernel/printk/printk.c:1423",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:find_first_fitting_seq"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_record_print_text_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580127340,
      "name": "get_record_print_text_size",
      "external": false,
      "loc": "kernel/printk/printk.c:1417",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:find_first_fitting_seq"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_record_print_text_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580273212,
      "name": "get_record_print_text_size",
      "external": false,
      "loc": "kernel/printk/printk.c:1433",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:find_first_fitting_seq"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_record_print_text_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580480828,
      "name": "get_record_print_text_size",
      "external": false,
      "loc": "kernel/printk/printk.c:1514",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:find_first_fitting_seq"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_record_print_text_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580552668,
      "name": "get_record_print_text_size",
      "external": false,
      "loc": "kernel/printk/printk.c:1483",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:find_first_fitting_seq"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_record_print_text_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580614348,
      "name": "get_record_print_text_size",
      "external": false,
      "loc": "kernel/printk/printk.c:1480",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:find_first_fitting_seq"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
size_t get_record_print_text_size(struct printk_info * info, unsigned int line_count, bool syslog, bool time)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
size_t get_record_print_text_size(struct printk_info * info, unsigned int line_count, bool syslog, bool time)
```
</details>
</li>
</ul>
