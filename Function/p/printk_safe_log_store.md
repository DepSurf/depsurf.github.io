# Function: <code>printk_safe_log_store</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_safe_log_store",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579782608,
      "name": "printk_safe_log_store",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:83",
      "file": "kernel/printk/printk_safe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782608,
      "name": "printk_safe_log_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_safe_log_store",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579815984,
      "name": "printk_safe_log_store",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:80",
      "file": "kernel/printk/printk_safe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815984,
      "name": "printk_safe_log_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_safe_log_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579848992,
      "name": "printk_safe_log_store",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:80",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848992,
      "name": "printk_safe_log_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_safe_log_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579896016,
      "name": "printk_safe_log_store",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:80",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579896016,
      "name": "printk_safe_log_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_safe_log_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579930816,
      "name": "printk_safe_log_store",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:68",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579930816,
      "name": "printk_safe_log_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_safe_log_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579980960,
      "name": "printk_safe_log_store",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:68",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980960,
      "name": "printk_safe_log_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_safe_log_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580028832,
      "name": "printk_safe_log_store",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:69",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028832,
      "name": "printk_safe_log_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_safe_log_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580007424,
      "name": "printk_safe_log_store",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:71",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007424,
      "name": "printk_safe_log_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_safe_log_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008560,
      "name": "printk_safe_log_store",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:71",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:vprintk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008560,
      "name": "printk_safe_log_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
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
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, va_list args)
```

```json
{
  "name": "printk_safe_log_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491166720,
      "name": "printk_safe_log_store",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:68",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491166720,
      "name": "printk_safe_log_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, va_list args)
```

```json
{
  "name": "printk_safe_log_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225192336,
      "name": "printk_safe_log_store",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:68",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225192336,
      "name": "printk_safe_log_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, va_list args)
```

```json
{
  "name": "printk_safe_log_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284064544,
      "name": "printk_safe_log_store",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:68",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284064544,
      "name": "printk_safe_log_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, va_list args)
```

```json
{
  "name": "printk_safe_log_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271719276,
      "name": "printk_safe_log_store",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:68",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271719276,
      "name": "printk_safe_log_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_safe_log_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579949696,
      "name": "printk_safe_log_store",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:68",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949696,
      "name": "printk_safe_log_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_safe_log_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579887584,
      "name": "printk_safe_log_store",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:68",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887584,
      "name": "printk_safe_log_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_safe_log_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579941232,
      "name": "printk_safe_log_store",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:68",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579941232,
      "name": "printk_safe_log_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "printk_safe_log_store",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579987584,
      "name": "printk_safe_log_store",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:68",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:vprintk_func",
        "kernel/printk/printk_safe.c:vprintk_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987584,
      "name": "printk_safe_log_store",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, struct __va_list_tag * args)
```
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int printk_safe_log_store(struct printk_safe_seq_buf * s, const char * fmt, struct __va_list_tag * args)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
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
