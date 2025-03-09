# Function: <code>bpf_map_update_elem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u64 bpf_map_update_elem(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580381936,
      "name": "bpf_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/helpers.c:57",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580381936,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
u64 bpf_map_update_elem(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580442016,
      "name": "bpf_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/helpers.c:57",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442016,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580496240,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:46",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580496240,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580524944,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:46",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580524944,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580587360,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:46",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580587360,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580682816,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:46",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580682816,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580753568,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:46",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580753568,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580836304,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:41",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580836304,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580887328,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:41",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580887328,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581026144,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:44",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581026144,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581032992,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:44",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581032992,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581044528,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:45",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581044528,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581267536,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:45",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267536,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581558704,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:48",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558704,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581931248,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:51",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581931248,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582114528,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:52",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582114528,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582254848,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:54",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582254848,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492212824,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:41",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492212824,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226110048,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:41",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226110048,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285434016,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:41",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285434016,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272361282,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:41",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272361282,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580856128,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:41",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580856128,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580802304,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:41",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580802304,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580847376,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:41",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580847376,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
u64 bpf_map_update_elem(u64 map, u64 key, u64 value, u64 flags, u64 __ur_1)
```

```json
{
  "name": "bpf_map_update_elem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580905664,
      "name": "bpf_map_update_elem",
      "external": true,
      "loc": "kernel/bpf/helpers.c:41",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580905664,
      "name": "bpf_map_update_elem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<code>u64 map</code>
</li>
<li>
<b>Param added. </b>
<code>u64 key</code>
</li>
<li>
<b>Param added. </b>
<code>u64 value</code>
</li>
<li>
<b>Param added. </b>
<code>u64 flags</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
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
<code>u64 r3</code>
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
