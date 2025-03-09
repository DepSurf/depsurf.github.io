# Function: <code>tcp_v6_ao_calc_key</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int tcp_v6_ao_calc_key(struct tcp_ao_key * mkt, u8 * key, const struct in6_addr * saddr, const struct in6_addr * daddr, __be16 sport, __be16 dport, __be32 sisn, __be32 disn)
```

```json
{
  "name": "tcp_v6_ao_calc_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596623664,
      "name": "tcp_v6_ao_calc_key",
      "external": false,
      "loc": "net/ipv6/tcp_ao.c:16",
      "file": "net/ipv6/tcp_ao.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ao.c:tcp_v6_ao_synack_hash",
        "net/ipv6/tcp_ao.c:tcp_v6_ao_calc_key_sk",
        "net/ipv6/tcp_ao.c:tcp_v6_ao_calc_key_sk",
        "net/ipv6/tcp_ao.c:tcp_v6_ao_calc_key_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596623664,
      "name": "tcp_v6_ao_calc_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int tcp_v6_ao_calc_key(struct tcp_ao_key * mkt, u8 * key, const struct in6_addr * saddr, const struct in6_addr * daddr, __be16 sport, __be16 dport, __be32 sisn, __be32 disn)
```
</details>
</li>
</ul>
