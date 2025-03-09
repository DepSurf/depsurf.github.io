# Function: <code>ptrace_has_cap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool ptrace_has_cap(const struct cred * tcred, unsigned int mode)
```

```json
{
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579412464,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:210",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579412464,
      "name": "ptrace_has_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
bool ptrace_has_cap(const struct cred * tcred, unsigned int mode)
```

```json
{
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579424736,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:209",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424736,
      "name": "ptrace_has_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
int ptrace_has_cap(struct user_namespace * ns, unsigned int mode)
```

```json
{
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579445792,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:247",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579445792,
      "name": "ptrace_has_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ptrace_has_cap(struct user_namespace * ns, unsigned int mode)
```

```json
{
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579433824,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:262",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433824,
      "name": "ptrace_has_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ptrace_has_cap(struct user_namespace * ns, unsigned int mode)
```

```json
{
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579462176,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:262",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462176,
      "name": "ptrace_has_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ptrace_has_cap(struct user_namespace * ns, unsigned int mode)
```

```json
{
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579475168,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:262",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579475168,
      "name": "ptrace_has_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ptrace_has_cap(struct user_namespace * ns, unsigned int mode)
```

```json
{
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579509024,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:262",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509024,
      "name": "ptrace_has_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ptrace_has_cap(struct user_namespace * ns, unsigned int mode)
```

```json
{
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579528656,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:267",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528656,
      "name": "ptrace_has_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
bool ptrace_has_cap(const struct cred * cred, struct user_namespace * ns, unsigned int mode)
```

```json
{
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579554096,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:267",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554096,
      "name": "ptrace_has_cap",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579586639,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:267",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
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
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579566699,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:267",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
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
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579572191,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:284",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
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
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579646159,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:284",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
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
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579742267,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:278",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
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
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579873675,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:278",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
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
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579923531,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:279",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
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
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579962779,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:268",
      "file": "kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
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
bool ptrace_has_cap(const struct cred * cred, struct user_namespace * ns, unsigned int mode)
```

```json
{
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490707168,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:267",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490707168,
      "name": "ptrace_has_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
bool ptrace_has_cap(const struct cred * cred, struct user_namespace * ns, unsigned int mode)
```

```json
{
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224769964,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:267",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224769964,
      "name": "ptrace_has_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
bool ptrace_has_cap(const struct cred * cred, struct user_namespace * ns, unsigned int mode)
```

```json
{
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283531280,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:267",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283531280,
      "name": "ptrace_has_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
bool ptrace_has_cap(const struct cred * cred, struct user_namespace * ns, unsigned int mode)
```

```json
{
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271431218,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:267",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271431218,
      "name": "ptrace_has_cap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
bool ptrace_has_cap(const struct cred * cred, struct user_namespace * ns, unsigned int mode)
```

```json
{
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579530400,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:267",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530400,
      "name": "ptrace_has_cap",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool ptrace_has_cap(const struct cred * cred, struct user_namespace * ns, unsigned int mode)
```

```json
{
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579459200,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:267",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579459200,
      "name": "ptrace_has_cap",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool ptrace_has_cap(const struct cred * cred, struct user_namespace * ns, unsigned int mode)
```

```json
{
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527680,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:267",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527680,
      "name": "ptrace_has_cap",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool ptrace_has_cap(const struct cred * cred, struct user_namespace * ns, unsigned int mode)
```

```json
{
  "name": "ptrace_has_cap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579560784,
      "name": "ptrace_has_cap",
      "external": false,
      "loc": "kernel/ptrace.c:267",
      "file": "kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:__ptrace_may_access",
        "kernel/ptrace.c:__ptrace_may_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579560784,
      "name": "ptrace_has_cap",
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

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace * ns</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct cred * tcred</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred * cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>ns, mode</code> ➡️ <code>cred, ns, mode</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
bool ptrace_has_cap(const struct cred * cred, struct user_namespace * ns, unsigned int mode)
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
