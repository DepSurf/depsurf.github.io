# Function: <code>bpf_skb_vlan_push</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 r1, u64 r2, u64 vlan_tci, u64 r4, u64 r5)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586388640,
      "name": "bpf_skb_vlan_push",
      "external": false,
      "loc": "net/core/filter.c:1509",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586388640,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
u64 bpf_skb_vlan_push(u64 r1, u64 r2, u64 vlan_tci, u64 r4, u64 r5)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586831408,
      "name": "bpf_skb_vlan_push",
      "external": false,
      "loc": "net/core/filter.c:1728",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586831408,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587022480,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:1852",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587022480,
      "name": "bpf_skb_vlan_push",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587150256,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:1896",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587150256,
      "name": "bpf_skb_vlan_push",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587653632,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:1961",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587653632,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587977584,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:2480",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587977584,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588133760,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:2672",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588133760,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588451136,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:2718",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588451136,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588657696,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:2720",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588657696,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589522128,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:2758",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589522128,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589529408,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:3127",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589529408,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589427168,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:3124",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589427168,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590153760,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:3111",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590153760,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591713936,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:3112",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591713936,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593500960,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:3119",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593500960,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593966624,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:3135",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593966624,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594749184,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:3169",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594749184,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502201016,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:2720",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502201016,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234955940,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:2720",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234955940,
      "name": "bpf_skb_vlan_push",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295696960,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:2720",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295696960,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278460604,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:2720",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278460604,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588264432,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:2720",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588264432,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587977248,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:2720",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587977248,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588596256,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:2720",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588596256,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
u64 bpf_skb_vlan_push(u64 skb, u64 vlan_proto, u64 vlan_tci, u64 __ur_1, u64 __ur_2)
```

```json
{
  "name": "bpf_skb_vlan_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588733920,
      "name": "bpf_skb_vlan_push",
      "external": true,
      "loc": "net/core/filter.c:2720",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588733920,
      "name": "bpf_skb_vlan_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 skb</code>
</li>
<li>
<b>Param added. </b>
<code>u64 vlan_proto</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r4</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r5</code>
</li>
</ul>
</details>
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
