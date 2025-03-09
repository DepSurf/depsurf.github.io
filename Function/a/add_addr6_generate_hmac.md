# Function: <code>add_addr6_generate_hmac</code>

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
u64 add_addr6_generate_hmac(u64 key1, u64 key2, u8 addr_id, struct in6_addr * addr)
```

```json
{
  "name": "add_addr6_generate_hmac",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591105382,
      "name": "add_addr6_generate_hmac",
      "external": false,
      "loc": "net/mptcp/options.c:558",
      "file": "net/mptcp/options.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:mptcp_incoming_options"
      ],
      "caller_func": [
        "net/mptcp/options.c:mptcp_established_options_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591102784,
      "name": "add_addr6_generate_hmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 add_addr6_generate_hmac(u64 key1, u64 key2, u8 addr_id, struct in6_addr * addr, u16 port)
```

```json
{
  "name": "add_addr6_generate_hmac",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591187446,
      "name": "add_addr6_generate_hmac",
      "external": false,
      "loc": "net/mptcp/options.c:574",
      "file": "net/mptcp/options.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mptcp/options.c:mptcp_incoming_options"
      ],
      "caller_func": [
        "net/mptcp/options.c:mptcp_established_options_add_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591182896,
      "name": "add_addr6_generate_hmac",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
u64 add_addr6_generate_hmac(u64 key1, u64 key2, u8 addr_id, struct in6_addr * addr)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u16 port</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
u64 add_addr6_generate_hmac(u64 key1, u64 key2, u8 addr_id, struct in6_addr * addr, u16 port)
```
</details>
</li>
</ul>
