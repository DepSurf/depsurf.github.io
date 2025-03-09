# Function: <code>__tcp_ao_key_cmp</code>

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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int __tcp_ao_key_cmp(const struct tcp_ao_key * key, int l3index, const union tcp_ao_addr * addr, u8 prefixlen, int family, int sndid, int rcvid)
```

```json
{
  "name": "__tcp_ao_key_cmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcp_ao_key_cmp",
      "external": false,
      "loc": "net/ipv4/tcp_ao.c:139",
      "file": "net/ipv4/tcp_ao.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ao.c:__tcp_ao_do_lookup",
        "net/ipv4/tcp_ao.c:__tcp_ao_do_lookup",
        "net/ipv4/tcp_ao.c:tcp_ao_key_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595968064,
      "name": "__tcp_ao_key_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
    },
    {
      "addr": 18446744071597808217,
      "name": "__tcp_ao_key_cmp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int __tcp_ao_key_cmp(const struct tcp_ao_key * key, int l3index, const union tcp_ao_addr * addr, u8 prefixlen, int family, int sndid, int rcvid)
```
</details>
</li>
</ul>
