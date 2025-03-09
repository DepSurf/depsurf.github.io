# Function: <code>del_usage_links</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579923930,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1665",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:free_module"
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
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579951539,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1670",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:mod_sysfs_teardown"
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
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579982739,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1662",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:mod_sysfs_teardown"
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
void del_usage_links(struct module * mod)
```

```json
{
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579981184,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1664",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:mod_sysfs_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981184,
      "name": "del_usage_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void del_usage_links(struct module * mod)
```

```json
{
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580027696,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1672",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:load_module",
        "kernel/module.c:mod_sysfs_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027696,
      "name": "del_usage_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void del_usage_links(struct module * mod)
```

```json
{
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580083296,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1671",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580083296,
      "name": "del_usage_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void del_usage_links(struct module * mod)
```

```json
{
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580130656,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1672",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580130656,
      "name": "del_usage_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void del_usage_links(struct module * mod)
```

```json
{
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580177520,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1667",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580177520,
      "name": "del_usage_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void del_usage_links(struct module * mod)
```

```json
{
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580225408,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1722",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580225408,
      "name": "del_usage_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580303146,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1744",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup"
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
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580284730,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1805",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup"
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
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580290586,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1715",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup"
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
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580442602,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1717",
      "file": "kernel/module.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup"
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
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580494634,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module/sysfs.c:243",
      "file": "kernel/module/sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "kernel/module/sysfs.c:mod_sysfs_setup"
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
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580746458,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module/sysfs.c:243",
      "file": "kernel/module/sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "kernel/module/sysfs.c:mod_sysfs_setup"
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
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580828890,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module/sysfs.c:243",
      "file": "kernel/module/sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "kernel/module/sysfs.c:mod_sysfs_setup"
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
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580918314,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module/sysfs.c:243",
      "file": "kernel/module/sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/module/sysfs.c:mod_sysfs_teardown",
        "kernel/module/sysfs.c:mod_sysfs_setup"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void del_usage_links(struct module * mod)
```

```json
{
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491466264,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1722",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:free_module",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491466264,
      "name": "del_usage_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void del_usage_links(struct module * mod)
```

```json
{
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225449836,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1722",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:free_module",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225449836,
      "name": "del_usage_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void del_usage_links(struct module * mod)
```

```json
{
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284414848,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1722",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284414848,
      "name": "del_usage_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void del_usage_links(struct module * mod)
```

```json
{
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271917702,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1722",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:free_module",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271917702,
      "name": "del_usage_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void del_usage_links(struct module * mod)
```

```json
{
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580194208,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1722",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580194208,
      "name": "del_usage_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void del_usage_links(struct module * mod)
```

```json
{
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580141648,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1722",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141648,
      "name": "del_usage_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void del_usage_links(struct module * mod)
```

```json
{
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580185680,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1722",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580185680,
      "name": "del_usage_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void del_usage_links(struct module * mod)
```

```json
{
  "name": "del_usage_links",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580237920,
      "name": "del_usage_links",
      "external": false,
      "loc": "kernel/module.c:1722",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:mod_sysfs_teardown",
        "kernel/module.c:mod_sysfs_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580237920,
      "name": "del_usage_links",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void del_usage_links(struct module * mod)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void del_usage_links(struct module * mod)
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
