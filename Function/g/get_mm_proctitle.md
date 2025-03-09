# Function: <code>get_mm_proctitle</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_mm_proctitle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582367086,
      "name": "get_mm_proctitle",
      "external": false,
      "loc": "fs/proc/base.c:216",
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
  "name": "get_mm_proctitle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582466494,
      "name": "get_mm_proctitle",
      "external": false,
      "loc": "fs/proc/base.c:216",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_mm_proctitle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582765257,
      "name": "get_mm_proctitle",
      "external": false,
      "loc": "fs/proc/base.c:218",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:get_mm_cmdline"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_mm_proctitle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582838041,
      "name": "get_mm_proctitle",
      "external": false,
      "loc": "fs/proc/base.c:218",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:get_mm_cmdline"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_mm_proctitle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582868862,
      "name": "get_mm_proctitle",
      "external": false,
      "loc": "fs/proc/base.c:217",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:get_mm_cmdline"
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
  "name": "get_mm_proctitle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583202894,
      "name": "get_mm_proctitle",
      "external": false,
      "loc": "fs/proc/base.c:219",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:get_mm_cmdline"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t get_mm_proctitle(struct mm_struct * mm, char * buf, size_t count, long unsigned int pos, long unsigned int arg_start)
```

```json
{
  "name": "get_mm_proctitle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_mm_proctitle",
      "external": false,
      "loc": "fs/proc/base.c:218",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:get_mm_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583686880,
      "name": "get_mm_proctitle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    },
    {
      "addr": 18446744071594028150,
      "name": "get_mm_proctitle.cold",
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
ssize_t get_mm_proctitle(struct mm_struct * mm, char * buf, size_t count, long unsigned int pos, long unsigned int arg_start)
```

```json
{
  "name": "get_mm_proctitle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584296368,
      "name": "get_mm_proctitle",
      "external": false,
      "loc": "fs/proc/base.c:219",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:get_mm_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584296368,
      "name": "get_mm_proctitle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
ssize_t get_mm_proctitle(struct mm_struct * mm, char * buf, size_t count, long unsigned int pos, long unsigned int arg_start)
```

```json
{
  "name": "get_mm_proctitle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584526240,
      "name": "get_mm_proctitle",
      "external": false,
      "loc": "fs/proc/base.c:220",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:get_mm_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584526240,
      "name": "get_mm_proctitle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
ssize_t get_mm_proctitle(struct mm_struct * mm, char * buf, size_t count, long unsigned int pos, long unsigned int arg_start)
```

```json
{
  "name": "get_mm_proctitle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584758144,
      "name": "get_mm_proctitle",
      "external": false,
      "loc": "fs/proc/base.c:220",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:get_mm_cmdline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584758144,
      "name": "get_mm_proctitle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
  "name": "get_mm_proctitle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494087832,
      "name": "get_mm_proctitle",
      "external": false,
      "loc": "fs/proc/base.c:216",
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
  "name": "get_mm_proctitle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227536656,
      "name": "get_mm_proctitle",
      "external": false,
      "loc": "fs/proc/base.c:216",
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
  "name": "get_mm_proctitle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287750540,
      "name": "get_mm_proctitle",
      "external": false,
      "loc": "fs/proc/base.c:216",
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
  "name": "get_mm_proctitle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273576014,
      "name": "get_mm_proctitle",
      "external": false,
      "loc": "fs/proc/base.c:216",
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
  "name": "get_mm_proctitle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582435230,
      "name": "get_mm_proctitle",
      "external": false,
      "loc": "fs/proc/base.c:216",
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
  "name": "get_mm_proctitle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582372398,
      "name": "get_mm_proctitle",
      "external": false,
      "loc": "fs/proc/base.c:216",
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
  "name": "get_mm_proctitle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582425710,
      "name": "get_mm_proctitle",
      "external": false,
      "loc": "fs/proc/base.c:216",
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
  "name": "get_mm_proctitle",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582505796,
      "name": "get_mm_proctitle",
      "external": false,
      "loc": "fs/proc/base.c:216",
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
ssize_t get_mm_proctitle(struct mm_struct * mm, char * buf, size_t count, long unsigned int pos, long unsigned int arg_start)
```
</details>
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
