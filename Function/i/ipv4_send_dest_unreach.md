# Function: <code>ipv4_send_dest_unreach</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv4_send_dest_unreach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588748312,
      "name": "ipv4_send_dest_unreach",
      "external": false,
      "loc": "net/ipv4/route.c:1195",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure"
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
  "name": "ipv4_send_dest_unreach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588972264,
      "name": "ipv4_send_dest_unreach",
      "external": false,
      "loc": "net/ipv4/route.c:1197",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ipv4_send_dest_unreach(struct sk_buff * skb)
```

```json
{
  "name": "ipv4_send_dest_unreach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589928304,
      "name": "ipv4_send_dest_unreach",
      "external": false,
      "loc": "net/ipv4/route.c:1201",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589928304,
      "name": "ipv4_send_dest_unreach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
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
void ipv4_send_dest_unreach(struct sk_buff * skb)
```

```json
{
  "name": "ipv4_send_dest_unreach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589968896,
      "name": "ipv4_send_dest_unreach",
      "external": false,
      "loc": "net/ipv4/route.c:1207",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589968896,
      "name": "ipv4_send_dest_unreach",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void ipv4_send_dest_unreach(struct sk_buff * skb)
```

```json
{
  "name": "ipv4_send_dest_unreach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589882992,
      "name": "ipv4_send_dest_unreach",
      "external": false,
      "loc": "net/ipv4/route.c:1193",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589882992,
      "name": "ipv4_send_dest_unreach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
void ipv4_send_dest_unreach(struct sk_buff * skb)
```

```json
{
  "name": "ipv4_send_dest_unreach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590646832,
      "name": "ipv4_send_dest_unreach",
      "external": false,
      "loc": "net/ipv4/route.c:1208",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590646832,
      "name": "ipv4_send_dest_unreach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
void ipv4_send_dest_unreach(struct sk_buff * skb)
```

```json
{
  "name": "ipv4_send_dest_unreach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592271392,
      "name": "ipv4_send_dest_unreach",
      "external": false,
      "loc": "net/ipv4/route.c:1214",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592271392,
      "name": "ipv4_send_dest_unreach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
void ipv4_send_dest_unreach(struct sk_buff * skb)
```

```json
{
  "name": "ipv4_send_dest_unreach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594106304,
      "name": "ipv4_send_dest_unreach",
      "external": false,
      "loc": "net/ipv4/route.c:1214",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594106304,
      "name": "ipv4_send_dest_unreach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
void ipv4_send_dest_unreach(struct sk_buff * skb)
```

```json
{
  "name": "ipv4_send_dest_unreach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594493184,
      "name": "ipv4_send_dest_unreach",
      "external": false,
      "loc": "net/ipv4/route.c:1214",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594493184,
      "name": "ipv4_send_dest_unreach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
void ipv4_send_dest_unreach(struct sk_buff * skb)
```

```json
{
  "name": "ipv4_send_dest_unreach",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595296080,
      "name": "ipv4_send_dest_unreach",
      "external": false,
      "loc": "net/ipv4/route.c:1214",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ipv4_link_failure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595296080,
      "name": "ipv4_send_dest_unreach",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ipv4_send_dest_unreach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502575100,
      "name": "ipv4_send_dest_unreach",
      "external": false,
      "loc": "net/ipv4/route.c:1197",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure"
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
  "name": "ipv4_send_dest_unreach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235281920,
      "name": "ipv4_send_dest_unreach",
      "external": false,
      "loc": "net/ipv4/route.c:1197",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure"
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
  "name": "ipv4_send_dest_unreach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296162072,
      "name": "ipv4_send_dest_unreach",
      "external": false,
      "loc": "net/ipv4/route.c:1197",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure"
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
  "name": "ipv4_send_dest_unreach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278733438,
      "name": "ipv4_send_dest_unreach",
      "external": false,
      "loc": "net/ipv4/route.c:1197",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure"
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
  "name": "ipv4_send_dest_unreach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588578648,
      "name": "ipv4_send_dest_unreach",
      "external": false,
      "loc": "net/ipv4/route.c:1197",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure"
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
  "name": "ipv4_send_dest_unreach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588290632,
      "name": "ipv4_send_dest_unreach",
      "external": false,
      "loc": "net/ipv4/route.c:1197",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure"
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
  "name": "ipv4_send_dest_unreach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589014824,
      "name": "ipv4_send_dest_unreach",
      "external": false,
      "loc": "net/ipv4/route.c:1197",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure"
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
  "name": "ipv4_send_dest_unreach",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589053418,
      "name": "ipv4_send_dest_unreach",
      "external": false,
      "loc": "net/ipv4/route.c:1197",
      "file": "net/ipv4/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ipv4_link_failure"
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
void ipv4_send_dest_unreach(struct sk_buff * skb)
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
