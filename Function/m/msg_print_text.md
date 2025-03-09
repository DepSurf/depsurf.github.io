# Function: <code>msg_print_text</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
size_t msg_print_text(const struct printk_log * msg, enum log_flags prev, bool syslog, char * buf, size_t size)
```

```json
{
  "name": "msg_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579727312,
      "name": "msg_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1079",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579727312,
      "name": "msg_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
size_t msg_print_text(const struct printk_log * msg, enum log_flags prev, bool syslog, char * buf, size_t size)
```

```json
{
  "name": "msg_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579747696,
      "name": "msg_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1216",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579747696,
      "name": "msg_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
size_t msg_print_text(const struct printk_log * msg, bool syslog, char * buf, size_t size)
```

```json
{
  "name": "msg_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579772640,
      "name": "msg_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1197",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579772640,
      "name": "msg_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
size_t msg_print_text(const struct printk_log * msg, bool syslog, char * buf, size_t size)
```

```json
{
  "name": "msg_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579769200,
      "name": "msg_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1247",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579769200,
      "name": "msg_print_text",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
size_t msg_print_text(const struct printk_log * msg, bool syslog, char * buf, size_t size)
```

```json
{
  "name": "msg_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802320,
      "name": "msg_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1246",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802320,
      "name": "msg_print_text",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
size_t msg_print_text(const struct printk_log * msg, bool syslog, char * buf, size_t size)
```

```json
{
  "name": "msg_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579835808,
      "name": "msg_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1250",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835808,
      "name": "msg_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
size_t msg_print_text(const struct printk_log * msg, bool syslog, bool time, char * buf, size_t size)
```

```json
{
  "name": "msg_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579882144,
      "name": "msg_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1255",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock",
        "kernel/printk/printk.c:console_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882144,
      "name": "msg_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
size_t msg_print_text(const struct printk_log * msg, bool syslog, bool time, char * buf, size_t size)
```

```json
{
  "name": "msg_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579916704,
      "name": "msg_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1299",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock",
        "kernel/printk/printk.c:console_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916704,
      "name": "msg_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
size_t msg_print_text(const struct printk_log * msg, bool syslog, bool time, char * buf, size_t size)
```

```json
{
  "name": "msg_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579966752,
      "name": "msg_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1309",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock",
        "kernel/printk/printk.c:console_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579966752,
      "name": "msg_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
size_t msg_print_text(const struct printk_log * msg, bool syslog, bool time, char * buf, size_t size)
```

```json
{
  "name": "msg_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580013584,
      "name": "msg_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1337",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013584,
      "name": "msg_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
size_t msg_print_text(const struct printk_log * msg, bool syslog, bool time, char * buf, size_t size)
```

```json
{
  "name": "msg_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491147456,
      "name": "msg_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1309",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491147456,
      "name": "msg_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
size_t msg_print_text(const struct printk_log * msg, bool syslog, bool time, char * buf, size_t size)
```

```json
{
  "name": "msg_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225181084,
      "name": "msg_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1309",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225181084,
      "name": "msg_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 508
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
size_t msg_print_text(const struct printk_log * msg, bool syslog, bool time, char * buf, size_t size)
```

```json
{
  "name": "msg_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284044112,
      "name": "msg_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1309",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock",
        "kernel/printk/printk.c:console_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284044112,
      "name": "msg_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
size_t msg_print_text(const struct printk_log * msg, bool syslog, bool time, char * buf, size_t size)
```

```json
{
  "name": "msg_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271705240,
      "name": "msg_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1309",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock",
        "kernel/printk/printk.c:console_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271705240,
      "name": "msg_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
    }
  ]
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
size_t msg_print_text(const struct printk_log * msg, bool syslog, bool time, char * buf, size_t size)
```

```json
{
  "name": "msg_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579935488,
      "name": "msg_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1309",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock",
        "kernel/printk/printk.c:console_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579935488,
      "name": "msg_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
size_t msg_print_text(const struct printk_log * msg, bool syslog, bool time, char * buf, size_t size)
```

```json
{
  "name": "msg_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579873760,
      "name": "msg_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1309",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock",
        "kernel/printk/printk.c:console_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873760,
      "name": "msg_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
size_t msg_print_text(const struct printk_log * msg, bool syslog, bool time, char * buf, size_t size)
```

```json
{
  "name": "msg_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579927024,
      "name": "msg_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1309",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock",
        "kernel/printk/printk.c:console_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579927024,
      "name": "msg_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
size_t msg_print_text(const struct printk_log * msg, bool syslog, bool time, char * buf, size_t size)
```

```json
{
  "name": "msg_print_text",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579973008,
      "name": "msg_print_text",
      "external": false,
      "loc": "kernel/printk/printk.c:1309",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973008,
      "name": "msg_print_text",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
    }
  ]
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum log_flags prev</code>
</li>
<li>
<b>Param reordered. </b>
<code>msg, prev, syslog, buf, size</code> ➡️ <code>msg, syslog, buf, size</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool time</code>
</li>
<li>
<b>Param reordered. </b>
<code>msg, syslog, buf, size</code> ➡️ <code>msg, syslog, time, buf, size</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
size_t msg_print_text(const struct printk_log * msg, bool syslog, bool time, char * buf, size_t size)
```
</details>
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
