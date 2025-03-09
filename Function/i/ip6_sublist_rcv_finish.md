# Function: <code>ip6_sublist_rcv_finish</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588911015,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:79",
      "file": "net/ipv6/ip6_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv"
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
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589352987,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:79",
      "file": "net/ipv6/ip6_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void ip6_sublist_rcv_finish(struct list_head * head)
```

```json
{
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589575008,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:79",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589575008,
      "name": "ip6_sublist_rcv_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void ip6_sublist_rcv_finish(struct list_head * head)
```

```json
{
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590580016,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:79",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590580016,
      "name": "ip6_sublist_rcv_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void ip6_sublist_rcv_finish(struct list_head * head)
```

```json
{
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590640480,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:79",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590640480,
      "name": "ip6_sublist_rcv_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void ip6_sublist_rcv_finish(struct list_head * head)
```

```json
{
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590569792,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:79",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590569792,
      "name": "ip6_sublist_rcv_finish",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void ip6_sublist_rcv_finish(struct list_head * head)
```

```json
{
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591381584,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:79",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591381584,
      "name": "ip6_sublist_rcv_finish",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void ip6_sublist_rcv_finish(struct list_head * head)
```

```json
{
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593056304,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:82",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593056304,
      "name": "ip6_sublist_rcv_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void ip6_sublist_rcv_finish(struct list_head * head)
```

```json
{
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594948944,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:82",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594948944,
      "name": "ip6_sublist_rcv_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void ip6_sublist_rcv_finish(struct list_head * head)
```

```json
{
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595341584,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:82",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595341584,
      "name": "ip6_sublist_rcv_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void ip6_sublist_rcv_finish(struct list_head * head)
```

```json
{
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596182336,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:82",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596182336,
      "name": "ip6_sublist_rcv_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void ip6_sublist_rcv_finish(struct list_head * head)
```

```json
{
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503250072,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:79",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503250072,
      "name": "ip6_sublist_rcv_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void ip6_sublist_rcv_finish(struct list_head * head)
```

```json
{
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235921936,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:79",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235921936,
      "name": "ip6_sublist_rcv_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void ip6_sublist_rcv_finish(struct list_head * head)
```

```json
{
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296993424,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:79",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296993424,
      "name": "ip6_sublist_rcv_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void ip6_sublist_rcv_finish(struct list_head * head)
```

```json
{
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279278336,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:79",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279278336,
      "name": "ip6_sublist_rcv_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void ip6_sublist_rcv_finish(struct list_head * head)
```

```json
{
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589179376,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:79",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589179376,
      "name": "ip6_sublist_rcv_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void ip6_sublist_rcv_finish(struct list_head * head)
```

```json
{
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588904368,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:79",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588904368,
      "name": "ip6_sublist_rcv_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void ip6_sublist_rcv_finish(struct list_head * head)
```

```json
{
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589616240,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:79",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589616240,
      "name": "ip6_sublist_rcv_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void ip6_sublist_rcv_finish(struct list_head * head)
```

```json
{
  "name": "ip6_sublist_rcv_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589664576,
      "name": "ip6_sublist_rcv_finish",
      "external": false,
      "loc": "net/ipv6/ip6_input.c:79",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_input.c:ip6_sublist_rcv",
        "net/ipv6/ip6_input.c:ip6_sublist_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589664576,
      "name": "ip6_sublist_rcv_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void ip6_sublist_rcv_finish(struct list_head * head)
```
</details>
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
