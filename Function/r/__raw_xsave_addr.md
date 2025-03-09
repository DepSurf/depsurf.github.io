# Function: <code>__raw_xsave_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * __raw_xsave_addr(struct xregs_state * xsave, int xstate_feature_mask)
```

```json
{
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579087296,
      "name": "__raw_xsave_addr",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:775",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves",
        "arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579087296,
      "name": "__raw_xsave_addr",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * __raw_xsave_addr(struct xregs_state * xsave, int xstate_feature_mask)
```

```json
{
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579085472,
      "name": "__raw_xsave_addr",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:780",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves",
        "arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085472,
      "name": "__raw_xsave_addr",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * __raw_xsave_addr(struct xregs_state * xsave, int xstate_feature_mask)
```

```json
{
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579078056,
      "name": "__raw_xsave_addr",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:787",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves",
        "arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copyin_to_xsaves",
        "arch/x86/kernel/fpu/xstate.c:copyout_from_xsaves",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579076000,
      "name": "__raw_xsave_addr.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579077056,
      "name": "__raw_xsave_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * __raw_xsave_addr(struct xregs_state * xsave, int xstate_feature_mask)
```

```json
{
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579087685,
      "name": "__raw_xsave_addr",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:814",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579084768,
      "name": "__raw_xsave_addr.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579085616,
      "name": "__raw_xsave_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * __raw_xsave_addr(struct xregs_state * xsave, int xstate_feature_mask)
```

```json
{
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579093049,
      "name": "__raw_xsave_addr",
      "external": true,
      "loc": "arch/x86/kernel/fpu/xstate.c:814",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090144,
      "name": "__raw_xsave_addr.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    },
    {
      "addr": 18446744071579090992,
      "name": "__raw_xsave_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579098457,
      "name": "__raw_xsave_addr",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:812",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579095456,
      "name": "__raw_xsave_addr.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579108746,
      "name": "__raw_xsave_addr",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:806",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579105904,
      "name": "__raw_xsave_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579110746,
      "name": "__raw_xsave_addr",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:806",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579107728,
      "name": "__raw_xsave_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579123636,
      "name": "__raw_xsave_addr",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:859",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
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
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579123253,
      "name": "__raw_xsave_addr",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:899",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
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
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579130677,
      "name": "__raw_xsave_addr",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:934",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
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
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579153016,
      "name": "__raw_xsave_addr",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:850",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void * __raw_xsave_addr(struct xregs_state * xsave, int xfeature_nr)
```

```json
{
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__raw_xsave_addr",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:931",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579195568,
      "name": "__raw_xsave_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071593826600,
      "name": "__raw_xsave_addr.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void * __raw_xsave_addr(struct xregs_state * xsave, int xfeature_nr)
```

```json
{
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__raw_xsave_addr",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:926",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251632,
      "name": "__raw_xsave_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071595959885,
      "name": "__raw_xsave_addr.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void * __raw_xsave_addr(struct xregs_state * xsave, int xfeature_nr)
```

```json
{
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__raw_xsave_addr",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:933",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258112,
      "name": "__raw_xsave_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071596477220,
      "name": "__raw_xsave_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void * __raw_xsave_addr(struct xregs_state * xsave, int xfeature_nr)
```

```json
{
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__raw_xsave_addr",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:929",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:__copy_xstate_to_uabi_buf",
        "arch/x86/kernel/fpu/xstate.c:get_xsave_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288496,
      "name": "__raw_xsave_addr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    },
    {
      "addr": 18446744071597373005,
      "name": "__raw_xsave_addr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579111130,
      "name": "__raw_xsave_addr",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:806",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108112,
      "name": "__raw_xsave_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579043514,
      "name": "__raw_xsave_addr",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:806",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579040528,
      "name": "__raw_xsave_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579110682,
      "name": "__raw_xsave_addr",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:806",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579107664,
      "name": "__raw_xsave_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__raw_xsave_addr",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579115770,
      "name": "__raw_xsave_addr",
      "external": false,
      "loc": "arch/x86/kernel/fpu/xstate.c:806",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:copy_user_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_kernel_to_xstate",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_user",
        "arch/x86/kernel/fpu/xstate.c:copy_xstate_to_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579112736,
      "name": "__raw_xsave_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 15
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
void * __raw_xsave_addr(struct xregs_state * xsave, int xstate_feature_mask)
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void * __raw_xsave_addr(struct xregs_state * xsave, int xstate_feature_mask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void * __raw_xsave_addr(struct xregs_state * xsave, int xfeature_nr)
```
</details>
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
