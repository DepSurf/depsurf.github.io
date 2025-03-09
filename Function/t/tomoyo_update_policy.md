# Function: <code>tomoyo_update_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582438576,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:28",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582438576,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582660336,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:28",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582660336,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582753392,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:28",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582753392,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582845664,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:30",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582845664,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583002496,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002496,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583203136,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583203136,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583320048,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583320048,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583507680,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583507680,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583613568,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583613568,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583970592,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_update_manager_entry",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583970592,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584090448,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_update_manager_entry",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584090448,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584117728,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584117728,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592304054,
      "name": "tomoyo_update_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071584498976,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594085275,
      "name": "tomoyo_update_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071585135856,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596099267,
      "name": "tomoyo_update_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071585860560,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596622365,
      "name": "tomoyo_update_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071586092512,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597528674,
      "name": "tomoyo_update_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071586341616,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495396304,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495396304,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228769076,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228769076,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289423824,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289423824,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274596904,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274596904,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583582304,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583582304,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583519360,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583519360,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583566080,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583566080,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int tomoyo_update_policy(struct tomoyo_acl_head * new_entry, const int size, struct tomoyo_acl_param * param, bool (*)(const struct tomoyo_acl_head *, const struct tomoyo_acl_head *) check_duplicate)
```

```json
{
  "name": "tomoyo_update_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583663216,
      "name": "tomoyo_update_policy",
      "external": true,
      "loc": "security/tomoyo/domain.c:31",
      "file": "security/tomoyo/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/group.c:tomoyo_write_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583663216,
      "name": "tomoyo_update_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
