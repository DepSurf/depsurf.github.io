# Function: <code>compute_score</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586587989,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:171",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586746747,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:339",
      "file": "net/ipv4/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv4/udp.c:__udp4_lib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587117775,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:144",
      "file": "net/ipv6/udp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:__udp6_lib_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587241995,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:96",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int compute_score(struct sock * sk, struct net * net, const short unsigned int hnum, const __be32 daddr, const int dif)
```

```json
{
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587029898,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:173",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587181536,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:394",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ]
    },
    {
      "addr": 18446744071587569213,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:118",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ]
    },
    {
      "addr": 18446744071587705733,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:96",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587181536,
      "name": "compute_score",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071587561024,
      "name": "compute_score.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int compute_score(struct sock * sk, struct net * net, const short unsigned int hnum, const __be32 daddr, const int dif, bool exact_dif)
```

```json
{
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587225935,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:174",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587381696,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:395",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ]
    },
    {
      "addr": 18446744071587773437,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:118",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ]
    },
    {
      "addr": 18446744071587920332,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:96",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587381696,
      "name": "compute_score",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    },
    {
      "addr": 18446744071587765312,
      "name": "compute_score.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int compute_score(struct sock * sk, struct net * net, const short unsigned int hnum, const __be32 daddr, const int dif, bool exact_dif)
```

```json
{
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587358046,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:171",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587516080,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:381",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ]
    },
    {
      "addr": 18446744071587920976,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:129",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ]
    },
    {
      "addr": 18446744071588078246,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:96",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587516080,
      "name": "compute_score",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071587920976,
      "name": "compute_score",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int compute_score(struct sock * sk, struct net * net, const short unsigned int hnum, const __be32 daddr, const int dif, const int sdif, bool exact_dif)
```

```json
{
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587877989,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:171",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588038928,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:378",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ]
    },
    {
      "addr": 18446744071588456192,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:129",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ]
    },
    {
      "addr": 18446744071588622598,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:96",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588038928,
      "name": "compute_score",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    },
    {
      "addr": 18446744071588456192,
      "name": "compute_score",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int compute_score(struct sock * sk, struct net * net, const short unsigned int hnum, const __be32 daddr, const int dif, const int sdif, bool exact_dif)
```

```json
{
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588225251,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:226",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:__inet_lookup_listener",
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588390432,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:366",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_lookup",
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ]
    },
    {
      "addr": 18446744071588817456,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:113",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_lookup",
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ]
    },
    {
      "addr": 18446744071588989195,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:96",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lookup_listener",
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588390432,
      "name": "compute_score",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071588817456,
      "name": "compute_score",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588410980,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:232",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588592880,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:369",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589047550,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:114",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589212740,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:96",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
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
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588814792,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:228",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589004396,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:353",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589497792,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:101",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589666696,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:92",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
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
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589038120,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:228",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589228844,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:353",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589721856,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:101",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589890952,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:92",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589999672,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:229",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590193641,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:356",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590745315,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:101",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590921480,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:92",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590041959,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:232",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590244151,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:357",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590804250,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:101",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590985047,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:94",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589956135,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:232",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590158215,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:357",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590731002,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:101",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590915687,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:94",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590723334,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:232",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590938635,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:357",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591540670,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:102",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591751477,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:94",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592353311,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:196",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592582348,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:357",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593230086,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:103",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593457953,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:94",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594192895,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:312",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594444972,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:364",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595130694,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:117",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595375105,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:92",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int compute_score(struct sock * sk, struct net * net, const short unsigned int hnum, const __be32 daddr, const int dif, const int sdif)
```

```json
{
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594580017,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:312",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594826448,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:366",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ]
    },
    {
      "addr": 18446744071595522160,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:119",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ]
    },
    {
      "addr": 18446744071595772001,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:92",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594826448,
      "name": "compute_score",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071595522160,
      "name": "compute_score",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int compute_score(struct sock * sk, struct net * net, const short unsigned int hnum, const __be32 daddr, const int dif, const int sdif)
```

```json
{
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595383680,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:314",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595637760,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:366",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp4_lib_lookup2",
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ]
    },
    {
      "addr": 18446744071596365520,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:120",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:udp6_lib_lookup2",
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ]
    },
    {
      "addr": 18446744071596620656,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:93",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595637760,
      "name": "compute_score",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071596365520,
      "name": "compute_score",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502647944,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:228",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502844048,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:353",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503409576,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:101",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503613528,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:92",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
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
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235352380,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:228",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 3235556760,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:353",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 3236075032,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:101",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 3236257332,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:92",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
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
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296249008,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:228",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296509392,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:353",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297194800,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:101",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297427376,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:92",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
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
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278788776,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:228",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278959722,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:353",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279406500,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:101",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279564346,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:92",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
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
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588644504,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:228",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588835228,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:353",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589326224,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:101",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589495320,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:92",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
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
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588356488,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:228",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588547164,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:353",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589051216,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:101",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589220312,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:92",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
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
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589080680,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:228",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589271404,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:353",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589763088,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:101",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589936584,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:92",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
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
  "name": "compute_score",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589120312,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/inet_hashtables.c:228",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_hashtables.c:inet_lhash2_lookup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589317233,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv4/udp.c:353",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp4_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589813748,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/udp.c:101",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/udp.c:udp6_lib_lookup2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589986072,
      "name": "compute_score",
      "external": false,
      "loc": "net/ipv6/inet6_hashtables.c:92",
      "file": "net/ipv6/inet6_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup"
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int compute_score(struct sock * sk, struct net * net, const short unsigned int hnum, const __be32 daddr, const int dif)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool exact_dif</code>
</li>
</ul>
</details>
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
<code>const int sdif</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, net, hnum, daddr, dif, exact_dif</code> ➡️ <code>sk, net, hnum, daddr, dif, sdif, exact_dif</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int compute_score(struct sock * sk, struct net * net, const short unsigned int hnum, const __be32 daddr, const int dif, const int sdif, bool exact_dif)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int compute_score(struct sock * sk, struct net * net, const short unsigned int hnum, const __be32 daddr, const int dif, const int sdif)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
