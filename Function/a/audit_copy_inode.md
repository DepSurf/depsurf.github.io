# Function: <code>audit_copy_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, const struct inode * inode)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580034256,
      "name": "audit_copy_inode",
      "external": true,
      "loc": "kernel/audit.c:1724",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_link_denied",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034256,
      "name": "audit_copy_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580066816,
      "name": "audit_copy_inode",
      "external": true,
      "loc": "kernel/audit.c:1735",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_link_denied",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580066816,
      "name": "audit_copy_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580107040,
      "name": "audit_copy_inode",
      "external": true,
      "loc": "kernel/audit.c:1874",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_link_denied",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107040,
      "name": "audit_copy_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580112432,
      "name": "audit_copy_inode",
      "external": true,
      "loc": "kernel/audit.c:2041",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_link_denied",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580112432,
      "name": "audit_copy_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580164976,
      "name": "audit_copy_inode",
      "external": true,
      "loc": "kernel/audit.c:2049",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_log_link_denied",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580164976,
      "name": "audit_copy_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580224832,
      "name": "audit_copy_inode",
      "external": true,
      "loc": "kernel/audit.c:2102",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580224832,
      "name": "audit_copy_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580277248,
      "name": "audit_copy_inode",
      "external": true,
      "loc": "kernel/audit.c:2101",
      "file": "kernel/audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580277248,
      "name": "audit_copy_inode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580345120,
      "name": "audit_copy_inode",
      "external": false,
      "loc": "kernel/auditsc.c:1920",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580345120,
      "name": "audit_copy_inode",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580393888,
      "name": "audit_copy_inode",
      "external": false,
      "loc": "kernel/auditsc.c:1920",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580393888,
      "name": "audit_copy_inode",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580480190,
      "name": "audit_copy_inode",
      "external": false,
      "loc": "kernel/auditsc.c:1951",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:__audit_inode_child"
      ],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580478720,
      "name": "audit_copy_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580468525,
      "name": "audit_copy_inode",
      "external": false,
      "loc": "kernel/auditsc.c:1968",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:__audit_inode_child"
      ],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580466896,
      "name": "audit_copy_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580471676,
      "name": "audit_copy_inode",
      "external": false,
      "loc": "kernel/auditsc.c:1965",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:__audit_inode_child"
      ],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580470656,
      "name": "audit_copy_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580638764,
      "name": "audit_copy_inode",
      "external": false,
      "loc": "kernel/auditsc.c:1978",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:__audit_inode_child"
      ],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580637712,
      "name": "audit_copy_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580849895,
      "name": "audit_copy_inode",
      "external": false,
      "loc": "kernel/auditsc.c:2269",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:__audit_inode_child"
      ],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845296,
      "name": "audit_copy_inode",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581136487,
      "name": "audit_copy_inode",
      "external": false,
      "loc": "kernel/auditsc.c:2247",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:__audit_inode_child"
      ],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581132448,
      "name": "audit_copy_inode",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581225409,
      "name": "audit_copy_inode",
      "external": false,
      "loc": "kernel/auditsc.c:2244",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:__audit_inode_child"
      ],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218000,
      "name": "audit_copy_inode",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581331738,
      "name": "audit_copy_inode",
      "external": false,
      "loc": "kernel/auditsc.c:2239",
      "file": "kernel/auditsc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/auditsc.c:__audit_inode_child"
      ],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581324432,
      "name": "audit_copy_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491659944,
      "name": "audit_copy_inode",
      "external": false,
      "loc": "kernel/auditsc.c:1920",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491659944,
      "name": "audit_copy_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225614008,
      "name": "audit_copy_inode",
      "external": false,
      "loc": "kernel/auditsc.c:1920",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225614008,
      "name": "audit_copy_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284662880,
      "name": "audit_copy_inode",
      "external": false,
      "loc": "kernel/auditsc.c:1920",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284662880,
      "name": "audit_copy_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272052540,
      "name": "audit_copy_inode",
      "external": false,
      "loc": "kernel/auditsc.c:1920",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272052540,
      "name": "audit_copy_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580362688,
      "name": "audit_copy_inode",
      "external": false,
      "loc": "kernel/auditsc.c:1920",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580362688,
      "name": "audit_copy_inode",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580309856,
      "name": "audit_copy_inode",
      "external": false,
      "loc": "kernel/auditsc.c:1920",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309856,
      "name": "audit_copy_inode",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580353936,
      "name": "audit_copy_inode",
      "external": false,
      "loc": "kernel/auditsc.c:1920",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580353936,
      "name": "audit_copy_inode",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names * name, const struct dentry * dentry, struct inode * inode, unsigned int flags)
```

```json
{
  "name": "audit_copy_inode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580409232,
      "name": "audit_copy_inode",
      "external": false,
      "loc": "kernel/auditsc.c:1920",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode_child",
        "kernel/auditsc.c:__audit_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580409232,
      "name": "audit_copy_inode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct inode * inode</code> ➡️ <code>struct inode * inode</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
</ul>
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
