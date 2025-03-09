# Function: <code>selinux_inode_getsecid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void selinux_inode_getsecid(const struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582259312,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3208",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_socket_getpeersec_dgram"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582259312,
      "name": "selinux_inode_getsecid",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582478096,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3290",
      "file": "security/selinux/hooks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582478096,
      "name": "selinux_inode_getsecid",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582580549,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3327",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582570560,
      "name": "selinux_inode_getsecid",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582672117,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3309",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582660096,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582826805,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3324",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582815232,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583017581,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3485",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583009664,
      "name": "selinux_inode_getsecid",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583133396,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3233",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583123104,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583320394,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3360",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583310416,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583425722,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3418",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583415488,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583766074,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3405",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583756016,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583885402,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3425",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583877520,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583911866,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3584",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583903680,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584275546,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3569",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584267392,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584892554,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3459",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584881120,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585599850,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3477",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585587296,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585830954,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3469",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585818416,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495183080,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3418",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495171280,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228571608,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3418",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228557704,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289126068,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3418",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289108272,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274423738,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3418",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274413852,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583394458,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3418",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583384224,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583331546,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3418",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583321312,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583378234,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3418",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583368000,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
```

```json
{
  "name": "selinux_inode_getsecid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583471818,
      "name": "selinux_inode_getsecid",
      "external": false,
      "loc": "security/selinux/hooks.c:3418",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_copy_up"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583463392,
      "name": "selinux_inode_getsecid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void selinux_inode_getsecid(struct inode * inode, u32 * secid)
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
