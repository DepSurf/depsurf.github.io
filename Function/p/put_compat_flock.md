# Function: <code>put_compat_flock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int put_compat_flock(struct flock * kfl, struct compat_flock * ufl)
```

```json
{
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581348176,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/compat.c:362",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat.c:compat_SyS_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581348176,
      "name": "put_compat_flock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int put_compat_flock(struct flock * kfl, struct compat_flock * ufl)
```

```json
{
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581528992,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/compat.c:362",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat.c:compat_SyS_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581528992,
      "name": "put_compat_flock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int put_compat_flock(struct flock * kfl, struct compat_flock * ufl)
```

```json
{
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581614992,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/compat.c:348",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat.c:compat_SyS_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581614992,
      "name": "put_compat_flock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int put_compat_flock(const struct flock * kfl, struct compat_flock * ufl)
```

```json
{
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581357776,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:553",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:compat_SyS_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581357776,
      "name": "put_compat_flock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int put_compat_flock(const struct flock * kfl, struct compat_flock * ufl)
```

```json
{
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581498912,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:554",
      "file": "fs/fcntl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fcntl.c:compat_SyS_fcntl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498912,
      "name": "put_compat_flock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581658881,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:554",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64"
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
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581745155,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:554",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64"
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
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581862650,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:554",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64"
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
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581935018,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:554",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582165003,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:554",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64"
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
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582211451,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:554",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64"
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
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582236425,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:559",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64"
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
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582555017,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:563",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64"
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
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583083614,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:541",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64"
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
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583651022,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:542",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64"
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
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583868151,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:543",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64"
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
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584075207,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:544",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64"
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
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493418356,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:554",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286977748,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:554",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64"
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
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581903754,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:554",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64"
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
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581841354,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:554",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64"
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
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581895066,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:554",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64"
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
  "name": "put_compat_flock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581964650,
      "name": "put_compat_flock",
      "external": false,
      "loc": "fs/fcntl.c:554",
      "file": "fs/fcntl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fcntl.c:do_compat_fcntl64"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct flock * kfl</code> ➡️ <code>const struct flock * kfl</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int put_compat_flock(const struct flock * kfl, struct compat_flock * ufl)
```
</details>
</li>
</ul>
