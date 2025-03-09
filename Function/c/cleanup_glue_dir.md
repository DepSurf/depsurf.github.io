# Function: <code>cleanup_glue_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584378208,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:839",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:cleanup_device_parent",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move"
      ],
      "caller_func": [
        "drivers/base/core.c:cleanup_device_parent",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584378208,
      "name": "cleanup_glue_dir.isra.14.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584717768,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:839",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:cleanup_device_parent"
      ],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:cleanup_device_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584713184,
      "name": "cleanup_glue_dir.isra.14.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cleanup_glue_dir(struct device * dev, struct kobject * glue_dir)
```

```json
{
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584900880,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:1427",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584900880,
      "name": "cleanup_glue_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584992792,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:1425",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584986176,
      "name": "cleanup_glue_dir.part.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585414680,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:1560",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585408096,
      "name": "cleanup_glue_dir.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585657658,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:1602",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585650560,
      "name": "cleanup_glue_dir.part.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585789818,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:1676",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585779968,
      "name": "cleanup_glue_dir.part.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586021116,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:1824",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586012992,
      "name": "cleanup_glue_dir.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586168828,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:1861",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586160512,
      "name": "cleanup_glue_dir.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cleanup_glue_dir(struct device * dev, struct kobject * glue_dir)
```

```json
{
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586918064,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:2341",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586918064,
      "name": "cleanup_glue_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cleanup_glue_dir(struct device * dev, struct kobject * glue_dir)
```

```json
{
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587002640,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:2750",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587002640,
      "name": "cleanup_glue_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void cleanup_glue_dir(struct device * dev, struct kobject * glue_dir)
```

```json
{
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586884992,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:2968",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586884992,
      "name": "cleanup_glue_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void cleanup_glue_dir(struct device * dev, struct kobject * glue_dir)
```

```json
{
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587446560,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:3036",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587446560,
      "name": "cleanup_glue_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cleanup_glue_dir(struct device * dev, struct kobject * glue_dir)
```

```json
{
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588763616,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:3071",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588763616,
      "name": "cleanup_glue_dir",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cleanup_glue_dir(struct device * dev, struct kobject * glue_dir)
```

```json
{
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590253440,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:3269",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590253440,
      "name": "cleanup_glue_dir",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cleanup_glue_dir(struct device * dev, struct kobject * glue_dir)
```

```json
{
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590573520,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:3292",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590573520,
      "name": "cleanup_glue_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cleanup_glue_dir(struct device * dev, struct kobject * glue_dir)
```

```json
{
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590931920,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:3305",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590931920,
      "name": "cleanup_glue_dir",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498964672,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:1861",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498956056,
      "name": "cleanup_glue_dir.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231534892,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:1861",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231527240,
      "name": "cleanup_glue_dir.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292110800,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:1861",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292099248,
      "name": "cleanup_glue_dir.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276345498,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:1861",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276338194,
      "name": "cleanup_glue_dir.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585929196,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:1861",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585920880,
      "name": "cleanup_glue_dir.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585778332,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:1861",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585770016,
      "name": "cleanup_glue_dir.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586118844,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:1861",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586110528,
      "name": "cleanup_glue_dir.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
  "name": "cleanup_glue_dir",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586227452,
      "name": "cleanup_glue_dir",
      "external": false,
      "loc": "drivers/base/core.c:1861",
      "file": "drivers/base/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ],
      "caller_func": [
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_move",
        "drivers/base/core.c:device_del",
        "drivers/base/core.c:device_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586219136,
      "name": "cleanup_glue_dir.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void cleanup_glue_dir(struct device * dev, struct kobject * glue_dir)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void cleanup_glue_dir(struct device * dev, struct kobject * glue_dir)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void cleanup_glue_dir(struct device * dev, struct kobject * glue_dir)
```
</details>
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
