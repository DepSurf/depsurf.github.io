# Function: <code>csum_and_copy_to_pipe_iter</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "csum_and_copy_to_pipe_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583950303,
      "name": "csum_and_copy_to_pipe_iter",
      "external": false,
      "loc": "lib/iov_iter.c:571",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
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
  "name": "csum_and_copy_to_pipe_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584129500,
      "name": "csum_and_copy_to_pipe_iter",
      "external": false,
      "loc": "lib/iov_iter.c:572",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
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
  "name": "csum_and_copy_to_pipe_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584252672,
      "name": "csum_and_copy_to_pipe_iter",
      "external": false,
      "loc": "lib/iov_iter.c:572",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
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
size_t csum_and_copy_to_pipe_iter(const void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_to_pipe_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584642192,
      "name": "csum_and_copy_to_pipe_iter",
      "external": false,
      "loc": "lib/iov_iter.c:587",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584642192,
      "name": "csum_and_copy_to_pipe_iter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
size_t csum_and_copy_to_pipe_iter(const void * addr, size_t bytes, struct csum_state * csstate, struct iov_iter * i)
```

```json
{
  "name": "csum_and_copy_to_pipe_iter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584763520,
      "name": "csum_and_copy_to_pipe_iter",
      "external": false,
      "loc": "lib/iov_iter.c:594",
      "file": "lib/iov_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584763520,
      "name": "csum_and_copy_to_pipe_iter",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "csum_and_copy_to_pipe_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584821851,
      "name": "csum_and_copy_to_pipe_iter",
      "external": false,
      "loc": "lib/iov_iter.c:615",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
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
  "name": "csum_and_copy_to_pipe_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585240511,
      "name": "csum_and_copy_to_pipe_iter",
      "external": false,
      "loc": "lib/iov_iter.c:585",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
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
  "name": "csum_and_copy_to_pipe_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586081166,
      "name": "csum_and_copy_to_pipe_iter",
      "external": false,
      "loc": "lib/iov_iter.c:630",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
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
  "name": "csum_and_copy_to_pipe_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587062370,
      "name": "csum_and_copy_to_pipe_iter",
      "external": false,
      "loc": "lib/iov_iter.c:489",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "csum_and_copy_to_pipe_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496130200,
      "name": "csum_and_copy_to_pipe_iter",
      "external": false,
      "loc": "lib/iov_iter.c:572",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
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
  "name": "csum_and_copy_to_pipe_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229453044,
      "name": "csum_and_copy_to_pipe_iter",
      "external": false,
      "loc": "lib/iov_iter.c:572",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
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
  "name": "csum_and_copy_to_pipe_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290380256,
      "name": "csum_and_copy_to_pipe_iter",
      "external": false,
      "loc": "lib/iov_iter.c:572",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
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
  "name": "csum_and_copy_to_pipe_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275189282,
      "name": "csum_and_copy_to_pipe_iter",
      "external": false,
      "loc": "lib/iov_iter.c:572",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
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
  "name": "csum_and_copy_to_pipe_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584221408,
      "name": "csum_and_copy_to_pipe_iter",
      "external": false,
      "loc": "lib/iov_iter.c:572",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
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
  "name": "csum_and_copy_to_pipe_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584156624,
      "name": "csum_and_copy_to_pipe_iter",
      "external": false,
      "loc": "lib/iov_iter.c:572",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
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
  "name": "csum_and_copy_to_pipe_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584205168,
      "name": "csum_and_copy_to_pipe_iter",
      "external": false,
      "loc": "lib/iov_iter.c:572",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
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
  "name": "csum_and_copy_to_pipe_iter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584309707,
      "name": "csum_and_copy_to_pipe_iter",
      "external": false,
      "loc": "lib/iov_iter.c:572",
      "file": "lib/iov_iter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/iov_iter.c:csum_and_copy_to_iter"
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
size_t csum_and_copy_to_pipe_iter(const void * addr, size_t bytes, __wsum * csum, struct iov_iter * i)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct csum_state * csstate</code>
</li>
<li>
<b>Param removed. </b>
<code>__wsum * csum</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
size_t csum_and_copy_to_pipe_iter(const void * addr, size_t bytes, struct csum_state * csstate, struct iov_iter * i)
```
</details>
</li>
</ul>
