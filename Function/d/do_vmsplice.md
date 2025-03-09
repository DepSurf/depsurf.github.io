# Function: <code>do_vmsplice</code>

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
  "name": "do_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581799953,
      "name": "do_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1331",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ],
      "caller_func": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581799056,
      "name": "do_vmsplice.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581887089,
      "name": "do_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1335",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ],
      "caller_func": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886272,
      "name": "do_vmsplice.part.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582013172,
      "name": "do_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1341",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ],
      "caller_func": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582012352,
      "name": "do_vmsplice.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582091140,
      "name": "do_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1349",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ],
      "caller_func": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582090320,
      "name": "do_vmsplice.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int do_vmsplice(struct file * f, struct iov_iter * iter, unsigned int flags)
```

```json
{
  "name": "do_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582323456,
      "name": "do_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1337",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582323456,
      "name": "do_vmsplice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "do_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493623400,
      "name": "do_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1349",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ],
      "caller_func": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493622560,
      "name": "do_vmsplice.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "do_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227163940,
      "name": "do_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1349",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:__do_sys_vmsplice"
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
  "name": "do_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287217448,
      "name": "do_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1349",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ],
      "caller_func": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287216384,
      "name": "do_vmsplice.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "do_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273266108,
      "name": "do_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1349",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:__do_sys_vmsplice"
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
  "name": "do_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582059876,
      "name": "do_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1349",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ],
      "caller_func": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582059056,
      "name": "do_vmsplice.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581997428,
      "name": "do_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1349",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ],
      "caller_func": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581996608,
      "name": "do_vmsplice.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582051156,
      "name": "do_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1349",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ],
      "caller_func": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582050336,
      "name": "do_vmsplice.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_vmsplice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582122836,
      "name": "do_vmsplice",
      "external": false,
      "loc": "fs/splice.c:1349",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ],
      "caller_func": [
        "fs/splice.c:__do_compat_sys_vmsplice",
        "fs/splice.c:__do_sys_vmsplice"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582122016,
      "name": "do_vmsplice.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long int do_vmsplice(struct file * f, struct iov_iter * iter, unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
long int do_vmsplice(struct file * f, struct iov_iter * iter, unsigned int flags)
```
</details>
</li>
</ul>
