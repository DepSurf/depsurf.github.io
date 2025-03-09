# Function: <code>ppp_send_frame</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585101996,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1238",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process"
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
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585495628,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1451",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_xmit_process"
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
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585683244,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1482",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
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
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585770299,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1496",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
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
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586206509,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1523",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
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
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586465757,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1506",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
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
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586613469,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1506",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
```

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1502",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586865744,
      "name": "ppp_send_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1492
    },
    {
      "addr": 18446744071586871972,
      "name": "ppp_send_frame.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
```

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1502",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587011744,
      "name": "ppp_send_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1492
    },
    {
      "addr": 18446744071587018004,
      "name": "ppp_send_frame.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
```

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1590",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587843632,
      "name": "ppp_send_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1169
    },
    {
      "addr": 18446744071587846950,
      "name": "ppp_send_frame.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
```

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1700",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587902816,
      "name": "ppp_send_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1169
    },
    {
      "addr": 18446744071591533563,
      "name": "ppp_send_frame.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
```

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1733",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587779200,
      "name": "ppp_send_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1155
    },
    {
      "addr": 18446744071591475717,
      "name": "ppp_send_frame.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
```

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1738",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588375616,
      "name": "ppp_send_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1107
    },
    {
      "addr": 18446744071592546406,
      "name": "ppp_send_frame.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
```

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1739",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589769216,
      "name": "ppp_send_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1115
    },
    {
      "addr": 18446744071594425744,
      "name": "ppp_send_frame.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
```

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591419456,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1739",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591419456,
      "name": "ppp_send_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
```

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591834752,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1739",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591834752,
      "name": "ppp_send_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
```

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592582816,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1739",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592582816,
      "name": "ppp_send_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1210
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
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
```

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500123576,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1502",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500123576,
      "name": "ppp_send_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1436
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
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
```

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232623016,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1502",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232623016,
      "name": "ppp_send_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1616
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
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
```

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293345632,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1502",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293345632,
      "name": "ppp_send_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1904
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
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
```

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277079020,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1502",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277079020,
      "name": "ppp_send_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1330
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
```

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1502",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586768768,
      "name": "ppp_send_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1492
    },
    {
      "addr": 18446744071586775028,
      "name": "ppp_send_frame.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
```

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1502",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586674000,
      "name": "ppp_send_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1492
    },
    {
      "addr": 18446744071586680260,
      "name": "ppp_send_frame.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
```

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1502",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586966304,
      "name": "ppp_send_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1492
    },
    {
      "addr": 18446744071586972564,
      "name": "ppp_send_frame.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
```

```json
{
  "name": "ppp_send_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ppp_send_frame",
      "external": false,
      "loc": "drivers/net/ppp/ppp_generic.c:1502",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:__ppp_xmit_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587073456,
      "name": "ppp_send_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1492
    },
    {
      "addr": 18446744071587079751,
      "name": "ppp_send_frame.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void ppp_send_frame(struct ppp * ppp, struct sk_buff * skb)
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
