# Function: <code>unix_open_file</code>

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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587761563,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2599",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588290347,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2578",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588660632,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2568",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588864376,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2585",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589304078,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2521",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589528430,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2533",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
int unix_open_file(struct sock * sk)
```

```json
{
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590525248,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2584",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590525248,
      "name": "unix_open_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int unix_open_file(struct sock * sk)
```

```json
{
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590585104,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2575",
      "file": "net/unix/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/unix/af_unix.c:unix_compat_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590585104,
      "name": "unix_open_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590512705,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2624",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591319225,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2948",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592986205,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:3032",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594874573,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:3068",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595266877,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2983",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596107725,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:3000",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503198040,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2533",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235870068,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2533",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296933136,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2533",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279235116,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2533",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589132798,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2533",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588857790,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2533",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589569662,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2533",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
  "name": "unix_open_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589616478,
      "name": "unix_open_file",
      "external": false,
      "loc": "net/unix/af_unix.c:2533",
      "file": "net/unix/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/unix/af_unix.c:unix_ioctl"
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
int unix_open_file(struct sock * sk)
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
int unix_open_file(struct sock * sk)
```
</details>
</li>
</ul>
