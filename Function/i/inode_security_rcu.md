# Function: <code>inode_security_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582494317,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:281",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
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
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582585533,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:282",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582677593,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:274",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582831145,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:275",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583043442,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:307",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct inode_security_struct * inode_security_rcu(struct inode * inode, bool rcu)
```

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583158752,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:292",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583158752,
      "name": "inode_security_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
struct inode_security_struct * inode_security_rcu(struct inode * inode, bool rcu)
```

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583345680,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:293",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583345680,
      "name": "inode_security_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
struct inode_security_struct * inode_security_rcu(struct inode * inode, bool rcu)
```

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583451232,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:295",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583451232,
      "name": "inode_security_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583787895,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:280",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link",
        "security/selinux/hooks.c:selinux_inode_follow_link"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583909959,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:281",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link",
        "security/selinux/hooks.c:selinux_inode_follow_link"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583938088,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:317",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link",
        "security/selinux/hooks.c:selinux_inode_follow_link"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584302805,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:294",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link",
        "security/selinux/hooks.c:selinux_inode_follow_link"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584917613,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:280",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link",
        "security/selinux/hooks.c:selinux_inode_follow_link"
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
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585626973,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:282",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link",
        "security/selinux/hooks.c:selinux_inode_follow_link"
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
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585857085,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:278",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link",
        "security/selinux/hooks.c:selinux_inode_follow_link"
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
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586106816,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:306",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link",
        "security/selinux/hooks.c:selinux_inode_follow_link"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct inode_security_struct * inode_security_rcu(struct inode * inode, bool rcu)
```

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495212808,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:295",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495212808,
      "name": "inode_security_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
struct inode_security_struct * inode_security_rcu(struct inode * inode, bool rcu)
```

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228589040,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:295",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228589040,
      "name": "inode_security_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
struct inode_security_struct * inode_security_rcu(struct inode * inode, bool rcu)
```

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289153216,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:295",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289153216,
      "name": "inode_security_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct inode_security_struct * inode_security_rcu(struct inode * inode, bool rcu)
```

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274446210,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:295",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274446210,
      "name": "inode_security_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
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
struct inode_security_struct * inode_security_rcu(struct inode * inode, bool rcu)
```

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583419968,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:295",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583419968,
      "name": "inode_security_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
struct inode_security_struct * inode_security_rcu(struct inode * inode, bool rcu)
```

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583357040,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:295",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583357040,
      "name": "inode_security_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
struct inode_security_struct * inode_security_rcu(struct inode * inode, bool rcu)
```

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583403744,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:295",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583403744,
      "name": "inode_security_rcu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
struct inode_security_struct * inode_security_rcu(struct inode * inode, bool rcu)
```

```json
{
  "name": "inode_security_rcu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583488160,
      "name": "inode_security_rcu",
      "external": false,
      "loc": "security/selinux/hooks.c:295",
      "file": "security/selinux/hooks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_inode_permission",
        "security/selinux/hooks.c:selinux_inode_follow_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583488160,
      "name": "inode_security_rcu",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct inode_security_struct * inode_security_rcu(struct inode * inode, bool rcu)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct inode_security_struct * inode_security_rcu(struct inode * inode, bool rcu)
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
