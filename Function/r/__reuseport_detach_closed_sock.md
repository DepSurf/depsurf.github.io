# Function: <code>__reuseport_detach_closed_sock</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__reuseport_detach_closed_sock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590190506,
      "name": "__reuseport_detach_closed_sock",
      "external": false,
      "loc": "net/core/sock_reuseport.c:75",
      "file": "net/core/sock_reuseport.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_detach_sock",
        "net/core/sock_reuseport.c:reuseport_resurrect",
        "net/core/sock_reuseport.c:reuseport_resurrect",
        "net/core/sock_reuseport.c:reuseport_grow"
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
  "name": "__reuseport_detach_closed_sock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591753612,
      "name": "__reuseport_detach_closed_sock",
      "external": false,
      "loc": "net/core/sock_reuseport.c:75",
      "file": "net/core/sock_reuseport.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_reuseport.c:reuseport_detach_sock",
        "net/core/sock_reuseport.c:reuseport_resurrect",
        "net/core/sock_reuseport.c:reuseport_resurrect",
        "net/core/sock_reuseport.c:reuseport_grow"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool __reuseport_detach_closed_sock(struct sock * sk, struct sock_reuseport * reuse)
```

```json
{
  "name": "__reuseport_detach_closed_sock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593543344,
      "name": "__reuseport_detach_closed_sock",
      "external": false,
      "loc": "net/core/sock_reuseport.c:158",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_detach_sock",
        "net/core/sock_reuseport.c:reuseport_resurrect",
        "net/core/sock_reuseport.c:reuseport_resurrect",
        "net/core/sock_reuseport.c:reuseport_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593543344,
      "name": "__reuseport_detach_closed_sock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
bool __reuseport_detach_closed_sock(struct sock * sk, struct sock_reuseport * reuse)
```

```json
{
  "name": "__reuseport_detach_closed_sock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594012416,
      "name": "__reuseport_detach_closed_sock",
      "external": false,
      "loc": "net/core/sock_reuseport.c:158",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_detach_sock",
        "net/core/sock_reuseport.c:reuseport_resurrect",
        "net/core/sock_reuseport.c:reuseport_resurrect",
        "net/core/sock_reuseport.c:reuseport_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594012416,
      "name": "__reuseport_detach_closed_sock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
bool __reuseport_detach_closed_sock(struct sock * sk, struct sock_reuseport * reuse)
```

```json
{
  "name": "__reuseport_detach_closed_sock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594798784,
      "name": "__reuseport_detach_closed_sock",
      "external": false,
      "loc": "net/core/sock_reuseport.c:158",
      "file": "net/core/sock_reuseport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_reuseport.c:reuseport_detach_sock",
        "net/core/sock_reuseport.c:reuseport_resurrect",
        "net/core/sock_reuseport.c:reuseport_resurrect",
        "net/core/sock_reuseport.c:reuseport_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594798784,
      "name": "__reuseport_detach_closed_sock",
      "section": ".text",
      "bind": "STB_LOCAL",
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
bool __reuseport_detach_closed_sock(struct sock * sk, struct sock_reuseport * reuse)
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
