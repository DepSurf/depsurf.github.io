# Function: <code>legitimize_links</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581037789,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:642",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:unlazy_walk"
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
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581198109,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:647",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:unlazy_walk"
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
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581275373,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:647",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/namei.c:unlazy_walk"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323696,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:647",
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
      "addr": 18446744071581323696,
      "name": "legitimize_links",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463856,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:648",
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
      "addr": 18446744071581463856,
      "name": "legitimize_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581620672,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:632",
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
      "addr": 18446744071581620672,
      "name": "legitimize_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581707040,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:632",
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
      "addr": 18446744071581707040,
      "name": "legitimize_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581825792,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:630",
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
      "addr": 18446744071581825792,
      "name": "legitimize_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581898336,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:628",
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
      "addr": 18446744071581898336,
      "name": "legitimize_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582125824,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:630",
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
      "addr": 18446744071582125824,
      "name": "legitimize_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582172304,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:630",
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
      "addr": 18446744071582172304,
      "name": "legitimize_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582199728,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:684",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:try_to_unlazy_next",
        "fs/namei.c:try_to_unlazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582199728,
      "name": "legitimize_links",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582517472,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:711",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:try_to_unlazy_next",
        "fs/namei.c:try_to_unlazy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582517472,
      "name": "legitimize_links",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583042688,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:712",
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
      "addr": 18446744071583042688,
      "name": "legitimize_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583607744,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:718",
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
      "addr": 18446744071583607744,
      "name": "legitimize_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583830736,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:721",
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
      "addr": 18446744071583830736,
      "name": "legitimize_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584036752,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:724",
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
      "addr": 18446744071584036752,
      "name": "legitimize_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493378176,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:628",
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
      "addr": 18446603336493378176,
      "name": "legitimize_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226964452,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:628",
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
      "addr": 3226964452,
      "name": "legitimize_links",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286930736,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:628",
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
      "addr": 13835058055286930736,
      "name": "legitimize_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273095670,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:628",
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
      "addr": 18446743936273095670,
      "name": "legitimize_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581867072,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:628",
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
      "addr": 18446744071581867072,
      "name": "legitimize_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581804672,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:628",
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
      "addr": 18446744071581804672,
      "name": "legitimize_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581858384,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:628",
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
      "addr": 18446744071581858384,
      "name": "legitimize_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
bool legitimize_links(struct nameidata * nd)
```

```json
{
  "name": "legitimize_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581929728,
      "name": "legitimize_links",
      "external": false,
      "loc": "fs/namei.c:628",
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
      "addr": 18446744071581929728,
      "name": "legitimize_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
bool legitimize_links(struct nameidata * nd)
```
</details>
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
