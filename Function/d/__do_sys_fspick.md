# Function: <code>__do_sys_fspick</code>

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
  "name": "__do_sys_fspick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582039682,
      "name": "__do_sys_fspick",
      "external": false,
      "loc": "fs/fsopen.c:158",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick"
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
  "name": "__do_sys_fspick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582117522,
      "name": "__do_sys_fspick",
      "external": false,
      "loc": "fs/fsopen.c:158",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick"
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
long int __do_sys_fspick(int dfd, const char * path, unsigned int flags)
```

```json
{
  "name": "__do_sys_fspick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582354656,
      "name": "__do_sys_fspick",
      "external": false,
      "loc": "fs/fsopen.c:158",
      "file": "fs/fsopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582354656,
      "name": "__do_sys_fspick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
long int __do_sys_fspick(int dfd, const char * path, unsigned int flags)
```

```json
{
  "name": "__do_sys_fspick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582406240,
      "name": "__do_sys_fspick",
      "external": false,
      "loc": "fs/fsopen.c:158",
      "file": "fs/fsopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582406240,
      "name": "__do_sys_fspick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
long int __do_sys_fspick(int dfd, const char * path, unsigned int flags)
```

```json
{
  "name": "__do_sys_fspick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582433440,
      "name": "__do_sys_fspick",
      "external": false,
      "loc": "fs/fsopen.c:158",
      "file": "fs/fsopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582433440,
      "name": "__do_sys_fspick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
long int __do_sys_fspick(int dfd, const char * path, unsigned int flags)
```

```json
{
  "name": "__do_sys_fspick",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582756208,
      "name": "__do_sys_fspick",
      "external": false,
      "loc": "fs/fsopen.c:158",
      "file": "fs/fsopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582756208,
      "name": "__do_sys_fspick",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
  "name": "__do_sys_fspick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583304572,
      "name": "__do_sys_fspick",
      "external": false,
      "loc": "fs/fsopen.c:158",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick"
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
  "name": "__do_sys_fspick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583890044,
      "name": "__do_sys_fspick",
      "external": false,
      "loc": "fs/fsopen.c:158",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick"
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
  "name": "__do_sys_fspick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584111932,
      "name": "__do_sys_fspick",
      "external": false,
      "loc": "fs/fsopen.c:158",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick"
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
  "name": "__do_sys_fspick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584328508,
      "name": "__do_sys_fspick",
      "external": false,
      "loc": "fs/fsopen.c:158",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick"
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
  "name": "__do_sys_fspick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493658048,
      "name": "__do_sys_fspick",
      "external": false,
      "loc": "fs/fsopen.c:158",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__arm64_sys_fspick"
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
  "name": "__do_sys_fspick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227191684,
      "name": "__do_sys_fspick",
      "external": false,
      "loc": "fs/fsopen.c:158",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__se_sys_fspick"
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
  "name": "__do_sys_fspick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287256564,
      "name": "__do_sys_fspick",
      "external": false,
      "loc": "fs/fsopen.c:158",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__se_sys_fspick"
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
  "name": "__do_sys_fspick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273287390,
      "name": "__do_sys_fspick",
      "external": false,
      "loc": "fs/fsopen.c:158",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__se_sys_fspick"
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
  "name": "__do_sys_fspick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582086258,
      "name": "__do_sys_fspick",
      "external": false,
      "loc": "fs/fsopen.c:158",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick"
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
  "name": "__do_sys_fspick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582023778,
      "name": "__do_sys_fspick",
      "external": false,
      "loc": "fs/fsopen.c:158",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick"
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
  "name": "__do_sys_fspick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582076738,
      "name": "__do_sys_fspick",
      "external": false,
      "loc": "fs/fsopen.c:158",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick"
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
  "name": "__do_sys_fspick",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582149298,
      "name": "__do_sys_fspick",
      "external": false,
      "loc": "fs/fsopen.c:158",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__ia32_sys_fspick",
        "fs/fsopen.c:__x64_sys_fspick"
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
long int __do_sys_fspick(int dfd, const char * path, unsigned int flags)
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
long int __do_sys_fspick(int dfd, const char * path, unsigned int flags)
```
</details>
</li>
</ul>
