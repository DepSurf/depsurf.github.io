# Function: <code>legitimize_root</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool legitimize_root(struct nameidata * nd)
```

```json
{
  "name": "legitimize_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581898544,
      "name": "legitimize_root",
      "external": false,
      "loc": "fs/namei.c:642",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_fast",
        "fs/namei.c:unlazy_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581898544,
      "name": "legitimize_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
bool legitimize_root(struct nameidata * nd)
```

```json
{
  "name": "legitimize_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582126016,
      "name": "legitimize_root",
      "external": false,
      "loc": "fs/namei.c:644",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:unlazy_child",
        "fs/namei.c:unlazy_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126016,
      "name": "legitimize_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
bool legitimize_root(struct nameidata * nd)
```

```json
{
  "name": "legitimize_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582172496,
      "name": "legitimize_root",
      "external": false,
      "loc": "fs/namei.c:644",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:unlazy_child",
        "fs/namei.c:try_to_unlazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582172496,
      "name": "legitimize_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
bool legitimize_root(struct nameidata * nd)
```

```json
{
  "name": "legitimize_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582196944,
      "name": "legitimize_root",
      "external": false,
      "loc": "fs/namei.c:703",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:try_to_unlazy_next",
        "fs/namei.c:try_to_unlazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582196944,
      "name": "legitimize_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
bool legitimize_root(struct nameidata * nd)
```

```json
{
  "name": "legitimize_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582514272,
      "name": "legitimize_root",
      "external": false,
      "loc": "fs/namei.c:730",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:try_to_unlazy_next",
        "fs/namei.c:try_to_unlazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582514272,
      "name": "legitimize_root",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "legitimize_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583043458,
      "name": "legitimize_root",
      "external": false,
      "loc": "fs/namei.c:731",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:try_to_unlazy_next",
        "fs/namei.c:try_to_unlazy"
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
  "name": "legitimize_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583608122,
      "name": "legitimize_root",
      "external": false,
      "loc": "fs/namei.c:737",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:try_to_unlazy_next",
        "fs/namei.c:try_to_unlazy"
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
  "name": "legitimize_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583831114,
      "name": "legitimize_root",
      "external": false,
      "loc": "fs/namei.c:740",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:try_to_unlazy_next",
        "fs/namei.c:try_to_unlazy"
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
  "name": "legitimize_root",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584037130,
      "name": "legitimize_root",
      "external": false,
      "loc": "fs/namei.c:743",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:try_to_unlazy_next",
        "fs/namei.c:try_to_unlazy"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool legitimize_root(struct nameidata * nd)
```

```json
{
  "name": "legitimize_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493378392,
      "name": "legitimize_root",
      "external": false,
      "loc": "fs/namei.c:642",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_fast",
        "fs/namei.c:unlazy_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493378392,
      "name": "legitimize_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
bool legitimize_root(struct nameidata * nd)
```

```json
{
  "name": "legitimize_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226964640,
      "name": "legitimize_root",
      "external": false,
      "loc": "fs/namei.c:642",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_fast",
        "fs/namei.c:unlazy_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226964640,
      "name": "legitimize_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
bool legitimize_root(struct nameidata * nd)
```

```json
{
  "name": "legitimize_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286931072,
      "name": "legitimize_root",
      "external": false,
      "loc": "fs/namei.c:642",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_fast",
        "fs/namei.c:unlazy_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286931072,
      "name": "legitimize_root",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool legitimize_root(struct nameidata * nd)
```

```json
{
  "name": "legitimize_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273095832,
      "name": "legitimize_root",
      "external": false,
      "loc": "fs/namei.c:642",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_fast",
        "fs/namei.c:unlazy_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273095832,
      "name": "legitimize_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
bool legitimize_root(struct nameidata * nd)
```

```json
{
  "name": "legitimize_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581867280,
      "name": "legitimize_root",
      "external": false,
      "loc": "fs/namei.c:642",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_fast",
        "fs/namei.c:unlazy_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581867280,
      "name": "legitimize_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
bool legitimize_root(struct nameidata * nd)
```

```json
{
  "name": "legitimize_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581804880,
      "name": "legitimize_root",
      "external": false,
      "loc": "fs/namei.c:642",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_fast",
        "fs/namei.c:unlazy_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804880,
      "name": "legitimize_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
bool legitimize_root(struct nameidata * nd)
```

```json
{
  "name": "legitimize_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581858592,
      "name": "legitimize_root",
      "external": false,
      "loc": "fs/namei.c:642",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_fast",
        "fs/namei.c:unlazy_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581858592,
      "name": "legitimize_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
bool legitimize_root(struct nameidata * nd)
```

```json
{
  "name": "legitimize_root",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581929936,
      "name": "legitimize_root",
      "external": false,
      "loc": "fs/namei.c:642",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_fast",
        "fs/namei.c:unlazy_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581929936,
      "name": "legitimize_root",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
bool legitimize_root(struct nameidata * nd)
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool legitimize_root(struct nameidata * nd)
```
</details>
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
