# Function: <code>ip_copy_addrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586571480,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:371",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:ip_queue_xmit",
        "net/ipv4/ip_output.c:__ip_make_skb"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587018000,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:369",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:ip_queue_xmit"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587213680,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:413",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:ip_queue_xmit"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr * iph, const struct flowi4 * fl4)
```

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587333184,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:417",
      "file": "net/ipv4/ip_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:ip_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587333184,
      "name": "ip_copy_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr * iph, const struct flowi4 * fl4)
```

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587853728,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:417",
      "file": "net/ipv4/ip_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:ip_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587853728,
      "name": "ip_copy_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr * iph, const struct flowi4 * fl4)
```

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588198528,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:417",
      "file": "net/ipv4/ip_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:ip_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588198528,
      "name": "ip_copy_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr * iph, const struct flowi4 * fl4)
```

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588384160,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:417",
      "file": "net/ipv4/ip_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588384160,
      "name": "ip_copy_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr * iph, const struct flowi4 * fl4)
```

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588785648,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:444",
      "file": "net/ipv4/ip_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588785648,
      "name": "ip_copy_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr * iph, const struct flowi4 * fl4)
```

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589009248,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:444",
      "file": "net/ipv4/ip_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589009248,
      "name": "ip_copy_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589982079,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:443",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590022847,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:444",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589937072,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:445",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590704094,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:443",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592332635,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:443",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
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
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594170315,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:443",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
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
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594557216,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:445",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
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
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595359840,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:446",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr * iph, const struct flowi4 * fl4)
```

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502615096,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:444",
      "file": "net/ipv4/ip_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502615096,
      "name": "ip_copy_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr * iph, const struct flowi4 * fl4)
```

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235321464,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:444",
      "file": "net/ipv4/ip_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235321464,
      "name": "ip_copy_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr * iph, const struct flowi4 * fl4)
```

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296209744,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:444",
      "file": "net/ipv4/ip_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296209744,
      "name": "ip_copy_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278777064,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:444",
      "file": "net/ipv4/ip_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr * iph, const struct flowi4 * fl4)
```

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588615632,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:444",
      "file": "net/ipv4/ip_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588615632,
      "name": "ip_copy_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr * iph, const struct flowi4 * fl4)
```

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588327616,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:444",
      "file": "net/ipv4/ip_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588327616,
      "name": "ip_copy_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr * iph, const struct flowi4 * fl4)
```

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589051808,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:444",
      "file": "net/ipv4/ip_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589051808,
      "name": "ip_copy_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void ip_copy_addrs(struct iphdr * iph, const struct flowi4 * fl4)
```

```json
{
  "name": "ip_copy_addrs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589090992,
      "name": "ip_copy_addrs",
      "external": false,
      "loc": "net/ipv4/ip_output.c:444",
      "file": "net/ipv4/ip_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/ip_output.c:__ip_make_skb",
        "net/ipv4/ip_output.c:__ip_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589090992,
      "name": "ip_copy_addrs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void ip_copy_addrs(struct iphdr * iph, const struct flowi4 * fl4)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void ip_copy_addrs(struct iphdr * iph, const struct flowi4 * fl4)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void ip_copy_addrs(struct iphdr * iph, const struct flowi4 * fl4)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
