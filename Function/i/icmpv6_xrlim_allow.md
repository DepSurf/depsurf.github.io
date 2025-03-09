# Function: <code>icmpv6_xrlim_allow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587134038,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:173",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587585767,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:173",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587790140,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:174",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587947417,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:196",
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
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588483131,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:196",
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
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588846813,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:196",
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
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589070227,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:198",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589522112,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:193",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589522112,
      "name": "icmpv6_xrlim_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589746192,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:193",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589746192,
      "name": "icmpv6_xrlim_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590764064,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:193",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590764064,
      "name": "icmpv6_xrlim_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590823408,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:199",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590823408,
      "name": "icmpv6_xrlim_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590750544,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:199",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590750544,
      "name": "icmpv6_xrlim_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:200",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591567440,
      "name": "icmpv6_xrlim_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    },
    {
      "addr": 18446744071592741154,
      "name": "icmpv6_xrlim_allow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:192",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593259152,
      "name": "icmpv6_xrlim_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    },
    {
      "addr": 18446744071594627851,
      "name": "icmpv6_xrlim_allow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:192",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595160288,
      "name": "icmpv6_xrlim_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    },
    {
      "addr": 18446744071596361597,
      "name": "icmpv6_xrlim_allow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:193",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595555552,
      "name": "icmpv6_xrlim_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071596890112,
      "name": "icmpv6_xrlim_allow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:193",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596398256,
      "name": "icmpv6_xrlim_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071597814491,
      "name": "icmpv6_xrlim_allow.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503441496,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:193",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503441496,
      "name": "icmpv6_xrlim_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236099140,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:193",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236099140,
      "name": "icmpv6_xrlim_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
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
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297224080,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:193",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297224080,
      "name": "icmpv6_xrlim_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279427624,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:193",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279427624,
      "name": "icmpv6_xrlim_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    }
  ]
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
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589350560,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:193",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589350560,
      "name": "icmpv6_xrlim_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589075552,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:193",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589075552,
      "name": "icmpv6_xrlim_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589787424,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:193",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589787424,
      "name": "icmpv6_xrlim_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```

```json
{
  "name": "icmpv6_xrlim_allow",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589838160,
      "name": "icmpv6_xrlim_allow",
      "external": false,
      "loc": "net/ipv6/icmp.c:193",
      "file": "net/ipv6/icmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/icmp.c:icmpv6_echo_reply",
        "net/ipv6/icmp.c:icmp6_send"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589838160,
      "name": "icmpv6_xrlim_allow",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool icmpv6_xrlim_allow(struct sock * sk, u8 type, struct flowi6 * fl6)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
