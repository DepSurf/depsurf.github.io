# Function: <code>aa_label_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582559136,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:888",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__aa_labelset_update_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582559136,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582800000,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:888",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__aa_labelset_update_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582800000,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582895808,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:904",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__aa_labelset_update_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582895808,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582963488,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:903",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__aa_labelset_update_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582963488,
      "name": "aa_label_insert",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583125808,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:903",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__aa_labelset_update_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583125808,
      "name": "aa_label_insert",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583331664,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:902",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__aa_labelset_update_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583331664,
      "name": "aa_label_insert",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583450240,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:903",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__aa_labelset_update_subtree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583450240,
      "name": "aa_label_insert",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583635232,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:899",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__labelset_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583635232,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583741520,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:926",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__labelset_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741520,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584129696,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:926",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584129696,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584248080,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:926",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584248080,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584270992,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:926",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584270992,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584657024,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:926",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584657024,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585317776,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:928",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585317776,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586057760,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:928",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586057760,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586292768,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:928",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586292768,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586549456,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:935",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586549456,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495540512,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:926",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__labelset_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495540512,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228904676,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:926",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__labelset_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228904676,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289624896,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:926",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__labelset_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289624896,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274714624,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:926",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__labelset_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274714624,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583710256,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:926",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__labelset_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583710256,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583647312,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:926",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__labelset_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583647312,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583694032,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:926",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__labelset_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583694032,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
struct aa_label * aa_label_insert(struct aa_labelset * ls, struct aa_label * label)
```

```json
{
  "name": "aa_label_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583793920,
      "name": "aa_label_insert",
      "external": true,
      "loc": "security/apparmor/label.c:926",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__add_profile",
        "security/apparmor/label.c:__labelset_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583793920,
      "name": "aa_label_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
