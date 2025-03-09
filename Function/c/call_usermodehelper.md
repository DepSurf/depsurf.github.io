# Function: <code>call_usermodehelper</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int call_usermodehelper(char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579462448,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/kmod.c:616",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_do_trigger",
        "kernel/reboot.c:run_cmd",
        "kernel/cgroup.c:cgroup_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462448,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int call_usermodehelper(char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579475696,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/kmod.c:616",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_do_trigger",
        "kernel/reboot.c:run_cmd",
        "kernel/cgroup.c:cgroup_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579475696,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int call_usermodehelper(char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579496096,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/kmod.c:616",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_do_trigger",
        "kernel/reboot.c:run_cmd",
        "kernel/cgroup.c:cgroup_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496096,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579484576,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/kmod.c:647",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_do_trigger",
        "kernel/reboot.c:run_cmd",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579484576,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579512480,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:478",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_do_trigger",
        "kernel/reboot.c:run_cmd",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512480,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579538688,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:596",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_do_trigger",
        "kernel/reboot.c:run_cmd",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538688,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579575280,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:617",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger",
        "kernel/reboot.c:run_cmd",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579575280,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579598736,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:618",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger",
        "kernel/reboot.c:run_cmd",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598736,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579624592,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:618",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger",
        "kernel/reboot.c:run_cmd",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624592,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653744,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:629",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger",
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:poweroff_work_func",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653744,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579634080,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:472",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger",
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:poweroff_work_func",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579634080,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579640736,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:474",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger",
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:poweroff_work_func",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640736,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579717344,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:474",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger",
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:poweroff_work_func",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717344,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579819680,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:474",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger",
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:poweroff_work_func",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579819680,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579956080,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:486",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger",
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:poweroff_work_func",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579956080,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580006416,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:483",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger",
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:poweroff_work_func",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006416,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580046080,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:483",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger",
        "kernel/reboot.c:reboot_work_func",
        "kernel/reboot.c:poweroff_work_func",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046080,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490790456,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:618",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:run_cmd",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490790456,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224826808,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:618",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:run_cmd",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224826808,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283617680,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:618",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:run_cmd",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283617680,
      "name": "call_usermodehelper",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271471590,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:618",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:run_cmd",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271471590,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579600896,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:618",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger",
        "kernel/reboot.c:run_cmd",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579600896,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579529536,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:618",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger",
        "kernel/reboot.c:run_cmd",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529536,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579598176,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:618",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger",
        "kernel/reboot.c:run_cmd",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598176,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int call_usermodehelper(const char * path, char * * argv, char * * envp, int wait)
```

```json
{
  "name": "call_usermodehelper",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579632672,
      "name": "call_usermodehelper",
      "external": true,
      "loc": "kernel/umh.c:618",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_do_trigger",
        "kernel/reboot.c:run_cmd",
        "kernel/cgroup/cgroup-v1.c:cgroup1_release_agent",
        "security/tomoyo/load_policy.c:tomoyo_load_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579632672,
      "name": "call_usermodehelper",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * path</code> ➡️ <code>const char * path</code>
</li>
</ul>
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
