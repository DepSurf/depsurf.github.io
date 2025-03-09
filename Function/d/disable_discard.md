# Function: <code>disable_discard</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void disable_discard(struct mapped_device * md)
```

```json
{
  "name": "disable_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587726832,
      "name": "disable_discard",
      "external": true,
      "loc": "drivers/md/dm.c:948",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:clone_endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587726832,
      "name": "disable_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void disable_discard(struct mapped_device * md)
```

```json
{
  "name": "disable_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587931184,
      "name": "disable_discard",
      "external": true,
      "loc": "drivers/md/dm.c:948",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:clone_endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587931184,
      "name": "disable_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void disable_discard(struct mapped_device * md)
```

```json
{
  "name": "disable_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588782032,
      "name": "disable_discard",
      "external": true,
      "loc": "drivers/md/dm.c:961",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:clone_endio"
      ],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588784288,
      "name": "disable_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void disable_discard(struct mapped_device * md)
```

```json
{
  "name": "disable_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588802105,
      "name": "disable_discard",
      "external": true,
      "loc": "drivers/md/dm.c:957",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:clone_endio"
      ],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588802784,
      "name": "disable_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void disable_discard(struct mapped_device * md)
```

```json
{
  "name": "disable_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588686983,
      "name": "disable_discard",
      "external": true,
      "loc": "drivers/md/dm.c:960",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:clone_endio"
      ],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588688384,
      "name": "disable_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void disable_discard(struct mapped_device * md)
```

```json
{
  "name": "disable_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589373550,
      "name": "disable_discard",
      "external": true,
      "loc": "drivers/md/dm.c:849",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:clone_endio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589376752,
      "name": "disable_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void disable_discard(struct mapped_device * md)
```

```json
{
  "name": "disable_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590850661,
      "name": "disable_discard",
      "external": true,
      "loc": "drivers/md/dm.c:995",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:clone_endio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590852400,
      "name": "disable_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void disable_discard(struct mapped_device * md)
```

```json
{
  "name": "disable_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592538089,
      "name": "disable_discard",
      "external": true,
      "loc": "drivers/md/dm.c:1073",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:clone_endio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592542992,
      "name": "disable_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void disable_discard(struct mapped_device * md)
```

```json
{
  "name": "disable_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592968695,
      "name": "disable_discard",
      "external": true,
      "loc": "drivers/md/dm.c:1089",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:clone_endio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592974208,
      "name": "disable_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void disable_discard(struct mapped_device * md)
```

```json
{
  "name": "disable_discard",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593718832,
      "name": "disable_discard",
      "external": true,
      "loc": "drivers/md/dm.c:1075",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:clone_endio"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593724192,
      "name": "disable_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void disable_discard(struct mapped_device * md)
```

```json
{
  "name": "disable_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501166976,
      "name": "disable_discard",
      "external": true,
      "loc": "drivers/md/dm.c:948",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:clone_endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501166976,
      "name": "disable_discard",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void disable_discard(struct mapped_device * md)
```

```json
{
  "name": "disable_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233676768,
      "name": "disable_discard",
      "external": true,
      "loc": "drivers/md/dm.c:948",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:clone_endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233676768,
      "name": "disable_discard",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void disable_discard(struct mapped_device * md)
```

```json
{
  "name": "disable_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294678928,
      "name": "disable_discard",
      "external": true,
      "loc": "drivers/md/dm.c:948",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:clone_endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294678928,
      "name": "disable_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void disable_discard(struct mapped_device * md)
```

```json
{
  "name": "disable_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277874908,
      "name": "disable_discard",
      "external": true,
      "loc": "drivers/md/dm.c:948",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:clone_endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277874908,
      "name": "disable_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void disable_discard(struct mapped_device * md)
```

```json
{
  "name": "disable_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587562160,
      "name": "disable_discard",
      "external": true,
      "loc": "drivers/md/dm.c:948",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:clone_endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587562160,
      "name": "disable_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void disable_discard(struct mapped_device * md)
```

```json
{
  "name": "disable_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587330240,
      "name": "disable_discard",
      "external": true,
      "loc": "drivers/md/dm.c:948",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:clone_endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587330240,
      "name": "disable_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void disable_discard(struct mapped_device * md)
```

```json
{
  "name": "disable_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587887328,
      "name": "disable_discard",
      "external": true,
      "loc": "drivers/md/dm.c:948",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:clone_endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587887328,
      "name": "disable_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void disable_discard(struct mapped_device * md)
```

```json
{
  "name": "disable_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588002624,
      "name": "disable_discard",
      "external": true,
      "loc": "drivers/md/dm.c:948",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:clone_endio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588002624,
      "name": "disable_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void disable_discard(struct mapped_device * md)
```
</details>
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
