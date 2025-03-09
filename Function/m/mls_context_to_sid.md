# Function: <code>mls_context_to_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mls_context_to_sid(struct policydb * pol, char oldc, char * * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582367312,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582367312,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mls_context_to_sid(struct policydb * pol, char oldc, char * * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582588432,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582588432,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 819
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mls_context_to_sid(struct policydb * pol, char oldc, char * * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582681664,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582681664,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 819
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
int mls_context_to_sid(struct policydb * pol, char oldc, char * * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582774528,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582774528,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 821
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
int mls_context_to_sid(struct policydb * pol, char oldc, char * * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582930592,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:235",
      "file": "security/selinux/ss/mls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582930592,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 821
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
int mls_context_to_sid(struct policydb * pol, char oldc, char * * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583130240,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:236",
      "file": "security/selinux/ss/mls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583130240,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 819
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583247166,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_from_string"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583244864,
      "name": "mls_context_to_sid.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
    },
    {
      "addr": 18446744071583246928,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583434095,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_from_string"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583431808,
      "name": "mls_context_to_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
    },
    {
      "addr": 18446744071583433856,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583539999,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_from_string"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583537712,
      "name": "mls_context_to_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
    },
    {
      "addr": 18446744071583539760,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583889599,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_from_string"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583887232,
      "name": "mls_context_to_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    },
    {
      "addr": 18446744071583889504,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584009711,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_from_string"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584007360,
      "name": "mls_context_to_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    },
    {
      "addr": 18446744071584009616,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584037775,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_from_string"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584035392,
      "name": "mls_context_to_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    },
    {
      "addr": 18446744071584037680,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584408895,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_from_string"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584406336,
      "name": "mls_context_to_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
    },
    {
      "addr": 18446744071584408800,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585034992,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:233",
      "file": "security/selinux/ss/mls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585034992,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585753504,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:233",
      "file": "security/selinux/ss/mls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585753504,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585984160,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:233",
      "file": "security/selinux/ss/mls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585984160,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 742
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
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586231488,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:233",
      "file": "security/selinux/ss/mls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586231488,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 745
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495311020,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_from_string"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495308512,
      "name": "mls_context_to_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
    },
    {
      "addr": 18446603336495310688,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228689588,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_from_string"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228687248,
      "name": "mls_context_to_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    },
    {
      "addr": 3228689304,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289299992,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_from_string"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289296448,
      "name": "mls_context_to_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
    },
    {
      "addr": 13835058055289299552,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274528238,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_from_string"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274526052,
      "name": "mls_context_to_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    },
    {
      "addr": 18446743936274527988,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583508735,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_from_string"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583506448,
      "name": "mls_context_to_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
    },
    {
      "addr": 18446744071583508496,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583445791,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_from_string"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583443504,
      "name": "mls_context_to_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
    },
    {
      "addr": 18446744071583445552,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583492511,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_from_string"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583490224,
      "name": "mls_context_to_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
    },
    {
      "addr": 18446744071583492272,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mls_context_to_sid(struct policydb * pol, char oldc, char * scontext, struct context * context, struct sidtab * s, u32 def_sid)
```

```json
{
  "name": "mls_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583588879,
      "name": "mls_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/mls.c:234",
      "file": "security/selinux/ss/mls.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/ss/mls.c:mls_from_string"
      ],
      "caller_func": [
        "security/selinux/ss/services.c:string_to_context_struct",
        "security/selinux/ss/mls.c:mls_from_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583586592,
      "name": "mls_context_to_sid.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
    },
    {
      "addr": 18446744071583588640,
      "name": "mls_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * * scontext</code> ➡️ <code>char * scontext</code>
</li>
</ul>
</details>
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
