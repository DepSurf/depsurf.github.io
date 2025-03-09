# Function: <code>udp_lib_lport_inuse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, int (*)(const struct sock *, const struct sock *) saddr_comp, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586734160,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:135",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586734160,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, int (*)(const struct sock *, const struct sock *, bool) saddr_comp, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587182000,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:136",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587182000,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, int (*)(const struct sock *, const struct sock *, bool) saddr_comp, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587382176,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:137",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587382176,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587516592,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:148",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587516592,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588039488,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:148",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588039488,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588390864,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:142",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588390864,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588581248,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:144",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588581248,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588992464,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:128",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588992464,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589216896,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:128",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589216896,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590189520,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:131",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590189520,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590238720,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:132",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590238720,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590152912,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:132",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590152912,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:132",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590933328,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
    },
    {
      "addr": 18446744071592722253,
      "name": "udp_lib_lport_inuse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:132",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592575360,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071594608518,
      "name": "udp_lib_lport_inuse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:139",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594437248,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071596343824,
      "name": "udp_lib_lport_inuse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:141",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594827456,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071596872860,
      "name": "udp_lib_lport_inuse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:141",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595638768,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071597796832,
      "name": "udp_lib_lport_inuse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502842176,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:128",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502842176,
      "name": "udp_lib_lport_inuse.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235540000,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:128",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235540000,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296492736,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:128",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296492736,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278949140,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:128",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278949140,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588823280,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:128",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588823280,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588535216,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:128",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588535216,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589259456,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:128",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589259456,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```

```json
{
  "name": "udp_lib_lport_inuse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589300784,
      "name": "udp_lib_lport_inuse",
      "external": false,
      "loc": "net/ipv4/udp.c:128",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_lib_get_port",
        "net/ipv4/udp.c:udp_lib_get_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589300784,
      "name": "udp_lib_lport_inuse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
<code>int (*)(const struct sock *, const struct sock *) saddr_comp</code> ➡️ <code>int (*)(const struct sock *, const struct sock *, bool) saddr_comp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int (*)(const struct sock *, const struct sock *, bool) saddr_comp</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, num, hslot, bitmap, sk, saddr_comp, log</code> ➡️ <code>net, num, hslot, bitmap, sk, log</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int udp_lib_lport_inuse(struct net * net, __u16 num, const struct udp_hslot * hslot, long unsigned int * bitmap, struct sock * sk, unsigned int log)
```
</details>
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
