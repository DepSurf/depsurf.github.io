# Function: <code>__find_child</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582512468,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:381",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_find_child"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582747961,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:406",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_find_child"
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
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582843129,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:407",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_find_child"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582922416,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:319",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582922416,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583081632,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:319",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583081632,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583284704,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:324",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583284704,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583403088,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:324",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583403088,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583589328,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:319",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583589328,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583695488,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:319",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583695488,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584062752,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:323",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584062752,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584181840,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:323",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584181840,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584208640,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:323",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584208640,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584593904,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:323",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584593904,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585242112,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:366",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585242112,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585975104,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:372",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_learning_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585975104,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586207200,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:410",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_learning_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586207200,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586459360,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:437",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_learning_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586459360,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495489192,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:319",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495489192,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228856712,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:319",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228856712,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289551392,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:319",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289551392,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274673260,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:319",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_find_child"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583664224,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:319",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583664224,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583601280,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:319",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583601280,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583648000,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:319",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583648000,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```

```json
{
  "name": "__find_child",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583746336,
      "name": "__find_child",
      "external": false,
      "loc": "security/apparmor/policy.c:319",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__replace_profile",
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_find_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583746336,
      "name": "__find_child",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
struct aa_profile * __find_child(struct list_head * head, const char * name)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct aa_profile * __find_child(struct list_head * head, const char * name)
```
</details>
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
