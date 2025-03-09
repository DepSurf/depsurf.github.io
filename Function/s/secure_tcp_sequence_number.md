# Function: <code>secure_tcp_sequence_number</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
__u32 secure_tcp_sequence_number(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport)
```

```json
{
  "name": "secure_tcp_sequence_number",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586256048,
      "name": "secure_tcp_sequence_number",
      "external": true,
      "loc": "net/core/secure_seq.c:89",
      "file": "net/core/secure_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_init_sequence",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586256048,
      "name": "secure_tcp_sequence_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
__u32 secure_tcp_sequence_number(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport)
```

```json
{
  "name": "secure_tcp_sequence_number",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586680304,
      "name": "secure_tcp_sequence_number",
      "external": true,
      "loc": "net/core/secure_seq.c:89",
      "file": "net/core/secure_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586680304,
      "name": "secure_tcp_sequence_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
u32 secure_tcp_sequence_number(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 * tsoff)
```

```json
{
  "name": "secure_tcp_sequence_number",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586864944,
      "name": "secure_tcp_sequence_number",
      "external": true,
      "loc": "net/core/secure_seq.c:91",
      "file": "net/core/secure_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586864944,
      "name": "secure_tcp_sequence_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 * tsoff</code>
</li>
<li>
<b>Return type changed. </b>
<code>__u32</code> ➡️ <code>u32</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
u32 secure_tcp_sequence_number(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 * tsoff)
```
</details>
</li>
</ul>
