# Function: <code>do_proc_douintvec_w</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579424520,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:2306",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579451418,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:2296",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579466206,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:2301",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579499822,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:2349",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579517953,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:2435",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579544033,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:2437",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int do_proc_douintvec_w(unsigned int * tbl_data, struct ctl_table * table, void * buffer, size_t * lenp, loff_t * ppos, int (*)(long unsigned int *, unsigned int *, int, void *) conv, void * data)
```

```json
{
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:654",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:__do_proc_douintvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579576496,
      "name": "do_proc_douintvec_w",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    },
    {
      "addr": 18446744071579581626,
      "name": "do_proc_douintvec_w.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int do_proc_douintvec_w(unsigned int * tbl_data, struct ctl_table * table, void * buffer, size_t * lenp, loff_t * ppos, int (*)(long unsigned int *, unsigned int *, int, void *) conv, void * data)
```

```json
{
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:653",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:__do_proc_douintvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579558112,
      "name": "do_proc_douintvec_w",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    },
    {
      "addr": 18446744071591278838,
      "name": "do_proc_douintvec_w.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579567420,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:665",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579636481,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:689",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579732218,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:569",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579863984,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:556",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579914112,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:555",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579953360,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:555",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490692412,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:2437",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224760256,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:2437",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283518432,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:2437",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271428030,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:2437",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579517697,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:2437",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579446497,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:2437",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579517617,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:2437",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_proc_douintvec_w",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579550577,
      "name": "do_proc_douintvec_w",
      "external": false,
      "loc": "kernel/sysctl.c:2437",
      "file": "kernel/sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sysctl.c:__do_proc_douintvec"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int do_proc_douintvec_w(unsigned int * tbl_data, struct ctl_table * table, void * buffer, size_t * lenp, loff_t * ppos, int (*)(long unsigned int *, unsigned int *, int, void *) conv, void * data)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int do_proc_douintvec_w(unsigned int * tbl_data, struct ctl_table * table, void * buffer, size_t * lenp, loff_t * ppos, int (*)(long unsigned int *, unsigned int *, int, void *) conv, void * data)
```
</details>
</li>
</ul>
