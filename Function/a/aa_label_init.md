# Function: <code>aa_label_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool aa_label_init(struct aa_label * label, int size)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582556624,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:383",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/label.c:aa_label_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582556624,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
bool aa_label_init(struct aa_label * label, int size)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582797488,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:383",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/label.c:aa_label_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582797488,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
bool aa_label_init(struct aa_label * label, int size)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582893312,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:399",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile",
        "security/apparmor/label.c:aa_label_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582893312,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
bool aa_label_init(struct aa_label * label, int size)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582962019,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:405",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582961856,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool aa_label_init(struct aa_label * label, int size)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583124335,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:405",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583124176,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool aa_label_init(struct aa_label * label, int size, gfp_t gfp)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583330159,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:405",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583330000,
      "name": "aa_label_init",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool aa_label_init(struct aa_label * label, int size)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583448735,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:405",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583448576,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
bool aa_label_init(struct aa_label * label, int size)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583633741,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:401",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583633584,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
bool aa_label_init(struct aa_label * label, int size)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583739901,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:395",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583739744,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
bool aa_label_init(struct aa_label * label, int size, gfp_t gfp)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584127486,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:396",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584127328,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool aa_label_init(struct aa_label * label, int size, gfp_t gfp)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584245870,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:396",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584245712,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool aa_label_init(struct aa_label * label, int size, gfp_t gfp)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584268798,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:396",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584268640,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool aa_label_init(struct aa_label * label, int size, gfp_t gfp)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584654828,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:396",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584654656,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool aa_label_init(struct aa_label * label, int size, gfp_t gfp)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585315416,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:399",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585315216,
      "name": "aa_label_init",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool aa_label_init(struct aa_label * label, int size, gfp_t gfp)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586054967,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:399",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586054768,
      "name": "aa_label_init",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool aa_label_init(struct aa_label * label, int size, gfp_t gfp)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586290024,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:399",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586289824,
      "name": "aa_label_init",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool aa_label_init(struct aa_label * label, int size, gfp_t gfp)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586546696,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:405",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586546496,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
bool aa_label_init(struct aa_label * label, int size)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495538092,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:395",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495537904,
      "name": "aa_label_init",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool aa_label_init(struct aa_label * label, int size)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228902984,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:395",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228902796,
      "name": "aa_label_init",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool aa_label_init(struct aa_label * label, int size)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289622332,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:395",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289622048,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
bool aa_label_init(struct aa_label * label, int size)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274713100,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:395",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274712918,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
bool aa_label_init(struct aa_label * label, int size)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583708637,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:395",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583708480,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
bool aa_label_init(struct aa_label * label, int size)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583645693,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:395",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583645536,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
bool aa_label_init(struct aa_label * label, int size)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583692413,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:395",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583692256,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
bool aa_label_init(struct aa_label * label, int size)
```

```json
{
  "name": "aa_label_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583792301,
      "name": "aa_label_init",
      "external": true,
      "loc": "security/apparmor/label.c:395",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_alloc"
      ],
      "caller_func": [
        "security/apparmor/policy.c:aa_alloc_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583792144,
      "name": "aa_label_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>gfp_t gfp</code>
</li>
</ul>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
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
