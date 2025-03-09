# Function: <code>tomoyo_get_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582453728,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:147",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582453728,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582675904,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:147",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582675904,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582768960,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:147",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582768960,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582861328,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:147",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582861328,
      "name": "tomoyo_get_name",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583018272,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:148",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583018272,
      "name": "tomoyo_get_name",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583218880,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:148",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583218880,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583335904,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:148",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583335904,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583523376,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:152",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583523376,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583629264,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:152",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629264,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583986480,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:152",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_update_manager_entry",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_transit_preference",
        "security/tomoyo/condition.c:tomoyo_parse_envp",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_env",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986480,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584106240,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:152",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_update_manager_entry",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_transit_preference",
        "security/tomoyo/condition.c:tomoyo_parse_envp",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_env",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584106240,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584133760,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:152",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584133760,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584516752,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:152",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584516752,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 447
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585154992,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:152",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585154992,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585880736,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:152",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585880736,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586112640,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:152",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586112640,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586361936,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:152",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586361936,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495415672,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:152",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495415672,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228785720,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:152",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228785720,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289450768,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:152",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289450768,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1072
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274612782,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:152",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274612782,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583598000,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:152",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583598000,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583535056,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:152",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583535056,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583581776,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:152",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583581776,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
const struct tomoyo_path_info * tomoyo_get_name(const char * name)
```

```json
{
  "name": "tomoyo_get_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583678864,
      "name": "tomoyo_get_name",
      "external": true,
      "loc": "security/tomoyo/memory.c:152",
      "file": "security/tomoyo/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_manager",
        "security/tomoyo/common.c:tomoyo_write_profile",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_condition",
        "security/tomoyo/condition.c:tomoyo_get_dqword",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_aggregator",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/domain.c:tomoyo_write_transition_control",
        "security/tomoyo/environ.c:tomoyo_write_misc",
        "security/tomoyo/group.c:tomoyo_write_group",
        "security/tomoyo/memory.c:tomoyo_get_group",
        "security/tomoyo/memory.c:tomoyo_mm_init",
        "security/tomoyo/util.c:tomoyo_parse_name_union",
        "security/tomoyo/util.c:tomoyo_get_domainname"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583678864,
      "name": "tomoyo_get_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
