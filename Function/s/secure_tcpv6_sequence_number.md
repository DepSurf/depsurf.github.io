# Function: <code>secure_tcpv6_sequence_number</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
__u32 secure_tcpv6_sequence_number(const __be32 * saddr, const __be32 * daddr, __be16 sport, __be16 dport)
```

```json
{
  "name": "secure_tcpv6_sequence_number",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586255248,
      "name": "secure_tcpv6_sequence_number",
      "external": true,
      "loc": "net/core/secure_seq.c:43",
      "file": "net/core/secure_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_sequence",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586255248,
      "name": "secure_tcpv6_sequence_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
__u32 secure_tcpv6_sequence_number(const __be32 * saddr, const __be32 * daddr, __be16 sport, __be16 dport)
```

```json
{
  "name": "secure_tcpv6_sequence_number",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586679504,
      "name": "secure_tcpv6_sequence_number",
      "external": true,
      "loc": "net/core/secure_seq.c:43",
      "file": "net/core/secure_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586679504,
      "name": "secure_tcpv6_sequence_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
u32 secure_tcpv6_sequence_number(const __be32 * saddr, const __be32 * daddr, __be16 sport, __be16 dport, u32 * tsoff)
```

```json
{
  "name": "secure_tcpv6_sequence_number",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586864112,
      "name": "secure_tcpv6_sequence_number",
      "external": true,
      "loc": "net/core/secure_seq.c:44",
      "file": "net/core/secure_seq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_init_sequence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586864112,
      "name": "secure_tcpv6_sequence_number",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
u32 secure_tcpv6_sequence_number(const __be32 * saddr, const __be32 * daddr, __be16 sport, __be16 dport, u32 * tsoff)
```
</details>
</li>
</ul>
