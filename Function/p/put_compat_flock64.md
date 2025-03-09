# Function: <code>put_compat_flock64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int put_compat_flock64(struct flock * kfl, struct compat_flock64 * ufl)
```

```json
{
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581348464,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/compat.c:389",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581348464,
      "name": "put_compat_flock64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int put_compat_flock64(struct flock * kfl, struct compat_flock64 * ufl)
```

```json
{
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581529280,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/compat.c:389",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581529280,
      "name": "put_compat_flock64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int put_compat_flock64(struct flock * kfl, struct compat_flock64 * ufl)
```

```json
{
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581615280,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/compat.c:375",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581615280,
      "name": "put_compat_flock64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int put_compat_flock64(const struct flock * kfl, struct compat_flock64 * ufl)
```

```json
{
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581357904,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:564",
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
      "addr": 18446744071581357904,
      "name": "put_compat_flock64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
int put_compat_flock64(const struct flock * kfl, struct compat_flock64 * ufl)
```

```json
{
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581499040,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:565",
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
      "addr": 18446744071581499040,
      "name": "put_compat_flock64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581659177,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:565",
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
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581745414,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:565",
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
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581862778,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:565",
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
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581935146,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:565",
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
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582165140,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:565",
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
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582211588,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:565",
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
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582236534,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:570",
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
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582555126,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:574",
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
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583083751,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:552",
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
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583651159,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:553",
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
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583868288,
      "name": "put_compat_flock64",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584075344,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:555",
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
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493418640,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:565",
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
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286978224,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:565",
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
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581903882,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:565",
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
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581841482,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:565",
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
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581895194,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:565",
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
  "name": "put_compat_flock64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581964778,
      "name": "put_compat_flock64",
      "external": false,
      "loc": "fs/fcntl.c:565",
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
int put_compat_flock64(const struct flock * kfl, struct compat_flock64 * ufl)
```
</details>
</li>
</ul>
