# Function: <code>map_id_up</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580016310,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:209",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
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
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580050701,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:209",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
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
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580090378,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:255",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
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
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580096026,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:256",
      "file": "kernel/user_namespace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580148096,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:365",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148096,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580207904,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:365",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580207904,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580260160,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:365",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580260160,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580311216,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:359",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580311216,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580360048,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:359",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580360048,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580432976,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:359",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580432976,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580420016,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:359",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580420016,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580424208,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:360",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424208,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580587952,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:376",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580587952,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580789696,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:381",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580789696,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581074288,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:381",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074288,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581165056,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:381",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165056,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581275184,
      "name": "map_id_up",
      "external": true,
      "loc": "kernel/user_namespace.c:384",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns",
        "fs/mnt_idmapping.c:from_vfsgid",
        "fs/mnt_idmapping.c:from_vfsuid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275184,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491620944,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:359",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491620944,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225576432,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:359",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225576432,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284613376,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:359",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284613376,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272021098,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:359",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272021098,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580328848,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:359",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328848,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580276112,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:359",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580276112,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580320096,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:359",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580320096,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
```

```json
{
  "name": "map_id_up",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580375040,
      "name": "map_id_up",
      "external": false,
      "loc": "kernel/user_namespace.c:359",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:projid_m_show",
        "kernel/user_namespace.c:gid_m_show",
        "kernel/user_namespace.c:uid_m_show",
        "kernel/user_namespace.c:from_kprojid_munged",
        "kernel/user_namespace.c:from_kgid_munged",
        "kernel/user_namespace.c:from_kuid_munged",
        "kernel/user_namespace.c:create_user_ns",
        "kernel/user_namespace.c:create_user_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375040,
      "name": "map_id_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
u32 map_id_up(struct uid_gid_map * map, u32 id)
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
