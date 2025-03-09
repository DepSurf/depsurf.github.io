# Function: <code>disable_write_same</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585798035,
      "name": "disable_write_same",
      "external": false,
      "loc": "drivers/md/dm.c:983",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:clone_endio",
        "drivers/md/dm.c:dm_softirq_done"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586195432,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:817",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:clone_endio"
      ],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_softirq_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586200144,
      "name": "disable_write_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586399907,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:817",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:clone_endio"
      ],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_softirq_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586404624,
      "name": "disable_write_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586503315,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:818",
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
      "addr": 18446744071586508064,
      "name": "disable_write_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586970485,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:827",
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
      "addr": 18446744071586975600,
      "name": "disable_write_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587265534,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:911",
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
      "addr": 18446744071587272304,
      "name": "disable_write_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587445454,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:966",
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
      "addr": 18446744071587452800,
      "name": "disable_write_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587727222,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:957",
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
      "addr": 18446744071587727264,
      "name": "disable_write_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587931574,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:957",
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
      "addr": 18446744071587931616,
      "name": "disable_write_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588782106,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:970",
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
      "addr": 18446744071588784352,
      "name": "disable_write_same",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588802051,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:966",
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
      "addr": 18446744071588802848,
      "name": "disable_write_same",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588686937,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:969",
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
      "addr": 18446744071588688448,
      "name": "disable_write_same",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589373502,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:858",
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
      "addr": 18446744071589376816,
      "name": "disable_write_same",
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501167372,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:957",
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
      "addr": 18446603336501167400,
      "name": "disable_write_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233677196,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:957",
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
      "addr": 3233677224,
      "name": "disable_write_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294679460,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:957",
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
      "addr": 13835058055294679504,
      "name": "disable_write_same",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277875228,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:957",
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
      "addr": 18446743936277875252,
      "name": "disable_write_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587562550,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:957",
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
      "addr": 18446744071587562592,
      "name": "disable_write_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587330630,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:957",
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
      "addr": 18446744071587330672,
      "name": "disable_write_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587887718,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:957",
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
      "addr": 18446744071587887760,
      "name": "disable_write_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void disable_write_same(struct mapped_device * md)
```

```json
{
  "name": "disable_write_same",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588003014,
      "name": "disable_write_same",
      "external": true,
      "loc": "drivers/md/dm.c:957",
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
      "addr": 18446744071588003056,
      "name": "disable_write_same",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void disable_write_same(struct mapped_device * md)
```
</details>
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void disable_write_same(struct mapped_device * md)
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
