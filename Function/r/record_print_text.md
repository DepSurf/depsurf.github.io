# Function: <code>record_print_text</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
size_t record_print_text(struct printk_record * r, bool syslog, bool time)
```

```json
{
  "name": "record_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "record_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1306",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991808,
      "name": "record_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
    },
    {
      "addr": 18446744071591301365,
      "name": "record_print_text.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
size_t record_print_text(struct printk_record * r, bool syslog, bool time)
```

```json
{
  "name": "record_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "record_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1322",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993552,
      "name": "record_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
    },
    {
      "addr": 18446744071591244150,
      "name": "record_print_text.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
size_t record_print_text(struct printk_record * r, bool syslog, bool time)
```

```json
{
  "name": "record_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "record_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1316",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580125520,
      "name": "record_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
    },
    {
      "addr": 18446744071592132546,
      "name": "record_print_text.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
size_t record_print_text(struct printk_record * r, bool syslog, bool time)
```

```json
{
  "name": "record_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "record_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1332",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580267376,
      "name": "record_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    },
    {
      "addr": 18446744071593903264,
      "name": "record_print_text.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
size_t record_print_text(struct printk_record * r, bool syslog, bool time)
```

```json
{
  "name": "record_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580474960,
      "name": "record_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1413",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580474960,
      "name": "record_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
size_t record_print_text(struct printk_record * r, bool syslog, bool time)
```

```json
{
  "name": "record_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580546992,
      "name": "record_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1382",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:printk_get_next_message",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546992,
      "name": "record_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
size_t record_print_text(struct printk_record * r, bool syslog, bool time)
```

```json
{
  "name": "record_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580608480,
      "name": "record_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1379",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:printk_get_next_message",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580608480,
      "name": "record_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
size_t record_print_text(struct printk_record * r, bool syslog, bool time)
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
