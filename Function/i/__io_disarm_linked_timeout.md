# Function: <code>__io_disarm_linked_timeout</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct io_kiocb * __io_disarm_linked_timeout(struct io_kiocb * req, struct io_kiocb * link)
```

```json
{
  "name": "__io_disarm_linked_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586813540,
      "name": "__io_disarm_linked_timeout",
      "external": true,
      "loc": "io_uring/timeout.c:178",
      "file": "io_uring/timeout.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_disarm_next"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586813680,
      "name": "__io_disarm_linked_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct io_kiocb * __io_disarm_linked_timeout(struct io_kiocb * req, struct io_kiocb * link)
```

```json
{
  "name": "__io_disarm_linked_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587079982,
      "name": "__io_disarm_linked_timeout",
      "external": true,
      "loc": "io_uring/timeout.c:218",
      "file": "io_uring/timeout.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_disarm_next"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587080128,
      "name": "__io_disarm_linked_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct io_kiocb * __io_disarm_linked_timeout(struct io_kiocb * req, struct io_kiocb * link)
```

```json
{
  "name": "__io_disarm_linked_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587359262,
      "name": "__io_disarm_linked_timeout",
      "external": true,
      "loc": "io_uring/timeout.c:218",
      "file": "io_uring/timeout.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_disarm_next"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587359408,
      "name": "__io_disarm_linked_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct io_kiocb * __io_disarm_linked_timeout(struct io_kiocb * req, struct io_kiocb * link)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
