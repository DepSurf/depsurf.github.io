# Function: <code>tcf_get_next_chain</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
```

```json
{
  "name": "tcf_get_next_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588670016,
      "name": "tcf_get_next_chain",
      "external": true,
      "loc": "net/sched/cls_api.c:1062",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_tclass",
        "net/sched/sch_api.c:tc_bind_tclass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588670016,
      "name": "tcf_get_next_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
```

```json
{
  "name": "tcf_get_next_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588893472,
      "name": "tcf_get_next_chain",
      "external": true,
      "loc": "net/sched/cls_api.c:976",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588893472,
      "name": "tcf_get_next_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
```

```json
{
  "name": "tcf_get_next_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589785849,
      "name": "tcf_get_next_chain",
      "external": true,
      "loc": "net/sched/cls_api.c:939",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put"
      ],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589781568,
      "name": "tcf_get_next_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
```

```json
{
  "name": "tcf_get_next_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589821141,
      "name": "tcf_get_next_chain",
      "external": true,
      "loc": "net/sched/cls_api.c:941",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put"
      ],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589816848,
      "name": "tcf_get_next_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
```

```json
{
  "name": "tcf_get_next_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589727333,
      "name": "tcf_get_next_chain",
      "external": true,
      "loc": "net/sched/cls_api.c:941",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put"
      ],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589718288,
      "name": "tcf_get_next_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
```

```json
{
  "name": "tcf_get_next_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590485717,
      "name": "tcf_get_next_chain",
      "external": true,
      "loc": "net/sched/cls_api.c:942",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put"
      ],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590476512,
      "name": "tcf_get_next_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
```

```json
{
  "name": "tcf_get_next_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592086203,
      "name": "tcf_get_next_chain",
      "external": true,
      "loc": "net/sched/cls_api.c:959",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put"
      ],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592081744,
      "name": "tcf_get_next_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
```

```json
{
  "name": "tcf_get_next_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593904875,
      "name": "tcf_get_next_chain",
      "external": true,
      "loc": "net/sched/cls_api.c:961",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put"
      ],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593901040,
      "name": "tcf_get_next_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
```

```json
{
  "name": "tcf_get_next_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594284690,
      "name": "tcf_get_next_chain",
      "external": true,
      "loc": "net/sched/cls_api.c:1066",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put"
      ],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594279920,
      "name": "tcf_get_next_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
```

```json
{
  "name": "tcf_get_next_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595083754,
      "name": "tcf_get_next_chain",
      "external": true,
      "loc": "net/sched/cls_api.c:1068",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/cls_api.c:__tcf_block_put"
      ],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595078848,
      "name": "tcf_get_next_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
```

```json
{
  "name": "tcf_get_next_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502484728,
      "name": "tcf_get_next_chain",
      "external": true,
      "loc": "net/sched/cls_api.c:976",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502484728,
      "name": "tcf_get_next_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
```

```json
{
  "name": "tcf_get_next_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235200176,
      "name": "tcf_get_next_chain",
      "external": true,
      "loc": "net/sched/cls_api.c:976",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235200176,
      "name": "tcf_get_next_chain",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
```

```json
{
  "name": "tcf_get_next_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296048736,
      "name": "tcf_get_next_chain",
      "external": true,
      "loc": "net/sched/cls_api.c:976",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296048736,
      "name": "tcf_get_next_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
```

```json
{
  "name": "tcf_get_next_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278665048,
      "name": "tcf_get_next_chain",
      "external": true,
      "loc": "net/sched/cls_api.c:976",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278665048,
      "name": "tcf_get_next_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
```

```json
{
  "name": "tcf_get_next_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588499856,
      "name": "tcf_get_next_chain",
      "external": true,
      "loc": "net/sched/cls_api.c:976",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588499856,
      "name": "tcf_get_next_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
```

```json
{
  "name": "tcf_get_next_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588211856,
      "name": "tcf_get_next_chain",
      "external": true,
      "loc": "net/sched/cls_api.c:976",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588211856,
      "name": "tcf_get_next_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
```

```json
{
  "name": "tcf_get_next_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588832032,
      "name": "tcf_get_next_chain",
      "external": true,
      "loc": "net/sched/cls_api.c:976",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588832032,
      "name": "tcf_get_next_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
```

```json
{
  "name": "tcf_get_next_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588975392,
      "name": "tcf_get_next_chain",
      "external": true,
      "loc": "net/sched/cls_api.c:976",
      "file": "net/sched/cls_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/sch_api.c:tc_bind_class_walker",
        "net/sched/sch_api.c:tc_bind_class_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588975392,
      "name": "tcf_get_next_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct tcf_chain * tcf_get_next_chain(struct tcf_block * block, struct tcf_chain * chain)
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
