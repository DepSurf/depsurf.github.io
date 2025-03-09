# Function: <code>__do_sys_ioprio_get</code>

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
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583670670,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:185",
      "file": "block/ioprio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get"
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
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583777950,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:185",
      "file": "block/ioprio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get"
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
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583967678,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:186",
      "file": "block/ioprio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get"
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
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584071038,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:186",
      "file": "block/ioprio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get"
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
long int __do_sys_ioprio_get(int which, int who)
```

```json
{
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584463344,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:186",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463344,
      "name": "__do_sys_ioprio_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
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
long int __do_sys_ioprio_get(int which, int who)
```

```json
{
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584578384,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:186",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584578384,
      "name": "__do_sys_ioprio_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 789
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
long int __do_sys_ioprio_get(int which, int who)
```

```json
{
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584610448,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:193",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584610448,
      "name": "__do_sys_ioprio_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 789
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
long int __do_sys_ioprio_get(int which, int who)
```

```json
{
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585024816,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:199",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585024816,
      "name": "__do_sys_ioprio_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
long int __do_sys_ioprio_get(int which, int who)
```

```json
{
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585741568,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:167",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585741568,
      "name": "__do_sys_ioprio_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1012
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
long int __do_sys_ioprio_get(int which, int who)
```

```json
{
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586523952,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:209",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586523952,
      "name": "__do_sys_ioprio_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 875
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
long int __do_sys_ioprio_get(int which, int who)
```

```json
{
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586770176,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:210",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586770176,
      "name": "__do_sys_ioprio_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
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
long int __do_sys_ioprio_get(int which, int who)
```

```json
{
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587042864,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:184",
      "file": "block/ioprio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587042864,
      "name": "__do_sys_ioprio_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
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
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495914480,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:186",
      "file": "block/ioprio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/ioprio.c:__arm64_sys_ioprio_get"
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
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229257712,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:186",
      "file": "block/ioprio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/ioprio.c:__se_sys_ioprio_get"
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
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290124504,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:186",
      "file": "block/ioprio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/ioprio.c:__se_sys_ioprio_get"
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
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275028582,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:186",
      "file": "block/ioprio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/ioprio.c:__se_sys_ioprio_get"
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
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584039774,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:186",
      "file": "block/ioprio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get"
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
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583975534,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:186",
      "file": "block/ioprio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get"
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
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584023534,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:186",
      "file": "block/ioprio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get"
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
  "name": "__do_sys_ioprio_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584126094,
      "name": "__do_sys_ioprio_get",
      "external": false,
      "loc": "block/ioprio.c:186",
      "file": "block/ioprio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/ioprio.c:__ia32_sys_ioprio_get",
        "block/ioprio.c:__x64_sys_ioprio_get"
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
long int __do_sys_ioprio_get(int which, int who)
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
