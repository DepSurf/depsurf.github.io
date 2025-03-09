# Function: <code>fuse_send_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582084243,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:636",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_do_readpage",
        "fs/fuse/file.c:fuse_direct_io"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582304607,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:649",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_do_readpage"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582392943,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:650",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_do_readpage"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582477409,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:645",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_do_readpage"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582628387,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:645",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_do_readpage"
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
size_t fuse_send_read(struct fuse_req * req, struct fuse_io_priv * io, loff_t pos, size_t count, fl_owner_t owner)
```

```json
{
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582819936,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:645",
      "file": "fs/fuse/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_do_readpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582819936,
      "name": "fuse_send_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582925257,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:650",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_do_readpage"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583104962,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:662",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io",
        "fs/fuse/file.c:fuse_do_readpage"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583209452,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:722",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583537382,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:739",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583647238,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:762",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583666974,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:766",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584026722,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:770",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584614664,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:779",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585294004,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:779",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585524360,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:780",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585761390,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:781",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494929768,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:722",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228340688,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:722",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288800320,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:722",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274236514,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:722",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583178188,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:722",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583115340,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:722",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583162220,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:722",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
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
  "name": "fuse_send_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583255756,
      "name": "fuse_send_read",
      "external": false,
      "loc": "fs/fuse/file.c:722",
      "file": "fs/fuse/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_direct_io"
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
size_t fuse_send_read(struct fuse_req * req, struct fuse_io_priv * io, loff_t pos, size_t count, fl_owner_t owner)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
size_t fuse_send_read(struct fuse_req * req, struct fuse_io_priv * io, loff_t pos, size_t count, fl_owner_t owner)
```
</details>
</li>
</ul>
