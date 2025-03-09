# Function: <code>ns_cmp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ns_cmp(struct aa_ns * a, struct aa_ns * b)
```

```json
{
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582551488,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:109",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:profile_cmp",
        "security/apparmor/label.c:aa_label_find_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582551488,
      "name": "ns_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
int ns_cmp(struct aa_ns * a, struct aa_ns * b)
```

```json
{
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582792032,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:109",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:profile_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792032,
      "name": "ns_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int ns_cmp(struct aa_ns * a, struct aa_ns * b)
```

```json
{
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582887664,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:109",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:profile_cmp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582887664,
      "name": "ns_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582963929,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:111",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:profile_cmp"
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
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583126249,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:111",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:profile_cmp"
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
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583332112,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:111",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:profile_cmp"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583450688,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:111",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:profile_cmp",
        "security/apparmor/label.c:profile_cmp"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583636686,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:107",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583742974,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:107",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584132316,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:107",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:__vec_find",
        "security/apparmor/label.c:__vec_find",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:sort_cmp",
        "security/apparmor/label.c:sort_cmp"
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
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584250748,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:107",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:__vec_find",
        "security/apparmor/label.c:__vec_find",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:sort_cmp",
        "security/apparmor/label.c:sort_cmp"
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
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584274054,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:107",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:__vec_find",
        "security/apparmor/label.c:__vec_find",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:sort_cmp",
        "security/apparmor/label.c:sort_cmp"
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
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584660086,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:107",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:__vec_find",
        "security/apparmor/label.c:__vec_find",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:sort_cmp",
        "security/apparmor/label.c:sort_cmp"
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
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585321074,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:107",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:__vec_find",
        "security/apparmor/label.c:__vec_find",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:sort_cmp",
        "security/apparmor/label.c:sort_cmp"
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
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586061138,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:107",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:__vec_find",
        "security/apparmor/label.c:__vec_find",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:sort_cmp",
        "security/apparmor/label.c:sort_cmp"
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
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586296126,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:107",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:__vec_find",
        "security/apparmor/label.c:__vec_find",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:sort_cmp",
        "security/apparmor/label.c:sort_cmp"
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
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586552718,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:107",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:__vec_find",
        "security/apparmor/label.c:__vec_find",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:aa_vec_unique",
        "security/apparmor/label.c:sort_cmp",
        "security/apparmor/label.c:sort_cmp"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495542336,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:107",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:profile_cmp",
        "security/apparmor/label.c:profile_cmp"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228906004,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:107",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:profile_cmp",
        "security/apparmor/label.c:profile_cmp"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289627048,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:107",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274716020,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:107",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:profile_cmp",
        "security/apparmor/label.c:profile_cmp"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int ns_cmp(struct aa_ns * a, struct aa_ns * b)
```

```json
{
  "name": "ns_cmp",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583711710,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:107",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586451520,
      "name": "ns_cmp",
      "external": false,
      "loc": "drivers/nvme/host/core.c:3416",
      "file": "drivers/nvme/host/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586451520,
      "name": "ns_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int ns_cmp(struct aa_ns * a, struct aa_ns * b)
```

```json
{
  "name": "ns_cmp",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583648766,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:107",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586327760,
      "name": "ns_cmp",
      "external": false,
      "loc": "drivers/nvme/host/core.c:3416",
      "file": "drivers/nvme/host/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586327760,
      "name": "ns_cmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583695486,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:107",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ns_cmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583795454,
      "name": "ns_cmp",
      "external": false,
      "loc": "security/apparmor/label.c:107",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_find_merge",
        "security/apparmor/label.c:aa_label_find_merge"
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int ns_cmp(struct aa_ns * a, struct aa_ns * b)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➕</summary>

```c
int ns_cmp(struct aa_ns * a, struct aa_ns * b)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
int ns_cmp(struct aa_ns * a, struct aa_ns * b)
```
</details>
</li>
</ul>
