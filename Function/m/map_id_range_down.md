# Function: <code>map_id_range_down</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580019272,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:160",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
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
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580051892,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:160",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
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
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580091553,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:206",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
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
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580097143,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:207",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:map_write"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580147808,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:302",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147808,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580207616,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:302",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580207616,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580259872,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:302",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580259872,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580310912,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:296",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580310912,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580359744,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:296",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580359744,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580433696,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:296",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580433696,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580420736,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:296",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420736,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580424928,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:297",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424928,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580588672,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:313",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580588672,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580790528,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:318",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580790528,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581075280,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:318",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581075280,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581166208,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:318",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166208,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581270704,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:321",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:new_idmap_permitted",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581270704,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491620512,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:296",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491620512,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225576024,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:296",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225576024,
      "name": "map_id_range_down",
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284612832,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:296",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284612832,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272020736,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:296",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272020736,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580328544,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:296",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328544,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275808,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:296",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275808,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580319792,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:296",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580319792,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```

```json
{
  "name": "map_id_range_down",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580374736,
      "name": "map_id_range_down",
      "external": false,
      "loc": "kernel/user_namespace.c:296",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:map_write",
        "kernel/user_namespace.c:make_kprojid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580374736,
      "name": "map_id_range_down",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
u32 map_id_range_down(struct uid_gid_map * map, u32 id, u32 count)
```
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
