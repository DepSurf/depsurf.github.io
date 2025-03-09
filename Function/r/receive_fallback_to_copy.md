# Function: <code>receive_fallback_to_copy</code>

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
int receive_fallback_to_copy(struct sock * sk, struct tcp_zerocopy_receive * zc, int inq)
```

```json
{
  "name": "receive_fallback_to_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590079392,
      "name": "receive_fallback_to_copy",
      "external": false,
      "loc": "net/ipv4/tcp.c:1844",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590079392,
      "name": "receive_fallback_to_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int receive_fallback_to_copy(struct sock * sk, struct tcp_zerocopy_receive * zc, int inq, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "receive_fallback_to_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589993824,
      "name": "receive_fallback_to_copy",
      "external": false,
      "loc": "net/ipv4/tcp.c:1860",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589993824,
      "name": "receive_fallback_to_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
int receive_fallback_to_copy(struct sock * sk, struct tcp_zerocopy_receive * zc, int inq, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "receive_fallback_to_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590763328,
      "name": "receive_fallback_to_copy",
      "external": false,
      "loc": "net/ipv4/tcp.c:1862",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590763328,
      "name": "receive_fallback_to_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
int receive_fallback_to_copy(struct sock * sk, struct tcp_zerocopy_receive * zc, int inq, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "receive_fallback_to_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592395984,
      "name": "receive_fallback_to_copy",
      "external": false,
      "loc": "net/ipv4/tcp.c:1889",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592395984,
      "name": "receive_fallback_to_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
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
int receive_fallback_to_copy(struct sock * sk, struct tcp_zerocopy_receive * zc, int inq, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "receive_fallback_to_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594247120,
      "name": "receive_fallback_to_copy",
      "external": false,
      "loc": "net/ipv4/tcp.c:1989",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594247120,
      "name": "receive_fallback_to_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
int receive_fallback_to_copy(struct sock * sk, struct tcp_zerocopy_receive * zc, int inq, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "receive_fallback_to_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594633264,
      "name": "receive_fallback_to_copy",
      "external": false,
      "loc": "net/ipv4/tcp.c:1845",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594633264,
      "name": "receive_fallback_to_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
int receive_fallback_to_copy(struct sock * sk, struct tcp_zerocopy_receive * zc, int inq, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "receive_fallback_to_copy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595436416,
      "name": "receive_fallback_to_copy",
      "external": false,
      "loc": "net/ipv4/tcp.c:1857",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_zerocopy_receive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595436416,
      "name": "receive_fallback_to_copy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
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
int receive_fallback_to_copy(struct sock * sk, struct tcp_zerocopy_receive * zc, int inq)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct scm_timestamping_internal * tss</code>
</li>
</ul>
</details>
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
