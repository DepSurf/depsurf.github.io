# Function: <code>__do_sys_olduname</code>

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
  "name": "__do_sys_olduname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579524127,
      "name": "__do_sys_olduname",
      "external": false,
      "loc": "kernel/sys.c:1294",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_olduname",
        "kernel/sys.c:__x64_sys_olduname"
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
  "name": "__do_sys_olduname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579560223,
      "name": "__do_sys_olduname",
      "external": false,
      "loc": "kernel/sys.c:1295",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_olduname",
        "kernel/sys.c:__x64_sys_olduname"
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
  "name": "__do_sys_olduname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579579167,
      "name": "__do_sys_olduname",
      "external": false,
      "loc": "kernel/sys.c:1295",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_olduname",
        "kernel/sys.c:__x64_sys_olduname"
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
  "name": "__do_sys_olduname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579605263,
      "name": "__do_sys_olduname",
      "external": false,
      "loc": "kernel/sys.c:1295",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_olduname",
        "kernel/sys.c:__x64_sys_olduname"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int __do_sys_olduname(struct oldold_utsname * name)
```

```json
{
  "name": "__do_sys_olduname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579634672,
      "name": "__do_sys_olduname",
      "external": false,
      "loc": "kernel/sys.c:1309",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_olduname",
        "kernel/sys.c:__x64_sys_olduname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579634672,
      "name": "__do_sys_olduname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
long int __do_sys_olduname(struct oldold_utsname * name)
```

```json
{
  "name": "__do_sys_olduname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579614560,
      "name": "__do_sys_olduname",
      "external": false,
      "loc": "kernel/sys.c:1310",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_olduname",
        "kernel/sys.c:__x64_sys_olduname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614560,
      "name": "__do_sys_olduname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
long int __do_sys_olduname(struct oldold_utsname * name)
```

```json
{
  "name": "__do_sys_olduname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579620864,
      "name": "__do_sys_olduname",
      "external": false,
      "loc": "kernel/sys.c:1327",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_olduname",
        "kernel/sys.c:__x64_sys_olduname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579620864,
      "name": "__do_sys_olduname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
long int __do_sys_olduname(struct oldold_utsname * name)
```

```json
{
  "name": "__do_sys_olduname",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579696288,
      "name": "__do_sys_olduname",
      "external": false,
      "loc": "kernel/sys.c:1336",
      "file": "kernel/sys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__ia32_sys_olduname",
        "kernel/sys.c:__x64_sys_olduname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579696288,
      "name": "__do_sys_olduname",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_olduname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579796836,
      "name": "__do_sys_olduname",
      "external": false,
      "loc": "kernel/sys.c:1343",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_olduname",
        "kernel/sys.c:__x64_sys_olduname"
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
  "name": "__do_sys_olduname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579931476,
      "name": "__do_sys_olduname",
      "external": false,
      "loc": "kernel/sys.c:1344",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_olduname",
        "kernel/sys.c:__x64_sys_olduname"
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
  "name": "__do_sys_olduname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579981412,
      "name": "__do_sys_olduname",
      "external": false,
      "loc": "kernel/sys.c:1362",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_olduname",
        "kernel/sys.c:__x64_sys_olduname"
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
  "name": "__do_sys_olduname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580020820,
      "name": "__do_sys_olduname",
      "external": false,
      "loc": "kernel/sys.c:1362",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_olduname",
        "kernel/sys.c:__x64_sys_olduname"
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_olduname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283595788,
      "name": "__do_sys_olduname",
      "external": false,
      "loc": "kernel/sys.c:1295",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__se_sys_olduname"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_olduname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579581567,
      "name": "__do_sys_olduname",
      "external": false,
      "loc": "kernel/sys.c:1295",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_olduname",
        "kernel/sys.c:__x64_sys_olduname"
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
  "name": "__do_sys_olduname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579510191,
      "name": "__do_sys_olduname",
      "external": false,
      "loc": "kernel/sys.c:1295",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_olduname",
        "kernel/sys.c:__x64_sys_olduname"
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
  "name": "__do_sys_olduname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579578847,
      "name": "__do_sys_olduname",
      "external": false,
      "loc": "kernel/sys.c:1295",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_olduname",
        "kernel/sys.c:__x64_sys_olduname"
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
  "name": "__do_sys_olduname",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579614207,
      "name": "__do_sys_olduname",
      "external": false,
      "loc": "kernel/sys.c:1295",
      "file": "kernel/sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sys.c:__ia32_sys_olduname",
        "kernel/sys.c:__x64_sys_olduname"
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
long int __do_sys_olduname(struct oldold_utsname * name)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
long int __do_sys_olduname(struct oldold_utsname * name)
```
</details>
</li>
</ul>
