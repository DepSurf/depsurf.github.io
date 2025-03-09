# Function: <code>lsm_inode_alloc</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582639998,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:519",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc",
        "security/security.c:lsm_early_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582636944,
      "name": "lsm_inode_alloc",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582794243,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:481",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc",
        "security/security.c:lsm_early_inode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582790816,
      "name": "lsm_inode_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583103621,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:548",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583101760,
      "name": "lsm_inode_alloc",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583289509,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:547",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583287184,
      "name": "lsm_inode_alloc",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583394693,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:581",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583392512,
      "name": "lsm_inode_alloc",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583734165,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:634",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731888,
      "name": "lsm_inode_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583854494,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:636",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583852208,
      "name": "lsm_inode_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583879518,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:639",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583877040,
      "name": "lsm_inode_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584244446,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:639",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584241968,
      "name": "lsm_inode_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584851790,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:667",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584848672,
      "name": "lsm_inode_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585554718,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:716",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585551120,
      "name": "lsm_inode_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585785614,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:724",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585781904,
      "name": "lsm_inode_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586033758,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:729",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586029600,
      "name": "lsm_inode_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495146380,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:581",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495143664,
      "name": "lsm_inode_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228534068,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:581",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228531416,
      "name": "lsm_inode_alloc",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289067876,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:581",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289062576,
      "name": "lsm_inode_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274394784,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:581",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274392786,
      "name": "lsm_inode_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583363429,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:581",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583361248,
      "name": "lsm_inode_alloc",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583300533,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:581",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583298352,
      "name": "lsm_inode_alloc",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583347205,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:581",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583345024,
      "name": "lsm_inode_alloc",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int lsm_inode_alloc(struct inode * inode)
```

```json
{
  "name": "lsm_inode_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583442389,
      "name": "lsm_inode_alloc",
      "external": true,
      "loc": "security/security.c:581",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_inode_alloc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_set_mnt_opts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583440208,
      "name": "lsm_inode_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int lsm_inode_alloc(struct inode * inode)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int lsm_inode_alloc(struct inode * inode)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int lsm_inode_alloc(struct inode * inode)
```
</details>
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
