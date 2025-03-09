# Function: <code>__sock_set_timestamps</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sock_set_timestamps(struct sock * sk, bool val, bool new, bool ns)
```

```json
{
  "name": "__sock_set_timestamps",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589238085,
      "name": "__sock_set_timestamps",
      "external": false,
      "loc": "net/core/sock.c:770",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_enable_timestamps"
      ],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589224944,
      "name": "__sock_set_timestamps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sock_set_timestamps",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589233819,
      "name": "__sock_set_timestamps",
      "external": false,
      "loc": "net/core/sock.c:750",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_enable_timestamps"
      ],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589222848,
      "name": "__sock_set_timestamps.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
  "name": "__sock_set_timestamps",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589127627,
      "name": "__sock_set_timestamps",
      "external": false,
      "loc": "net/core/sock.c:758",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_enable_timestamps"
      ],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589116624,
      "name": "__sock_set_timestamps.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
  "name": "__sock_set_timestamps",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589847114,
      "name": "__sock_set_timestamps",
      "external": false,
      "loc": "net/core/sock.c:777",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_enable_timestamps"
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
  "name": "__sock_set_timestamps",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591363677,
      "name": "__sock_set_timestamps",
      "external": false,
      "loc": "net/core/sock.c:817",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_enable_timestamps",
        "net/core/sock.c:sock_enable_timestamps"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sock_set_timestamps(struct sock * sk, bool val, bool new, bool ns)
```

```json
{
  "name": "__sock_set_timestamps",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593112688,
      "name": "__sock_set_timestamps",
      "external": false,
      "loc": "net/core/sock.c:819",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_enable_timestamps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593112688,
      "name": "__sock_set_timestamps",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sock_set_timestamps(struct sock * sk, bool val, bool new, bool ns)
```

```json
{
  "name": "__sock_set_timestamps",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593564224,
      "name": "__sock_set_timestamps",
      "external": false,
      "loc": "net/core/sock.c:825",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_enable_timestamps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593564224,
      "name": "__sock_set_timestamps",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sock_set_timestamps(struct sock * sk, bool val, bool new, bool ns)
```

```json
{
  "name": "__sock_set_timestamps",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594336816,
      "name": "__sock_set_timestamps",
      "external": false,
      "loc": "net/core/sock.c:821",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_set_timestamp",
        "net/core/sock.c:sock_enable_timestamps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594336816,
      "name": "__sock_set_timestamps",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __sock_set_timestamps(struct sock * sk, bool val, bool new, bool ns)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void __sock_set_timestamps(struct sock * sk, bool val, bool new, bool ns)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void __sock_set_timestamps(struct sock * sk, bool val, bool new, bool ns)
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
