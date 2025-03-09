# Function: <code>sched_core_put_cookie</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_core_put_cookie(long unsigned int cookie)
```

```json
{
  "name": "sched_core_put_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580074892,
      "name": "sched_core_put_cookie",
      "external": true,
      "loc": "kernel/sched/core_sched.c:26",
      "file": "kernel/sched/core_sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/core_sched.c:sched_core_free"
      ],
      "caller_func": [
        "kernel/sched/core_sched.c:sched_core_share_pid",
        "kernel/sched/core_sched.c:sched_core_share_pid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580074128,
      "name": "sched_core_put_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_core_put_cookie(long unsigned int cookie)
```

```json
{
  "name": "sched_core_put_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580202412,
      "name": "sched_core_put_cookie",
      "external": false,
      "loc": "kernel/sched/core_sched.c:23",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_core_free"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/sched/build_utility.c:__sched_core_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580163232,
      "name": "sched_core_put_cookie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_core_put_cookie(long unsigned int cookie)
```

```json
{
  "name": "sched_core_put_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580393516,
      "name": "sched_core_put_cookie",
      "external": false,
      "loc": "kernel/sched/core_sched.c:23",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_core_free"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/sched/build_utility.c:__sched_core_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580338560,
      "name": "sched_core_put_cookie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_core_put_cookie(long unsigned int cookie)
```

```json
{
  "name": "sched_core_put_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580461964,
      "name": "sched_core_put_cookie",
      "external": false,
      "loc": "kernel/sched/core_sched.c:23",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_core_free"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/sched/build_utility.c:__sched_core_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580405984,
      "name": "sched_core_put_cookie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sched_core_put_cookie(long unsigned int cookie)
```

```json
{
  "name": "sched_core_put_cookie",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580521628,
      "name": "sched_core_put_cookie",
      "external": false,
      "loc": "kernel/sched/core_sched.c:23",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:sched_core_free"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_core_share_pid",
        "kernel/sched/build_utility.c:__sched_core_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580462432,
      "name": "sched_core_put_cookie",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void sched_core_put_cookie(long unsigned int cookie)
```
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
