# Function: <code>flow_hash_from_keys</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586256512,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:622",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_get_hash_flowi6",
        "net/core/flow_dissector.c:__skb_get_hash_flowi4",
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/core/flow_dissector.c:__get_hash_from_flowi4"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586256512,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586680768,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:611",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi4",
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/core/flow_dissector.c:__skb_get_hash_flowi4",
        "net/core/flow_dissector.c:__skb_get_hash_flowi6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586680768,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586865424,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:716",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi4",
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/core/flow_dissector.c:__skb_get_hash_flowi4",
        "net/core/flow_dissector.c:__skb_get_hash_flowi6"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586865424,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586988800,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:911",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi4",
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/core/flow_dissector.c:__skb_get_hash_flowi4",
        "net/core/flow_dissector.c:__skb_get_hash_flowi6",
        "net/ipv4/route.c:fib_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586988800,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587487184,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1110",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi4",
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587487184,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587792608,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1165",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587792608,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 638
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587926704,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1341",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587926704,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 654
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588235808,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1454",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588235808,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588440528,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1490",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588440528,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589308864,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1509",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589308864,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589307856,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1532",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589307856,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589201856,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1558",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589201856,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589923344,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1563",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589923344,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591455344,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1617",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591455344,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593222688,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1689",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593222688,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593684800,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1729",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593684800,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594462960,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1780",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594462960,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501963992,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1490",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501963992,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234717744,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1490",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234717744,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295388960,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1490",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295388960,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278264296,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1490",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278264296,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588047312,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1490",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588047312,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587760400,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1490",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587760400,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588379088,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1490",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588379088,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
u32 flow_hash_from_keys(struct flow_keys * keys)
```

```json
{
  "name": "flow_hash_from_keys",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588514784,
      "name": "flow_hash_from_keys",
      "external": true,
      "loc": "net/core/flow_dissector.c:1490",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__get_hash_from_flowi6",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv4/route.c:fib_multipath_hash",
        "net/ipv6/route.c:rt6_multipath_hash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588514784,
      "name": "flow_hash_from_keys",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
