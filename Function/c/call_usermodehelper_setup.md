# Function: <code>call_usermodehelper_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579461892,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/kmod.c:519",
      "file": "kernel/kmod.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kmod.c:__request_module",
        "kernel/kmod.c:call_usermodehelper"
      ],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462288,
      "name": "call_usermodehelper_setup",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579475717,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/kmod.c:519",
      "file": "kernel/kmod.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kmod.c:call_usermodehelper",
        "kernel/kmod.c:__request_module"
      ],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579475536,
      "name": "call_usermodehelper_setup",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579496117,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/kmod.c:519",
      "file": "kernel/kmod.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kmod.c:call_usermodehelper",
        "kernel/kmod.c:__request_module"
      ],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495936,
      "name": "call_usermodehelper_setup",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579484597,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/kmod.c:536",
      "file": "kernel/kmod.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kmod.c:call_usermodehelper",
        "kernel/kmod.c:__request_module"
      ],
      "caller_func": [
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579484752,
      "name": "call_usermodehelper_setup",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579512501,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:367",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512656,
      "name": "call_usermodehelper_setup",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579538745,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:374",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538864,
      "name": "call_usermodehelper_setup",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579575337,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:378",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579575904,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579598793,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:379",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599360,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579624649,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:379",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579625216,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579653801,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:379",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/kmod.c:call_modprobe",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653184,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579634137,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:356",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/usermode_driver.c:fork_usermode_driver",
        "kernel/kmod.c:call_modprobe",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579633280,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579640793,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:358",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/usermode_driver.c:fork_usermode_driver",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579639936,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579717401,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:358",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/usermode_driver.c:fork_usermode_driver",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716448,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579819737,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:358",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/usermode_driver.c:fork_usermode_driver",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818736,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579956137,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:359",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/usermode_driver.c:fork_usermode_driver",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955056,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580006473,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:356",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/usermode_driver.c:fork_usermode_driver",
        "kernel/module/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580005392,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580046150,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:356",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/module/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045040,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490790496,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:379",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490789448,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224826828,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:379",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224826960,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283617752,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:379",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283617440,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271471626,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:379",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271471776,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579600953,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:379",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601520,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579529593,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:379",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530160,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579598233,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:379",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598800,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct subprocess_info * call_usermodehelper_setup(const char * path, char * * argv, char * * envp, gfp_t gfp_mask, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579632729,
      "name": "call_usermodehelper_setup",
      "external": true,
      "loc": "kernel/umh.c:379",
      "file": "kernel/umh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/umh.c:call_usermodehelper"
      ],
      "caller_func": [
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579632848,
      "name": "call_usermodehelper_setup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
