# Function: <code>copy_pipe_to_iter_mcsafe</code>

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
  "name": "copy_pipe_to_iter_mcsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583857732,
      "name": "copy_pipe_to_iter_mcsafe",
      "external": false,
      "loc": "lib/iov_iter.c:599",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
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
  "name": "copy_pipe_to_iter_mcsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583941916,
      "name": "copy_pipe_to_iter_mcsafe",
      "external": false,
      "loc": "lib/iov_iter.c:643",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
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
  "name": "copy_pipe_to_iter_mcsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584120481,
      "name": "copy_pipe_to_iter_mcsafe",
      "external": false,
      "loc": "lib/iov_iter.c:644",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
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
  "name": "copy_pipe_to_iter_mcsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584243649,
      "name": "copy_pipe_to_iter_mcsafe",
      "external": false,
      "loc": "lib/iov_iter.c:644",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
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
size_t copy_pipe_to_iter_mcsafe(const void * addr, size_t bytes, struct iov_iter * i)
```

```json
{
  "name": "copy_pipe_to_iter_mcsafe",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584643840,
      "name": "copy_pipe_to_iter_mcsafe",
      "external": false,
      "loc": "lib/iov_iter.c:662",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584643840,
      "name": "copy_pipe_to_iter_mcsafe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "copy_pipe_to_iter_mcsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290367776,
      "name": "copy_pipe_to_iter_mcsafe",
      "external": false,
      "loc": "lib/iov_iter.c:644",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
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
  "name": "copy_pipe_to_iter_mcsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584212385,
      "name": "copy_pipe_to_iter_mcsafe",
      "external": false,
      "loc": "lib/iov_iter.c:644",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
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
  "name": "copy_pipe_to_iter_mcsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584147601,
      "name": "copy_pipe_to_iter_mcsafe",
      "external": false,
      "loc": "lib/iov_iter.c:644",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
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
  "name": "copy_pipe_to_iter_mcsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584196145,
      "name": "copy_pipe_to_iter_mcsafe",
      "external": false,
      "loc": "lib/iov_iter.c:644",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
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
  "name": "copy_pipe_to_iter_mcsafe",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584300641,
      "name": "copy_pipe_to_iter_mcsafe",
      "external": false,
      "loc": "lib/iov_iter.c:644",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:_copy_to_iter_mcsafe"
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
size_t copy_pipe_to_iter_mcsafe(const void * addr, size_t bytes, struct iov_iter * i)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
size_t copy_pipe_to_iter_mcsafe(const void * addr, size_t bytes, struct iov_iter * i)
```
</details>
</li>
</ul>
