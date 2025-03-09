# Function: <code>do_shrink_slab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580550629,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:266",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580641717,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:280",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580708712,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:307",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580743429,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:308",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580830501,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:312",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580967679,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:360",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:452",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581043264,
      "name": "do_shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 690
    },
    {
      "addr": 18446744071581072390,
      "name": "do_shrink_slab.cold.61",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:464",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581107328,
      "name": "do_shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
    },
    {
      "addr": 18446744071581135785,
      "name": "do_shrink_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:462",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581164320,
      "name": "do_shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
    },
    {
      "addr": 18446744071581193529,
      "name": "do_shrink_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:419",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/vmscan.c:shrink_slab_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581355664,
      "name": "do_shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
    },
    {
      "addr": 18446744071581379994,
      "name": "do_shrink_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:412",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/vmscan.c:shrink_slab_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581399056,
      "name": "do_shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 571
    },
    {
      "addr": 18446744071591325292,
      "name": "do_shrink_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581414640,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:646",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/vmscan.c:shrink_slab_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581414640,
      "name": "do_shrink_slab",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:692",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/vmscan.c:shrink_slab_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581665216,
      "name": "do_shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    },
    {
      "addr": 18446744071592191533,
      "name": "do_shrink_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:704",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/vmscan.c:shrink_slab_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582040128,
      "name": "do_shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 787
    },
    {
      "addr": 18446744071593967454,
      "name": "do_shrink_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:781",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/vmscan.c:shrink_slab_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582483216,
      "name": "do_shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 773
    },
    {
      "addr": 18446744071596026098,
      "name": "do_shrink_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:834",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/vmscan.c:shrink_slab_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582696976,
      "name": "do_shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
    },
    {
      "addr": 18446744071596548275,
      "name": "do_shrink_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/shrinker.c:369",
      "file": "mm/shrinker.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shrinker.c:shrink_slab",
        "mm/shrinker.c:shrink_slab_memcg",
        "mm/shrinker.c:shrink_slab_memcg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582924480,
      "name": "do_shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 987
    },
    {
      "addr": 18446744071597452714,
      "name": "do_shrink_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492547008,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:462",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492547008,
      "name": "do_shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
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
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226408480,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:462",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226408480,
      "name": "do_shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1028
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
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285843952,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:462",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285843952,
      "name": "do_shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
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
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272591160,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:462",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272591160,
      "name": "do_shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:462",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581133168,
      "name": "do_shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
    },
    {
      "addr": 18446744071581162377,
      "name": "do_shrink_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:462",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581080112,
      "name": "do_shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
    },
    {
      "addr": 18446744071581109229,
      "name": "do_shrink_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:462",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581124368,
      "name": "do_shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
    },
    {
      "addr": 18446744071581153577,
      "name": "do_shrink_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```

```json
{
  "name": "do_shrink_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_shrink_slab",
      "external": false,
      "loc": "mm/vmscan.c:462",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581186816,
      "name": "do_shrink_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 723
    },
    {
      "addr": 18446744071581216343,
      "name": "do_shrink_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control * shrinkctl, struct shrinker * shrinker, int priority)
```
</details>
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
