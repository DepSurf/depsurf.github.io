# Function: <code>trace_check_vprintf</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void trace_check_vprintf(struct trace_iterator * iter, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "trace_check_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580679664,
      "name": "trace_check_vprintf",
      "external": true,
      "loc": "kernel/trace/trace.c:3720",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:trace_event_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580679664,
      "name": "trace_check_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1193
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
void trace_check_vprintf(struct trace_iterator * iter, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "trace_check_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_check_vprintf",
      "external": true,
      "loc": "kernel/trace/trace.c:3780",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:trace_event_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592170413,
      "name": "trace_check_vprintf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071580854160,
      "name": "trace_check_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1310
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
void trace_check_vprintf(struct trace_iterator * iter, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "trace_check_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_check_vprintf",
      "external": true,
      "loc": "kernel/trace/trace.c:3783",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:trace_event_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593944046,
      "name": "trace_check_vprintf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581083248,
      "name": "trace_check_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1580
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void trace_check_vprintf(struct trace_iterator * iter, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "trace_check_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_check_vprintf",
      "external": true,
      "loc": "kernel/trace/trace.c:3807",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:trace_event_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596004977,
      "name": "trace_check_vprintf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581390544,
      "name": "trace_check_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1576
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void trace_check_vprintf(struct trace_iterator * iter, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "trace_check_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_check_vprintf",
      "external": true,
      "loc": "kernel/trace/trace.c:3901",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:trace_event_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596523441,
      "name": "trace_check_vprintf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071581485248,
      "name": "trace_check_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1629
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void trace_check_vprintf(struct trace_iterator * iter, const char * fmt, struct __va_list_tag * ap)
```

```json
{
  "name": "trace_check_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_check_vprintf",
      "external": true,
      "loc": "kernel/trace/trace.c:3869",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_output.c:trace_event_printf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597424191,
      "name": "trace_check_vprintf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071581596096,
      "name": "trace_check_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1628
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void trace_check_vprintf(struct trace_iterator * iter, const char * fmt, struct __va_list_tag * ap)
```
</details>
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
