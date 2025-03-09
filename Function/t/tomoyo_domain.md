# Function: <code>tomoyo_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582430666,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1203",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_write_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582440613,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1203",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_find_next_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582461254,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1203",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_read_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582463275,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1203",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/tomoyo.c:tomoyo_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582468111,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1203",
      "file": "security/tomoyo/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/util.c:tomoyo_init_request_info"
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
  "name": "tomoyo_domain",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582652346,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1203",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_write_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582663553,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1203",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582683894,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1203",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_read_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582685515,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1203",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/tomoyo.c:tomoyo_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582690319,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1203",
      "file": "security/tomoyo/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/util.c:tomoyo_init_request_info"
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
  "name": "tomoyo_domain",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582745402,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1203",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_write_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582756609,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1203",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582776934,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1203",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_read_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582778555,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1203",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/tomoyo.c:tomoyo_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582783375,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1203",
      "file": "security/tomoyo/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/util.c:tomoyo_init_request_info"
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
  "name": "tomoyo_domain",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582837698,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1220",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_write_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582848845,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1220",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582869334,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1220",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_read_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582871032,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1220",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/tomoyo.c:tomoyo_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582875935,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1220",
      "file": "security/tomoyo/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/util.c:tomoyo_init_request_info"
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
  "name": "tomoyo_domain",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582994548,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1222",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_write_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583005789,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1222",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583026310,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1222",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_read_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583028013,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1222",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/tomoyo.c:tomoyo_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583032687,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1222",
      "file": "security/tomoyo/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/util.c:tomoyo_init_request_info"
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
  "name": "tomoyo_domain",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583194960,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1204",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_write_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583206465,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1204",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583226805,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1204",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_read_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583228463,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1204",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/tomoyo.c:tomoyo_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583233141,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1204",
      "file": "security/tomoyo/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/util.c:tomoyo_init_request_info"
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
  "name": "tomoyo_domain",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583311424,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1218",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_write_control"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583323404,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1218",
      "file": "security/tomoyo/domain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604857012,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1218",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583345567,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1218",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/tomoyo.c:tomoyo_file_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583350421,
      "name": "tomoyo_domain",
      "external": false,
      "loc": "security/tomoyo/common.h:1218",
      "file": "security/tomoyo/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/util.c:tomoyo_init_request_info"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct tomoyo_domain_info * tomoyo_domain()
```

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583533392,
      "name": "tomoyo_domain",
      "external": true,
      "loc": "security/tomoyo/tomoyo.c:16",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self",
        "security/tomoyo/util.c:tomoyo_init_request_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583533392,
      "name": "tomoyo_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct tomoyo_domain_info * tomoyo_domain()
```

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583639152,
      "name": "tomoyo_domain",
      "external": true,
      "loc": "security/tomoyo/tomoyo.c:16",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self",
        "security/tomoyo/util.c:tomoyo_init_request_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583639152,
      "name": "tomoyo_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct tomoyo_domain_info * tomoyo_domain()
```

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583996512,
      "name": "tomoyo_domain",
      "external": true,
      "loc": "security/tomoyo/tomoyo.c:16",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_manager",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_namespace_jump",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self",
        "security/tomoyo/util.c:tomoyo_init_request_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583996512,
      "name": "tomoyo_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct tomoyo_domain_info * tomoyo_domain()
```

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584116096,
      "name": "tomoyo_domain",
      "external": true,
      "loc": "security/tomoyo/tomoyo.c:16",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_manager",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_namespace_jump",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self",
        "security/tomoyo/util.c:tomoyo_init_request_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584116096,
      "name": "tomoyo_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct tomoyo_domain_info * tomoyo_domain()
```

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584143552,
      "name": "tomoyo_domain",
      "external": true,
      "loc": "security/tomoyo/tomoyo.c:16",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self",
        "security/tomoyo/util.c:tomoyo_init_request_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584143552,
      "name": "tomoyo_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct tomoyo_domain_info * tomoyo_domain()
```

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584527376,
      "name": "tomoyo_domain",
      "external": true,
      "loc": "security/tomoyo/tomoyo.c:16",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_manager",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self",
        "security/tomoyo/util.c:tomoyo_init_request_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584527376,
      "name": "tomoyo_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct tomoyo_domain_info * tomoyo_domain()
