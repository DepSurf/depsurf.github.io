# Function: <code>copy_bpf_fprog_from_user</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int copy_bpf_fprog_from_user(struct sock_fprog * dst, sockptr_t src, int len)
```

```json
{
  "name": "copy_bpf_fprog_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589523472,
      "name": "copy_bpf_fprog_from_user",
      "external": true,
      "loc": "net/core/filter.c:84",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/packet/af_packet.c:fanout_set_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589523472,
      "name": "copy_bpf_fprog_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int copy_bpf_fprog_from_user(struct sock_fprog * dst, sockptr_t src, int len)
```

```json
{
  "name": "copy_bpf_fprog_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589418608,
      "name": "copy_bpf_fprog_from_user",
      "external": true,
      "loc": "net/core/filter.c:84",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589418608,
      "name": "copy_bpf_fprog_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int copy_bpf_fprog_from_user(struct sock_fprog * dst, sockptr_t src, int len)
```

```json
{
  "name": "copy_bpf_fprog_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590146240,
      "name": "copy_bpf_fprog_from_user",
      "external": true,
      "loc": "net/core/filter.c:85",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590146240,
      "name": "copy_bpf_fprog_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int copy_bpf_fprog_from_user(struct sock_fprog * dst, sockptr_t src, int len)
```

```json
{
  "name": "copy_bpf_fprog_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591701168,
      "name": "copy_bpf_fprog_from_user",
      "external": true,
      "loc": "net/core/filter.c:86",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sock_setsockopt",
        "net/packet/af_packet.c:packet_setsockopt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591701168,
      "name": "copy_bpf_fprog_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int copy_bpf_fprog_from_user(struct sock_fprog * dst, sockptr_t src, int len)
```

```json
{
  "name": "copy_bpf_fprog_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593500704,
      "name": "copy_bpf_fprog_from_user",
      "external": true,
      "loc": "net/core/filter.c:88",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/packet/af_packet.c:fanout_set_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593500704,
      "name": "copy_bpf_fprog_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int copy_bpf_fprog_from_user(struct sock_fprog * dst, sockptr_t src, int len)
```

```json
{
  "name": "copy_bpf_fprog_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593972736,
      "name": "copy_bpf_fprog_from_user",
      "external": true,
      "loc": "net/core/filter.c:88",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/packet/af_packet.c:fanout_set_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593972736,
      "name": "copy_bpf_fprog_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int copy_bpf_fprog_from_user(struct sock_fprog * dst, sockptr_t src, int len)
```

```json
{
  "name": "copy_bpf_fprog_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594757632,
      "name": "copy_bpf_fprog_from_user",
      "external": true,
      "loc": "net/core/filter.c:93",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_setsockopt",
        "net/packet/af_packet.c:fanout_set_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594757632,
      "name": "copy_bpf_fprog_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int copy_bpf_fprog_from_user(struct sock_fprog * dst, sockptr_t src, int len)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
