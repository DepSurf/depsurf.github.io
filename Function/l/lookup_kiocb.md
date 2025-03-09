# Function: <code>lookup_kiocb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lookup_kiocb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581325707,
      "name": "lookup_kiocb",
      "external": false,
      "loc": "fs/aio.c:1647",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:SyS_io_cancel"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lookup_kiocb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581492923,
      "name": "lookup_kiocb",
      "external": false,
      "loc": "fs/aio.c:1655",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:SyS_io_cancel"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lookup_kiocb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581574459,
      "name": "lookup_kiocb",
      "external": false,
      "loc": "fs/aio.c:1742",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:SyS_io_cancel"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lookup_kiocb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581631115,
      "name": "lookup_kiocb",
      "external": false,
      "loc": "fs/aio.c:1760",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:SyS_io_cancel"
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
  "name": "lookup_kiocb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581775931,
      "name": "lookup_kiocb",
      "external": false,
      "loc": "fs/aio.c:1768",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:SyS_io_cancel"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb * lookup_kiocb(struct kioctx * ctx, struct iocb * iocb)
```

```json
{
  "name": "lookup_kiocb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581933840,
      "name": "lookup_kiocb",
      "external": false,
      "loc": "fs/aio.c:1787",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581933840,
      "name": "lookup_kiocb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct aio_kiocb * lookup_kiocb(struct kioctx * ctx, struct iocb * iocb)
```

```json
{
  "name": "lookup_kiocb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582018272,
      "name": "lookup_kiocb",
      "external": false,
      "loc": "fs/aio.c:2004",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582018272,
      "name": "lookup_kiocb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct aio_kiocb * lookup_kiocb(struct kioctx * ctx, struct iocb * iocb)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
struct aio_kiocb * lookup_kiocb(struct kioctx * ctx, struct iocb * iocb)
```
</details>
</li>
</ul>
