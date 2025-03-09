# Function: <code>mem_cgroup_oom_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580939610,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1575",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
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
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581086424,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1440",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
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
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581161426,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1411",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
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
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581209054,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1403",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
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
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581339422,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1417",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
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
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581486847,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1374",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581566480,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1555",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566480,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581677952,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1756",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677952,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581749888,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1772",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581749888,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581970192,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1638",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581970192,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582018816,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1827",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582018816,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582045056,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1650",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582045056,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1702",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582351824,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
    },
    {
      "addr": 18446744071592225022,
      "name": "mem_cgroup_oom_trylock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1719",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582847792,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071594004098,
      "name": "mem_cgroup_oom_trylock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1779",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583393648,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071596048783,
      "name": "mem_cgroup_oom_trylock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1813",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583612928,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071596571257,
      "name": "mem_cgroup_oom_trylock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1885",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583807824,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
    },
    {
      "addr": 18446744071597475746,
      "name": "mem_cgroup_oom_trylock.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493203656,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1772",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493203656,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226834300,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1772",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226834300,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286709376,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1772",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286709376,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272981700,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1772",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272981700,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718624,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1772",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718624,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581657504,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1772",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581657504,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581709936,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1772",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581709936,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
```

```json
{
  "name": "mem_cgroup_oom_trylock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581777440,
      "name": "mem_cgroup_oom_trylock",
      "external": false,
      "loc": "mm/memcontrol.c:1772",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777440,
      "name": "mem_cgroup_oom_trylock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
bool mem_cgroup_oom_trylock(struct mem_cgroup * memcg)
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
