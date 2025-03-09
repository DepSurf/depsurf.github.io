# Function: <code>strnstr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582981632,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:835",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:regex_match_middle",
        "security/apparmor/policy.c:__lookupn_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582981632,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583270816,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:832",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:regex_match_middle",
        "security/apparmor/policy.c:__lookupn_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583270816,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583389584,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:832",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:regex_match_middle",
        "security/apparmor/policy.c:__lookupn_profile"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389584,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588246000,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:858",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:regex_match_middle",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588246000,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588797424,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:925",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:regex_match_middle",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588797424,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589175520,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:925",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589175520,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589405440,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:926",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589405440,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589861248,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:988",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589861248,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590086736,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:969",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590086736,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585084592,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:1026",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585084592,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585233744,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:1022",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585233744,
      "name": "strnstr",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585116592,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:1022",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585116592,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585565296,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:1038",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585565296,
      "name": "strnstr",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586718240,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:851",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718240,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595880592,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:777",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595880592,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596397824,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:775",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596397824,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597293056,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:760",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597293056,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503865360,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:969",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503865360,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236492596,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:969",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236492596,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297724512,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:969",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297724512,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279760546,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:969",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279760546,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589688992,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:969",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589688992,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589414784,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:969",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589414784,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590132368,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:969",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590132368,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
char * strnstr(const char * s1, const char * s2, size_t len)
```

```json
{
  "name": "strnstr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590182752,
      "name": "strnstr",
      "external": true,
      "loc": "lib/string.c:969",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy.c:__lookupn_profile",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns",
        "security/apparmor/policy_ns.c:__aa_lookupn_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590182752,
      "name": "strnstr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
