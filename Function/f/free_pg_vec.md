# Function: <code>free_pg_vec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void free_pg_vec(void * * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586489808,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/netlink/af_netlink.c:322",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netlink/af_netlink.c:__netlink_set_ring",
        "net/netlink/af_netlink.c:netlink_setsockopt",
        "net/netlink/af_netlink.c:netlink_setsockopt"
      ]
    },
    {
      "addr": 18446744071587247056,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:3993",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586489808,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071587247056,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587710976,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4086",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587710976,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587925488,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4059",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587925488,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588083104,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4132",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588083104,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588627728,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4131",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588627728,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588993680,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4136",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588993680,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589217280,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4165",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589217280,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589671888,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4198",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589671888,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589896128,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4217",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589896128,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590925424,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4228",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590925424,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590989408,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4224",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590989408,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590919888,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4238",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590919888,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591755712,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4239",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591755712,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593462784,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4294",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593462784,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595379840,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4293",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595379840,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595776880,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4314",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595776880,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596627168,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4315",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596627168,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503619464,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4217",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503619464,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236263404,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4217",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236263404,
      "name": "free_pg_vec",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297434464,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4217",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297434464,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279570348,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4217",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279570348,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589500496,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4217",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589500496,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589226560,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4217",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589226560,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589941760,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4217",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589941760,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void free_pg_vec(struct pgv * pg_vec, unsigned int order, unsigned int len)
```

```json
{
  "name": "free_pg_vec",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589991888,
      "name": "free_pg_vec",
      "external": false,
      "loc": "net/packet/af_packet.c:4217",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_set_ring",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589991888,
      "name": "free_pg_vec",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void * * pg_vec</code> ➡️ <code>struct pgv * pg_vec</code>
</li>
</ul>
</details>
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
