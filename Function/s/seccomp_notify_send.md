# Function: <code>seccomp_notify_send</code>

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
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580384763,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1075",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
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
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580437403,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1080",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
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
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580486171,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1098",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
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
long int seccomp_notify_send(struct seccomp_filter * filter, void * buf)
```

```json
{
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580572032,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1114",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580572032,
      "name": "seccomp_notify_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
long int seccomp_notify_send(struct seccomp_filter * filter, void * buf)
```

```json
{
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580559472,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1485",
      "file": "kernel/seccomp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580559472,
      "name": "seccomp_notify_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580563739,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1515",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
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
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580733435,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1497",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
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
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580946395,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1526",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
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
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581240619,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1526",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
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
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581335839,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1526",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
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
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581442771,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1570",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
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
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491765848,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1098",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
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
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225713012,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1098",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
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
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284804848,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1098",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
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
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272082610,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1098",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
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
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580454971,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1098",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
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
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580402043,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1098",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
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
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580446219,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1098",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
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
  "name": "seccomp_notify_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580501851,
      "name": "seccomp_notify_send",
      "external": false,
      "loc": "kernel/seccomp.c:1098",
      "file": "kernel/seccomp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/seccomp.c:seccomp_notify_ioctl"
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
long int seccomp_notify_send(struct seccomp_filter * filter, void * buf)
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
long int seccomp_notify_send(struct seccomp_filter * filter, void * buf)
```
</details>
</li>
</ul>
