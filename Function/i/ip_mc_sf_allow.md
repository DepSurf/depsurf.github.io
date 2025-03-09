# Function: <code>ip_mc_sf_allow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586813920,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2497",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:udp_v4_early_demux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586813920,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587263344,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2508",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587263344,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587464192,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2546",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587464192,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587600432,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2560",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587600432,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588124448,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2586",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588124448,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588479344,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2612",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588479344,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588673104,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2628",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588673104,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589086432,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2624",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589086432,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589310592,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2624",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589310592,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590287792,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2614",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/udp.c:__udp4_lib_mcast_demux_lookup",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590287792,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590340672,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2614",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/udp.c:__udp4_lib_mcast_demux_lookup",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590340672,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590256528,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2622",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590256528,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591040816,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2628",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591040816,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592688880,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2637",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592688880,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594557792,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2641",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594557792,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int ip_mc_sf_allow(const struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594949520,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2642",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594949520,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int ip_mc_sf_allow(const struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595761872,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2644",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_v4_input",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_mcast_deliver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595761872,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502946712,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2624",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502946712,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235636836,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2624",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235636836,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296621776,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2624",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296621776,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279031800,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2624",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279031800,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588916768,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2624",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588916768,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588628704,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2624",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588628704,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589353152,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2624",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589353152,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int ip_mc_sf_allow(struct sock * sk, __be32 loc_addr, __be32 rmt_addr, int dif, int sdif)
```

```json
{
  "name": "ip_mc_sf_allow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589395536,
      "name": "ip_mc_sf_allow",
      "external": true,
      "loc": "net/ipv4/igmp.c:2624",
      "file": "net/ipv4/igmp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/raw.c:raw_local_deliver",
        "net/ipv4/udp.c:udp_v4_early_demux",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589395536,
      "name": "ip_mc_sf_allow",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int sdif</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sock * sk</code> ➡️ <code>const struct sock * sk</code>
</li>
</ul>
</details>
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
