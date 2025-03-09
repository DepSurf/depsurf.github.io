# Function: <code>inode_has_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581214685,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:492",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:invalidate_inode_buffers",
        "fs/buffer.c:remove_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:__destroy_inode",
        "fs/inode.c:inode_lru_isolate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581222880,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581388211,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:488",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581388048,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581466691,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:489",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581466528,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581522211,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:486",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522048,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581664467,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:465",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581664304,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581827749,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:457",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827632,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581914341,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:458",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581914224,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582052101,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:459",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052000,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582129957,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:459",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582129856,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582374469,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:485",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582374256,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582430773,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:484",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582430560,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582457557,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:484",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582457344,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582781173,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:484",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582780960,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583333301,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:484",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583333056,
      "name": "inode_has_buffers",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583917877,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:484",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583917600,
      "name": "inode_has_buffers",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584140581,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:525",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140304,
      "name": "inode_has_buffers",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584356645,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:519",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584356480,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493673528,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:459",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493673360,
      "name": "inode_has_buffers",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227205592,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:459",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227205448,
      "name": "inode_has_buffers",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287275032,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:459",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287274832,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273299128,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:459",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273298978,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582098693,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:459",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582098592,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582036133,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:459",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582036032,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582089173,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:459",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582089072,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int inode_has_buffers(struct inode * inode)
```

```json
{
  "name": "inode_has_buffers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582161893,
      "name": "inode_has_buffers",
      "external": true,
      "loc": "fs/buffer.c:459",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:remove_inode_buffers",
        "fs/buffer.c:invalidate_inode_buffers"
      ],
      "caller_func": [
        "fs/inode.c:inode_lru_isolate",
        "fs/inode.c:__destroy_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582161792,
      "name": "inode_has_buffers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
