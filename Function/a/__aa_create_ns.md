# Function: <code>__aa_create_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582843072,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:187",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582843072,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582939072,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:188",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:aa_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582939072,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
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
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582957712,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:246",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582957712,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583119904,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:246",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583119904,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:246",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583325744,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071583327239,
      "name": "__aa_create_ns.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:246",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583444304,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
    },
    {
      "addr": 18446744071583445799,
      "name": "__aa_create_ns.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:242",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629168,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071583630832,
      "name": "__aa_create_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:242",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583735344,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071583737008,
      "name": "__aa_create_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:242",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584118928,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
    },
    {
      "addr": 18446744071584121216,
      "name": "__aa_create_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:242",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584237872,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
    },
    {
      "addr": 18446744071591368635,
      "name": "__aa_create_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:242",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584262768,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
    },
    {
      "addr": 18446744071591311307,
      "name": "__aa_create_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:242",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584648720,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
    },
    {
      "addr": 18446744071592306441,
      "name": "__aa_create_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:257",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585306272,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
    },
    {
      "addr": 18446744071594087995,
      "name": "__aa_create_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586045328,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:256",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586045328,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586280336,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:256",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586280336,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586537248,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:219",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586537248,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495532136,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:242",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495532136,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228898396,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:242",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228898396,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289613632,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:242",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289613632,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274708376,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:242",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274708376,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:242",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583704080,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071583705744,
      "name": "__aa_create_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:242",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583641136,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071583642800,
      "name": "__aa_create_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:242",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583687856,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071583689520,
      "name": "__aa_create_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```

```json
{
  "name": "__aa_create_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__aa_create_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:242",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_prepare_ns",
        "security/apparmor/policy_ns.c:__aa_find_or_create_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583787680,
      "name": "__aa_create_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071583789408,
      "name": "__aa_create_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct aa_ns * __aa_create_ns(struct aa_ns * parent, const char * name, struct dentry * dir)
```
</details>
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
