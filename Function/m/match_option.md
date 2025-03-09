# Function: <code>match_option</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "match_option",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602654226,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:136",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool match_option(const char * arg, int arglen, const char * opt)
```

```json
{
  "name": "match_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579123004,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:259",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579123004,
      "name": "match_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
bool match_option(const char * arg, int arglen, const char * opt)
```

```json
{
  "name": "match_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579129596,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:239",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579129596,
      "name": "match_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
bool match_option(const char * arg, int arglen, const char * opt)
```

```json
{
  "name": "match_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579139752,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:393",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139752,
      "name": "match_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
bool match_option(const char * arg, int arglen, const char * opt)
```

```json
{
  "name": "match_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579141944,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:515",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579141944,
      "name": "match_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool match_option(const char * arg, int arglen, const char * opt)
```

```json
{
  "name": "match_option",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579158491,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:618",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:ssb_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation"
      ]
    },
    {
      "addr": 18446744071609078040,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:996",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579158491,
      "name": "match_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool match_option(const char * arg, int arglen, const char * opt)
```

```json
{
  "name": "match_option",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591252088,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:616",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:ssb_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation"
      ]
    },
    {
      "addr": 18446744071612141776,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:997",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:split_lock_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591252088,
      "name": "match_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool match_option(const char * arg, int arglen, const char * opt)
```

```json
{
  "name": "match_option",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591195692,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:616",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation"
      ]
    },
    {
      "addr": 18446744071614281666,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:1002",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:sld_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591195692,
      "name": "match_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool match_option(const char * arg, int arglen, const char * opt)
```

```json
{
  "name": "match_option",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592061887,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:680",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation"
      ]
    },
    {
      "addr": 18446744071615204933,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:1009",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:sld_state_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592061887,
      "name": "match_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
bool match_option(const char * arg, int arglen, const char * opt)
```

```json
{
  "name": "match_option",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593828437,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1005",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation"
      ]
    },
    {
      "addr": 18446744071616977914,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:1039",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:sld_state_setup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593828437,
      "name": "match_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "match_option",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627592987,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1042",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627598751,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:1205",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:sld_state_setup"
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
  "name": "match_option",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619346827,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1154",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619352831,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:1205",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:sld_state_setup"
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
  "name": "match_option",
  "collision_type": "Static-Static Collision",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621641675,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:1219",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621646847,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel.c:1021",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:sld_state_setup"
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool match_option(const char * arg, int arglen, const char * opt)
```

```json
{
  "name": "match_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579142312,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:515",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579142312,
      "name": "match_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
bool match_option(const char * arg, int arglen, const char * opt)
```

```json
{
  "name": "match_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579073560,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:515",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073560,
      "name": "match_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
bool match_option(const char * arg, int arglen, const char * opt)
```

```json
{
  "name": "match_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579141864,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:515",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579141864,
      "name": "match_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
bool match_option(const char * arg, int arglen, const char * opt)
```

```json
{
  "name": "match_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579147000,
      "name": "match_option",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:515",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579147000,
      "name": "match_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
bool match_option(const char * arg, int arglen, const char * opt)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool match_option(const char * arg, int arglen, const char * opt)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool match_option(const char * arg, int arglen, const char * opt)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool match_option(const char * arg, int arglen, const char * opt)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool match_option(const char * arg, int arglen, const char * opt)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool match_option(const char * arg, int arglen, const char * opt)
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
