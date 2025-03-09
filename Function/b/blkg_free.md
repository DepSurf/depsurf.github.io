# Function: <code>blkg_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blkg_free(struct blkcg_gq * blkg)
```

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582871424,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:64",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkcg_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582871424,
      "name": "blkg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void blkg_free(struct blkcg_gq * blkg)
```

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583157408,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:64",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_init_queue",
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583157408,
      "name": "blkg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void blkg_free(struct blkcg_gq * blkg)
```

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583269488,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:64",
      "file": "block/blk-cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkcg_init_queue",
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583269488,
      "name": "blkg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583333030,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:65",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583326864,
      "name": "blkg_free.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583516326,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:65",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583510080,
      "name": "blkg_free.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583729553,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:65",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583724048,
      "name": "blkg_free.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blkg_free(struct blkcg_gq * blkg)
```

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583830816,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:68",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583830816,
      "name": "blkg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584027853,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:72",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584021184,
      "name": "blkg_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584131851,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:72",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584124784,
      "name": "blkg_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584529376,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:72",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584522496,
      "name": "blkg_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584638835,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:72",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584631632,
      "name": "blkg_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584666755,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:70",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584659472,
      "name": "blkg_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585083199,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:73",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585073856,
      "name": "blkg_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585809179,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:108",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
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
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586590931,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:140",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586844964,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:156",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587122289,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:156",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495981068,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:72",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495971864,
      "name": "blkg_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229322252,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:72",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229315000,
      "name": "blkg_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290205612,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:72",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290194224,
      "name": "blkg_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275081148,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:72",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275073916,
      "name": "blkg_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584100587,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:72",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584093520,
      "name": "blkg_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584036293,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:72",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584029280,
      "name": "blkg_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584084347,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:72",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584077280,
      "name": "blkg_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584187137,
      "name": "blkg_free",
      "external": false,
      "loc": "block/blk-cgroup.c:72",
      "file": "block/blk-cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": [
        "block/blk-cgroup.c:blkg_conf_prep",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_alloc",
        "block/blk-cgroup.c:__blkg_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584180912,
      "name": "blkg_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void blkg_free(struct blkcg_gq * blkg)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void blkg_free(struct blkcg_gq * blkg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void blkg_free(struct blkcg_gq * blkg)
```
</details>
</li>
</ul>
