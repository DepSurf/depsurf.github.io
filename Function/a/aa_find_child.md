# Function: <code>aa_find_child</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582514192,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:409",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582514192,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582750160,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:434",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582750160,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582845328,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:435",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582845328,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582924384,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:331",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582924384,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583083600,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:331",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583083600,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583286560,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:336",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_null_profile"
      ],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583286560,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583404944,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:336",
      "file": "security/apparmor/policy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:aa_new_null_profile",
        "security/apparmor/policy.c:aa_new_null_profile"
      ],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583404944,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583591216,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:331",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583591216,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583697376,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:331",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583697376,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584066240,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:335",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584066240,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584184384,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:335",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584184384,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584211184,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:335",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584211184,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584596544,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:335",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584596544,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585245568,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:378",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585245568,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585978752,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:384",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_learning_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585978752,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586211296,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:422",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_learning_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586211296,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586463840,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:449",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_learning_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586463840,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495490904,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:331",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495490904,
      "name": "aa_find_child",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228858428,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:331",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228858428,
      "name": "aa_find_child",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289554080,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:331",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289554080,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274674880,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:331",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274674880,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583666112,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:331",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583666112,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583603168,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:331",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583603168,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583649888,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:331",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583649888,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct aa_profile * aa_find_child(struct aa_profile * parent, const char * name)
```

```json
{
  "name": "aa_find_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583748224,
      "name": "aa_find_child",
      "external": true,
      "loc": "security/apparmor/policy.c:331",
      "file": "security/apparmor/policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:x_table_lookup",
        "security/apparmor/policy.c:aa_new_null_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748224,
      "name": "aa_find_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
