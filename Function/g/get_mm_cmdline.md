# Function: <code>get_mm_cmdline</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582114474,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:208",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582207594,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:212",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582366519,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:253",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582465927,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:253",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t get_mm_cmdline(struct mm_struct * mm, char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:255",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_cmdline_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582764768,
      "name": "get_mm_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
    },
    {
      "addr": 18446744071582777477,
      "name": "get_mm_cmdline.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t get_mm_cmdline(struct mm_struct * mm, char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:255",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_cmdline_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582837552,
      "name": "get_mm_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
    },
    {
      "addr": 18446744071591345341,
      "name": "get_mm_cmdline.cold",
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
ssize_t get_mm_cmdline(struct mm_struct * mm, char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:254",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_cmdline_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582868368,
      "name": "get_mm_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
    },
    {
      "addr": 18446744071591288012,
      "name": "get_mm_cmdline.cold",
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
ssize_t get_mm_cmdline(struct mm_struct * mm, char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:256",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_cmdline_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583202400,
      "name": "get_mm_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
    },
    {
      "addr": 18446744071592247502,
      "name": "get_mm_cmdline.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t get_mm_cmdline(struct mm_struct * mm, char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583687232,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:255",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_cmdline_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583687232,
      "name": "get_mm_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
ssize_t get_mm_cmdline(struct mm_struct * mm, char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584296736,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:256",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_cmdline_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584296736,
      "name": "get_mm_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
ssize_t get_mm_cmdline(struct mm_struct * mm, char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584526608,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:257",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_cmdline_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584526608,
      "name": "get_mm_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
ssize_t get_mm_cmdline(struct mm_struct * mm, char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584758512,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:257",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:proc_pid_cmdline_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584758512,
      "name": "get_mm_cmdline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494087244,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:253",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227536108,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:253",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287749776,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:253",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:proc_pid_cmdline_read"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273575612,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:253",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582434663,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:253",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582371831,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:253",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582425143,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:253",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_mm_cmdline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582505223,
      "name": "get_mm_cmdline",
      "external": false,
      "loc": "fs/proc/base.c:253",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
ssize_t get_mm_cmdline(struct mm_struct * mm, char * buf, size_t count, loff_t * ppos)
```
</details>
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
