# Function: <code>has_capability_noaudit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579412416,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:359",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:oom_score_adj_write",
        "security/integrity/ima/ima_policy.c:ima_match_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579412416,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579424688,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:359",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "lib/vsprintf.c:pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424688,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579444928,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:360",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "lib/vsprintf.c:pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444928,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579432960,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:360",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "lib/vsprintf.c:pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432960,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461312,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:361",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461312,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579474896,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:361",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579474896,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508576,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:361",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508576,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527568,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:359",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527568,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579553648,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:359",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579553648,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579585136,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:359",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585136,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565184,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:359",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565184,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579570560,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:359",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570560,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644480,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:359",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644480,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579739328,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:359",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_match_rules",
        "security/integrity/ima/ima_policy.c:ima_match_rules",
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579739328,
      "name": "has_capability_noaudit",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579870336,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:359",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_match_rules",
        "security/integrity/ima/ima_policy.c:ima_match_rules",
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870336,
      "name": "has_capability_noaudit",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579919648,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:345",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_match_rules",
        "security/integrity/ima/ima_policy.c:ima_match_rules",
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579919648,
      "name": "has_capability_noaudit",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579958896,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:345",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579958896,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490706808,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:359",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490706808,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224769688,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:359",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224769688,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283530512,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:359",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283530512,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271430896,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:359",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271430896,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579529952,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:359",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529952,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579458752,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:359",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579458752,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527232,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:359",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527232,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
bool has_capability_noaudit(struct task_struct * t, int cap)
```

```json
{
  "name": "has_capability_noaudit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579560320,
      "name": "has_capability_noaudit",
      "external": true,
      "loc": "kernel/capability.c:359",
      "file": "kernel/capability.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:__set_oom_adj",
        "fs/proc/base.c:__set_oom_adj",
        "security/integrity/ima/ima_policy.c:ima_match_policy",
        "lib/vsprintf.c:restricted_pointer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579560320,
      "name": "has_capability_noaudit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
