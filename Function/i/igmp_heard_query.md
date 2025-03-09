# Function: <code>igmp_heard_query</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586809259,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:881",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_rcv"
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
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587258547,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:878",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_rcv"
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
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587459379,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:893",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_rcv"
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
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587595682,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:893",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_rcv"
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
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588119666,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:921",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_rcv"
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
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588474524,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:921",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_rcv"
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
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588668154,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:917",
      "file": "net/ipv4/igmp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/igmp.c:igmp_rcv"
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
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
```

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589078768,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:933",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589078768,
      "name": "igmp_heard_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1466
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
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
```

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589302928,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:933",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589302928,
      "name": "igmp_heard_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1466
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
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
```

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590281504,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:931",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590281504,
      "name": "igmp_heard_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1615
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
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
```

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590334480,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:931",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590334480,
      "name": "igmp_heard_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1620
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
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
```

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590248960,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:938",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590248960,
      "name": "igmp_heard_query",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
```

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591032896,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:938",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591032896,
      "name": "igmp_heard_query",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
```

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592680688,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:941",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592680688,
      "name": "igmp_heard_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1536
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
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
```

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594545072,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:941",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594545072,
      "name": "igmp_heard_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1530
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
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
```

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594937184,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:942",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594937184,
      "name": "igmp_heard_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1574
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
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
```

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595749424,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:944",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595749424,
      "name": "igmp_heard_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1561
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
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
```

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502936656,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:933",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502936656,
      "name": "igmp_heard_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1700
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
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
```

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235630180,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:933",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235630180,
      "name": "igmp_heard_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1656
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
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
```

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296612048,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:933",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296612048,
      "name": "igmp_heard_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1996
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
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
```

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279026782,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:933",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279026782,
      "name": "igmp_heard_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1274
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
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
```

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588909104,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:933",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588909104,
      "name": "igmp_heard_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1466
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
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
```

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588621040,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:933",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588621040,
      "name": "igmp_heard_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1466
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
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
```

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589345488,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:933",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589345488,
      "name": "igmp_heard_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1466
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
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
```

```json
{
  "name": "igmp_heard_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589387824,
      "name": "igmp_heard_query",
      "external": false,
      "loc": "net/ipv4/igmp.c:933",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/igmp.c:igmp_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589387824,
      "name": "igmp_heard_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1473
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
bool igmp_heard_query(struct in_device * in_dev, struct sk_buff * skb, int len)
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