```

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585166864,
      "name": "tomoyo_domain",
      "external": true,
      "loc": "security/tomoyo/tomoyo.c:16",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_manager",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self",
        "security/tomoyo/util.c:tomoyo_init_request_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585166864,
      "name": "tomoyo_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct tomoyo_domain_info * tomoyo_domain()
```

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585893712,
      "name": "tomoyo_domain",
      "external": true,
      "loc": "security/tomoyo/tomoyo.c:17",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_manager",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self",
        "security/tomoyo/util.c:tomoyo_init_request_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585893712,
      "name": "tomoyo_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct tomoyo_domain_info * tomoyo_domain()
```

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586125616,
      "name": "tomoyo_domain",
      "external": true,
      "loc": "security/tomoyo/tomoyo.c:17",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_manager",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self",
        "security/tomoyo/util.c:tomoyo_init_request_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586125616,
      "name": "tomoyo_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct tomoyo_domain_info * tomoyo_domain()
```

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586374912,
      "name": "tomoyo_domain",
      "external": true,
      "loc": "security/tomoyo/tomoyo.c:17",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_manager",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self",
        "security/tomoyo/tomoyo.c:tomoyo_file_open",
        "security/tomoyo/util.c:tomoyo_init_request_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586374912,
      "name": "tomoyo_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
struct tomoyo_domain_info * tomoyo_domain()
```

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495428728,
      "name": "tomoyo_domain",
      "external": true,
      "loc": "security/tomoyo/tomoyo.c:16",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self",
        "security/tomoyo/util.c:tomoyo_init_request_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495428728,
      "name": "tomoyo_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct tomoyo_domain_info * tomoyo_domain()
```

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228797540,
      "name": "tomoyo_domain",
      "external": true,
      "loc": "security/tomoyo/tomoyo.c:16",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self",
        "security/tomoyo/util.c:tomoyo_init_request_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228797540,
      "name": "tomoyo_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct tomoyo_domain_info * tomoyo_domain()
```

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289468032,
      "name": "tomoyo_domain",
      "external": true,
      "loc": "security/tomoyo/tomoyo.c:16",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self",
        "security/tomoyo/util.c:tomoyo_init_request_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289468032,
      "name": "tomoyo_domain",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct tomoyo_domain_info * tomoyo_domain()
```

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274622552,
      "name": "tomoyo_domain",
      "external": true,
      "loc": "security/tomoyo/tomoyo.c:16",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self",
        "security/tomoyo/util.c:tomoyo_init_request_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274622900,
      "name": "tomoyo_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct tomoyo_domain_info * tomoyo_domain()
```

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583607888,
      "name": "tomoyo_domain",
      "external": true,
      "loc": "security/tomoyo/tomoyo.c:16",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self",
        "security/tomoyo/util.c:tomoyo_init_request_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583607888,
      "name": "tomoyo_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct tomoyo_domain_info * tomoyo_domain()
```

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583544944,
      "name": "tomoyo_domain",
      "external": true,
      "loc": "security/tomoyo/tomoyo.c:16",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self",
        "security/tomoyo/util.c:tomoyo_init_request_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583544944,
      "name": "tomoyo_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct tomoyo_domain_info * tomoyo_domain()
```

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583591664,
      "name": "tomoyo_domain",
      "external": true,
      "loc": "security/tomoyo/tomoyo.c:16",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self",
        "security/tomoyo/util.c:tomoyo_init_request_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583591664,
      "name": "tomoyo_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct tomoyo_domain_info * tomoyo_domain()
```

```json
{
  "name": "tomoyo_domain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583688752,
      "name": "tomoyo_domain",
      "external": true,
      "loc": "security/tomoyo/tomoyo.c:16",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/domain.c:tomoyo_find_next_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/domain.c:tomoyo_assign_domain",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_read_self",
        "security/tomoyo/util.c:tomoyo_init_request_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583688752,
      "name": "tomoyo_domain",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct tomoyo_domain_info * tomoyo_domain()
```
</details>
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
