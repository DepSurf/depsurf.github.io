# Function: <code>printk_sprint</code>

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
u16 printk_sprint(char * text, u16 size, int facility, enum log_flags * lflags, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_sprint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992160,
      "name": "printk_sprint",
      "external": false,
      "loc": "kernel/printk/printk.c:1931",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992160,
      "name": "printk_sprint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
u16 printk_sprint(char * text, u16 size, int facility, enum log_flags * lflags, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_sprint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579993904,
      "name": "printk_sprint",
      "external": false,
      "loc": "kernel/printk/printk.c:2007",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993904,
      "name": "printk_sprint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
u16 printk_sprint(char * text, u16 size, int facility, enum printk_info_flags * flags, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_sprint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580136688,
      "name": "printk_sprint",
      "external": false,
      "loc": "kernel/printk/printk.c:2069",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580136688,
      "name": "printk_sprint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
u16 printk_sprint(char * text, u16 size, int facility, enum printk_info_flags * flags, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_sprint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580280192,
      "name": "printk_sprint",
      "external": false,
      "loc": "kernel/printk/printk.c:2086",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580280192,
      "name": "printk_sprint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
u16 printk_sprint(char * text, u16 size, int facility, enum printk_info_flags * flags, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_sprint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580488880,
      "name": "printk_sprint",
      "external": false,
      "loc": "kernel/printk/printk.c:2174",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580488880,
      "name": "printk_sprint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
u16 printk_sprint(char * text, u16 size, int facility, enum printk_info_flags * flags, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_sprint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580560816,
      "name": "printk_sprint",
      "external": false,
      "loc": "kernel/printk/printk.c:2122",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580560816,
      "name": "printk_sprint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
u16 printk_sprint(char * text, u16 size, int facility, enum printk_info_flags * flags, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_sprint",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580617840,
      "name": "printk_sprint",
      "external": false,
      "loc": "kernel/printk/printk.c:2118",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580617840,
      "name": "printk_sprint",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
u16 printk_sprint(char * text, u16 size, int facility, enum log_flags * lflags, const char * fmt, struct __va_list_tag * args)
```
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
<b>Param added. </b>
<code>enum printk_info_flags * flags</code>
</li>
<li>
<b>Param removed. </b>
<code>enum log_flags * lflags</code>
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
