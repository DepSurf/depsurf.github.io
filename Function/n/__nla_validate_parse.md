# Function: <code>__nla_validate_parse</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb)
```

```json
{
  "name": "__nla_validate_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nla_validate_parse",
      "external": false,
      "loc": "lib/nlattr.c:357",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:__nla_parse",
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584303216,
      "name": "__nla_validate_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071584304735,
      "name": "__nla_validate_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb)
```

```json
{
  "name": "__nla_validate_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nla_validate_parse",
      "external": false,
      "loc": "lib/nlattr.c:357",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:__nla_parse",
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584437920,
      "name": "__nla_validate_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071584439415,
      "name": "__nla_validate_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb, unsigned int depth)
```

```json
{
  "name": "__nla_validate_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nla_validate_parse",
      "external": false,
      "loc": "lib/nlattr.c:503",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:__nla_parse",
        "lib/nlattr.c:__nla_validate",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585002016,
      "name": "__nla_validate_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
    },
    {
      "addr": 18446744071585002473,
      "name": "__nla_validate_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb, unsigned int depth)
```

```json
{
  "name": "__nla_validate_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nla_validate_parse",
      "external": false,
      "loc": "lib/nlattr.c:558",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:__nla_parse",
        "lib/nlattr.c:__nla_validate",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585122848,
      "name": "__nla_validate_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    },
    {
      "addr": 18446744071591380556,
      "name": "__nla_validate_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb, unsigned int depth)
```

```json
{
  "name": "__nla_validate_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nla_validate_parse",
      "external": false,
      "loc": "lib/nlattr.c:558",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:__nla_parse",
        "lib/nlattr.c:__nla_validate",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585003360,
      "name": "__nla_validate_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071591322943,
      "name": "__nla_validate_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb, unsigned int depth)
```

```json
{
  "name": "__nla_validate_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nla_validate_parse",
      "external": false,
      "loc": "lib/nlattr.c:558",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:__nla_parse",
        "lib/nlattr.c:__nla_validate",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585444768,
      "name": "__nla_validate_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071592336828,
      "name": "__nla_validate_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb, unsigned int depth)
```

```json
{
  "name": "__nla_validate_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nla_validate_parse",
      "external": false,
      "loc": "lib/nlattr.c:558",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:__nla_parse",
        "lib/nlattr.c:__nla_validate",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586586080,
      "name": "__nla_validate_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    },
    {
      "addr": 18446744071594197302,
      "name": "__nla_validate_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb, unsigned int depth)
```

```json
{
  "name": "__nla_validate_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587826496,
      "name": "__nla_validate_parse",
      "external": false,
      "loc": "lib/nlattr.c:572",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:__nla_parse",
        "lib/nlattr.c:__nla_validate",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587826496,
      "name": "__nla_validate_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb, unsigned int depth)
```

```json
{
  "name": "__nla_validate_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588097856,
      "name": "__nla_validate_parse",
      "external": false,
      "loc": "lib/nlattr.c:572",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:__nla_parse",
        "lib/nlattr.c:__nla_validate",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588097856,
      "name": "__nla_validate_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb, unsigned int depth)
```

```json
{
  "name": "__nla_validate_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588433952,
      "name": "__nla_validate_parse",
      "external": false,
      "loc": "lib/nlattr.c:604",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:__nla_parse",
        "lib/nlattr.c:__nla_validate",
        "lib/nlattr.c:validate_nla",
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588433952,
      "name": "__nla_validate_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
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
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb)
```

```json
{
  "name": "__nla_validate_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496323200,
      "name": "__nla_validate_parse",
      "external": false,
      "loc": "lib/nlattr.c:357",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:__nla_parse",
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496323200,
      "name": "__nla_validate_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb)
```

```json
{
  "name": "__nla_validate_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229657932,
      "name": "__nla_validate_parse",
      "external": false,
      "loc": "lib/nlattr.c:357",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:__nla_parse",
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229657932,
      "name": "__nla_validate_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb)
```

```json
{
  "name": "__nla_validate_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290641280,
      "name": "__nla_validate_parse",
      "external": false,
      "loc": "lib/nlattr.c:357",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:__nla_parse",
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290641280,
      "name": "__nla_validate_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
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
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb)
```

```json
{
  "name": "__nla_validate_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275375048,
      "name": "__nla_validate_parse",
      "external": false,
      "loc": "lib/nlattr.c:357",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:__nla_parse",
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275375048,
      "name": "__nla_validate_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb)
```

```json
{
  "name": "__nla_validate_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nla_validate_parse",
      "external": false,
      "loc": "lib/nlattr.c:357",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:__nla_parse",
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584406656,
      "name": "__nla_validate_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071584408151,
      "name": "__nla_validate_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb)
```

```json
{
  "name": "__nla_validate_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nla_validate_parse",
      "external": false,
      "loc": "lib/nlattr.c:357",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:__nla_parse",
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584341856,
      "name": "__nla_validate_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071584343351,
      "name": "__nla_validate_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb)
```

```json
{
  "name": "__nla_validate_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nla_validate_parse",
      "external": false,
      "loc": "lib/nlattr.c:357",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:__nla_parse",
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584389568,
      "name": "__nla_validate_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071584391063,
      "name": "__nla_validate_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb)
```

```json
{
  "name": "__nla_validate_parse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__nla_validate_parse",
      "external": false,
      "loc": "lib/nlattr.c:357",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nlattr.c:__nla_parse",
        "lib/nlattr.c:validate_nla"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584495632,
      "name": "__nla_validate_parse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    },
    {
      "addr": 18446744071584497127,
      "name": "__nla_validate_parse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int __nla_validate_parse(const struct nlattr * head, int len, int maxtype, const struct nla_policy * policy, unsigned int validate, struct netlink_ext_ack * extack, struct nlattr * * tb)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int depth</code>
</li>
</ul>
</details>
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
