# Function: <code>proc_timens_set_offset</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int proc_timens_set_offset(struct file * file, struct task_struct * p, struct proc_timens_offset * offsets, int noffsets)
```

```json
{
  "name": "proc_timens_set_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580263344,
      "name": "proc_timens_set_offset",
      "external": true,
      "loc": "kernel/time/namespace.c:373",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:timens_offsets_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580263344,
      "name": "proc_timens_set_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 595
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
int proc_timens_set_offset(struct file * file, struct task_struct * p, struct proc_timens_offset * offsets, int noffsets)
```

```json
{
  "name": "proc_timens_set_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580247040,
      "name": "proc_timens_set_offset",
      "external": true,
      "loc": "kernel/time/namespace.c:362",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:timens_offsets_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580247040,
      "name": "proc_timens_set_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
int proc_timens_set_offset(struct file * file, struct task_struct * p, struct proc_timens_offset * offsets, int noffsets)
```

```json
{
  "name": "proc_timens_set_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580252160,
      "name": "proc_timens_set_offset",
      "external": true,
      "loc": "kernel/time/namespace.c:362",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:timens_offsets_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252160,
      "name": "proc_timens_set_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 606
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
int proc_timens_set_offset(struct file * file, struct task_struct * p, struct proc_timens_offset * offsets, int noffsets)
```

```json
{
  "name": "proc_timens_set_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_timens_set_offset",
      "external": true,
      "loc": "kernel/time/namespace.c:362",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:timens_offsets_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592157945,
      "name": "proc_timens_set_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580403312,
      "name": "proc_timens_set_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
int proc_timens_set_offset(struct file * file, struct task_struct * p, struct proc_timens_offset * offsets, int noffsets)
```

```json
{
  "name": "proc_timens_set_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_timens_set_offset",
      "external": true,
      "loc": "kernel/time/namespace.c:362",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:timens_offsets_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593932924,
      "name": "proc_timens_set_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071580622608,
      "name": "proc_timens_set_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 819
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
int proc_timens_set_offset(struct file * file, struct task_struct * p, struct proc_timens_offset * offsets, int noffsets)
```

```json
{
  "name": "proc_timens_set_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_timens_set_offset",
      "external": true,
      "loc": "kernel/time/namespace.c:380",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:timens_offsets_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595999036,
      "name": "proc_timens_set_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071580888384,
      "name": "proc_timens_set_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 819
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
int proc_timens_set_offset(struct file * file, struct task_struct * p, struct proc_timens_offset * offsets, int noffsets)
```

```json
{
  "name": "proc_timens_set_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_timens_set_offset",
      "external": true,
      "loc": "kernel/time/namespace.c:380",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:timens_offsets_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596517166,
      "name": "proc_timens_set_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071580972224,
      "name": "proc_timens_set_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
int proc_timens_set_offset(struct file * file, struct task_struct * p, struct proc_timens_offset * offsets, int noffsets)
```

```json
{
  "name": "proc_timens_set_offset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_timens_set_offset",
      "external": true,
      "loc": "kernel/time/namespace.c:380",
      "file": "kernel/time/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:timens_offsets_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597417118,
      "name": "proc_timens_set_offset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071581066960,
      "name": "proc_timens_set_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int proc_timens_set_offset(struct file * file, struct task_struct * p, struct proc_timens_offset * offsets, int noffsets)
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
