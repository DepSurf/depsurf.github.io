# Function: <code>inet_frag_maybe_warn_overflow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void inet_frag_maybe_warn_overflow(struct inet_frag_queue * q, const char * prefix)
```

```json
{
  "name": "inet_frag_maybe_warn_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586846608,
      "name": "inet_frag_maybe_warn_overflow",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:437",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586846608,
      "name": "inet_frag_maybe_warn_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void inet_frag_maybe_warn_overflow(struct inet_frag_queue * q, const char * prefix)
```

```json
{
  "name": "inet_frag_maybe_warn_overflow",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587298912,
      "name": "inet_frag_maybe_warn_overflow",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:429",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587298912,
      "name": "inet_frag_maybe_warn_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void inet_frag_maybe_warn_overflow(struct inet_frag_queue * q, const char * prefix)
```

```json
{
  "name": "inet_frag_maybe_warn_overflow",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587500976,
      "name": "inet_frag_maybe_warn_overflow",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:429",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587500976,
      "name": "inet_frag_maybe_warn_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void inet_frag_maybe_warn_overflow(struct inet_frag_queue * q, const char * prefix)
```

```json
{
  "name": "inet_frag_maybe_warn_overflow",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587638304,
      "name": "inet_frag_maybe_warn_overflow",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:427",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587638304,
      "name": "inet_frag_maybe_warn_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void inet_frag_maybe_warn_overflow(struct inet_frag_queue * q, const char * prefix)
```

```json
{
  "name": "inet_frag_maybe_warn_overflow",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588162896,
      "name": "inet_frag_maybe_warn_overflow",
      "external": true,
      "loc": "net/ipv4/inet_fragment.c:430",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_fragment.c:ip_defrag",
        "net/ipv6/reassembly.c:ipv6_frag_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588162896,
      "name": "inet_frag_maybe_warn_overflow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void inet_frag_maybe_warn_overflow(struct inet_frag_queue * q, const char * prefix)
```
</details>
</li>
</ul>
