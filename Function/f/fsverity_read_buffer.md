# Function: <code>fsverity_read_buffer</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsverity_read_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582713914,
      "name": "fsverity_read_buffer",
      "external": false,
      "loc": "fs/verity/read_metadata.c:81",
      "file": "fs/verity/read_metadata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata",
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata"
      ],
      "caller_func": [
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582712960,
      "name": "fsverity_read_buffer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fsverity_read_buffer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583040538,
      "name": "fsverity_read_buffer",
      "external": false,
      "loc": "fs/verity/read_metadata.c:81",
      "file": "fs/verity/read_metadata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata",
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata"
      ],
      "caller_func": [
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583039600,
      "name": "fsverity_read_buffer.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
int fsverity_read_buffer(void * dst, u64 offset, int length, const void * src, size_t src_length)
```

```json
{
  "name": "fsverity_read_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583514240,
      "name": "fsverity_read_buffer",
      "external": false,
      "loc": "fs/verity/read_metadata.c:81",
      "file": "fs/verity/read_metadata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata",
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583514240,
      "name": "fsverity_read_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int fsverity_read_buffer(void * dst, u64 offset, int length, const void * src, size_t src_length)
```

```json
{
  "name": "fsverity_read_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584112832,
      "name": "fsverity_read_buffer",
      "external": false,
      "loc": "fs/verity/read_metadata.c:81",
      "file": "fs/verity/read_metadata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata",
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584112832,
      "name": "fsverity_read_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int fsverity_read_buffer(void * dst, u64 offset, int length, const void * src, size_t src_length)
```

```json
{
  "name": "fsverity_read_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584338928,
      "name": "fsverity_read_buffer",
      "external": false,
      "loc": "fs/verity/read_metadata.c:81",
      "file": "fs/verity/read_metadata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata",
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584338928,
      "name": "fsverity_read_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int fsverity_read_buffer(void * dst, u64 offset, int length, const void * src, size_t src_length)
```

```json
{
  "name": "fsverity_read_buffer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584557136,
      "name": "fsverity_read_buffer",
      "external": false,
      "loc": "fs/verity/read_metadata.c:81",
      "file": "fs/verity/read_metadata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata",
        "fs/verity/read_metadata.c:fsverity_ioctl_read_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584557136,
      "name": "fsverity_read_buffer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int fsverity_read_buffer(void * dst, u64 offset, int length, const void * src, size_t src_length)
```
</details>
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
