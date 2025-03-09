# Function: <code>tcp_ao_do_lookup</code>

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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct tcp_ao_key * tcp_ao_do_lookup(const struct sock * sk, int l3index, const union tcp_ao_addr * addr, int family, int sndid, int rcvid)
```

```json
{
  "name": "tcp_ao_do_lookup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595982902,
      "name": "tcp_ao_do_lookup",
      "external": true,
      "loc": "net/ipv4/tcp_ao.c:217",
      "file": "net/ipv4/tcp_ao.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ao.c:tcp_ao_prepare_reset",
        "net/ipv4/tcp_ao.c:tcp_v4_ao_lookup",
        "net/ipv4/tcp_ao.c:tcp_v4_ao_lookup_rsk"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_parse_md5_keys",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ipv6.c:tcp_v6_parse_md5_keys",
        "net/ipv6/tcp_ao.c:tcp_v6_ao_lookup_rsk",
        "net/ipv6/tcp_ao.c:tcp_v6_ao_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595975360,
      "name": "tcp_ao_do_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct tcp_ao_key * tcp_ao_do_lookup(const struct sock * sk, int l3index, const union tcp_ao_addr * addr, int family, int sndid, int rcvid)
```
</details>
</li>
</ul>
