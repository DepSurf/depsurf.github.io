# Function: <code>label_free_or_put_new</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void label_free_or_put_new(struct aa_label * label, struct aa_label * new)
```

```json
{
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582890800,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:390",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582890800,
      "name": "label_free_or_put_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void label_free_or_put_new(struct aa_label * label, struct aa_label * new)
```

```json
{
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582961472,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:396",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582961472,
      "name": "label_free_or_put_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void label_free_or_put_new(struct aa_label * label, struct aa_label * new)
```

```json
{
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583123616,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:396",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583123616,
      "name": "label_free_or_put_new",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void label_free_or_put_new(struct aa_label * label, struct aa_label * new)
```

```json
{
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583329376,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:396",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583329376,
      "name": "label_free_or_put_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void label_free_or_put_new(struct aa_label * label, struct aa_label * new)
```

```json
{
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583447952,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:396",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:__aa_labelset_update_subtree",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583447952,
      "name": "label_free_or_put_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void label_free_or_put_new(struct aa_label * label, struct aa_label * new)
```

```json
{
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583632944,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:392",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583632944,
      "name": "label_free_or_put_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void label_free_or_put_new(struct aa_label * label, struct aa_label * new)
```

```json
{
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583739104,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:386",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583739104,
      "name": "label_free_or_put_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584130473,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:387",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
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
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584248860,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:387",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
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
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584271755,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:387",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
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
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584657787,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:387",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
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
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585318609,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:390",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
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
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586058609,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:390",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
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
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586293609,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:390",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
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
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586550299,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:396",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:__label_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
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
void label_free_or_put_new(struct aa_label * label, struct aa_label * new)
```

```json
{
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495537320,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:386",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495537320,
      "name": "label_free_or_put_new",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void label_free_or_put_new(struct aa_label * label, struct aa_label * new)
```

```json
{
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228902316,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:386",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228902316,
      "name": "label_free_or_put_new",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void label_free_or_put_new(struct aa_label * label, struct aa_label * new)
```

```json
{
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289621136,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:386",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289621136,
      "name": "label_free_or_put_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void label_free_or_put_new(struct aa_label * label, struct aa_label * new)
```

```json
{
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274712824,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:386",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274712824,
      "name": "label_free_or_put_new",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void label_free_or_put_new(struct aa_label * label, struct aa_label * new)
```

```json
{
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583707840,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:386",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583707840,
      "name": "label_free_or_put_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void label_free_or_put_new(struct aa_label * label, struct aa_label * new)
```

```json
{
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583644896,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:386",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583644896,
      "name": "label_free_or_put_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void label_free_or_put_new(struct aa_label * label, struct aa_label * new)
```

```json
{
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583691616,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:386",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583691616,
      "name": "label_free_or_put_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void label_free_or_put_new(struct aa_label * label, struct aa_label * new)
```

```json
{
  "name": "label_free_or_put_new",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583791504,
      "name": "label_free_or_put_new",
      "external": false,
      "loc": "security/apparmor/label.c:386",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:__labelset_update",
        "security/apparmor/label.c:aa_label_merge",
        "security/apparmor/label.c:aa_vec_find_or_create_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583791504,
      "name": "label_free_or_put_new",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void label_free_or_put_new(struct aa_label * label, struct aa_label * new)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void label_free_or_put_new(struct aa_label * label, struct aa_label * new)
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
