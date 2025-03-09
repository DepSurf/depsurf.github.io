# Function: <code>prb_read_valid_info</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool prb_read_valid_info(struct printk_ringbuffer * rb, u64 seq, struct printk_info * info, unsigned int * line_count)
```

```json
{
  "name": "prb_read_valid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012864,
      "name": "prb_read_valid_info",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1956",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line_nolock",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:devkmsg_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012864,
      "name": "prb_read_valid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool prb_read_valid_info(struct printk_ringbuffer * rb, u64 seq, struct printk_info * info, unsigned int * line_count)
```

```json
{
  "name": "prb_read_valid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580013776,
      "name": "prb_read_valid_info",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1956",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:devkmsg_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580013776,
      "name": "prb_read_valid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool prb_read_valid_info(struct printk_ringbuffer * rb, u64 seq, struct printk_info * info, unsigned int * line_count)
```

```json
{
  "name": "prb_read_valid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580145712,
      "name": "prb_read_valid_info",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1956",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:devkmsg_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145712,
      "name": "prb_read_valid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool prb_read_valid_info(struct printk_ringbuffer * rb, u64 seq, struct printk_info * info, unsigned int * line_count)
```

```json
{
  "name": "prb_read_valid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580289936,
      "name": "prb_read_valid_info",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1967",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:devkmsg_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580289936,
      "name": "prb_read_valid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
bool prb_read_valid_info(struct printk_ringbuffer * rb, u64 seq, struct printk_info * info, unsigned int * line_count)
```

```json
{
  "name": "prb_read_valid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580500224,
      "name": "prb_read_valid_info",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1967",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:devkmsg_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580500224,
      "name": "prb_read_valid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
bool prb_read_valid_info(struct printk_ringbuffer * rb, u64 seq, struct printk_info * info, unsigned int * line_count)
```

```json
{
  "name": "prb_read_valid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580572000,
      "name": "prb_read_valid_info",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1967",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:devkmsg_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580572000,
      "name": "prb_read_valid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
bool prb_read_valid_info(struct printk_ringbuffer * rb, u64 seq, struct printk_info * info, unsigned int * line_count)
```

```json
{
  "name": "prb_read_valid_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580636240,
      "name": "prb_read_valid_info",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1967",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:do_syslog",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:find_first_fitting_seq",
        "kernel/printk/printk.c:devkmsg_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580636240,
      "name": "prb_read_valid_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
bool prb_read_valid_info(struct printk_ringbuffer * rb, u64 seq, struct printk_info * info, unsigned int * line_count)
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
