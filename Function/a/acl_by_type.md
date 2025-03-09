# Function: <code>acl_by_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct posix_acl * * acl_by_type(struct inode * inode, int type)
```

```json
{
  "name": "acl_by_type",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581392288,
      "name": "acl_by_type",
      "external": true,
      "loc": "fs/posix_acl.c:24",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:get_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:get_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581392288,
      "name": "acl_by_type.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071581392304,
      "name": "acl_by_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581571110,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:24",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570336,
      "name": "acl_by_type.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581655878,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:24",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581655104,
      "name": "acl_by_type.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581710230,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:25",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581712749,
      "name": "acl_by_type.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581855878,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:25",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581858413,
      "name": "acl_by_type.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582035989,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:25",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582035584,
      "name": "acl_by_type.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582124245,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:25",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123712,
      "name": "acl_by_type.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582286213,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:26",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582285696,
      "name": "acl_by_type.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582385189,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:26",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582384672,
      "name": "acl_by_type.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582670485,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:26",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582670112,
      "name": "acl_by_type.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582739429,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:26",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582739040,
      "name": "acl_by_type.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582768197,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:26",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582767808,
      "name": "acl_by_type.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583095429,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:27",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl"
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583576037,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:28",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl"
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584178789,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:34",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl"
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584406501,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:35",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl"
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584627253,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:35",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl"
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493983428,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:26",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493982840,
      "name": "acl_by_type.part.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227448008,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:26",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227447436,
      "name": "acl_by_type.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287626388,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:26",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287625760,
      "name": "acl_by_type.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273503018,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:26",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273502626,
      "name": "acl_by_type.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582353925,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:26",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582353408,
      "name": "acl_by_type.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582291637,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:26",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582291120,
      "name": "acl_by_type.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582344405,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:26",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582343888,
      "name": "acl_by_type.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
  "name": "acl_by_type",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582423989,
      "name": "acl_by_type",
      "external": false,
      "loc": "fs/posix_acl.c:26",
      "file": "fs/posix_acl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ],
      "caller_func": [
        "fs/posix_acl.c:forget_cached_acl",
        "fs/posix_acl.c:set_cached_acl",
        "fs/posix_acl.c:get_cached_acl_rcu",
        "fs/posix_acl.c:get_cached_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582423456,
      "name": "acl_by_type.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
struct posix_acl * * acl_by_type(struct inode * inode, int type)
```
</details>
</li>
</ul>
