# Function: <code>packet_do_bind</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587253552,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:2916",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_bind_spkt",
        "net/packet/af_packet.c:packet_bind"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind_spkt",
        "net/packet/af_packet.c:packet_bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587253552,
      "name": "packet_do_bind.part.61",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587715634,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3030",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587714896,
      "name": "packet_do_bind.part.63",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587929874,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:2991",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587929120,
      "name": "packet_do_bind.part.66",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588085248,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3057",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588085248,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 581
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588629728,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3049",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588629728,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 627
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589006032,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3029",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589006032,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589224128,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3041",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589224128,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589681408,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3067",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589681408,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589906896,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3086",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589906896,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590941696,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3097",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590941696,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591005952,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3114",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591005952,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590937840,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3126",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590937840,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 675
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591773696,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3131",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591773696,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 667
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593471152,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3185",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593471152,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595389104,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3185",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595389104,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 813
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595785696,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3197",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595785696,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596635712,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3193",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596635712,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503633648,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3086",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503633648,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236264984,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3086",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236264984,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297439824,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3086",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297439824,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279579926,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3086",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279579926,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589511264,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3086",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589511264,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589237328,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3086",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589237328,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589952528,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3086",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589952528,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
```

```json
{
  "name": "packet_do_bind",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589993312,
      "name": "packet_do_bind",
      "external": false,
      "loc": "net/packet/af_packet.c:3086",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind",
        "net/packet/af_packet.c:packet_bind_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589993312,
      "name": "packet_do_bind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
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
int packet_do_bind(struct sock * sk, const char * name, int ifindex, __be16 proto)
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
