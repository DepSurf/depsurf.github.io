# Function: <code>icmpv6_global_allow</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587947086,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:182",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmp6_send"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588482776,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:182",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmp6_send"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588845966,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:182",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmp6_send"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589069414,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:184",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmp6_send"
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
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589526522,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:179",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send"
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
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589750602,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:179",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool icmpv6_global_allow(struct net * net, int type)
```

```json
{
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590764608,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:179",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590764608,
      "name": "icmpv6_global_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
bool icmpv6_global_allow(struct net * net, int type)
```

```json
{
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590823952,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:185",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590823952,
      "name": "icmpv6_global_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool icmpv6_global_allow(struct net * net, int type)
```

```json
{
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590751088,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:185",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590751088,
      "name": "icmpv6_global_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool icmpv6_global_allow(struct net * net, int type)
```

```json
{
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591568000,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:186",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591568000,
      "name": "icmpv6_global_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593264256,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:178",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
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
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595166737,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:178",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
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
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595561580,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:178",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
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
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596404298,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:178",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
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
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503445168,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:179",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send"
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
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236103560,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:179",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send"
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
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297228688,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:179",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send"
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
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279431428,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:179",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send"
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
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589354970,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:179",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send"
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
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589079962,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:179",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send"
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
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589791834,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:179",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send"
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
  "name": "icmpv6_global_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589842554,
      "name": "icmpv6_global_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:179",
      "file": "net/ipv6/icmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send",
        "net/ipv6/icmp.c:icmp6_send"
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
bool icmpv6_global_allow(struct net * net, int type)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool icmpv6_global_allow(struct net * net, int type)
```
</details>
</li>
</ul>
