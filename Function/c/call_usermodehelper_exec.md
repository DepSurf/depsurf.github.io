# Function: <code>call_usermodehelper_exec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579460144,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/kmod.c:555",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "kernel/kmod.c:__request_module",
        "kernel/kmod.c:call_usermodehelper",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460144,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579473392,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/kmod.c:555",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts_initrd.c:initrd_load",
        "kernel/kmod.c:call_usermodehelper",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579473392,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493792,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/kmod.c:555",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kmod.c:call_usermodehelper",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493792,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579483120,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/kmod.c:577",
      "file": "kernel/kmod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kmod.c:call_usermodehelper",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483120,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 369
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579511008,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:408",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579511008,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579538032,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:526",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
        "kernel/umh.c:fork_usermode_blob",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538032,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579574624,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:547",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
        "kernel/umh.c:fork_usermode_blob",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579574624,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579598064,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:548",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
        "kernel/umh.c:fork_usermode_blob",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598064,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579623920,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:548",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
        "kernel/umh.c:fork_usermode_blob",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579623920,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653360,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:559",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
        "kernel/umh.c:fork_usermode_blob",
        "kernel/kmod.c:call_modprobe",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653360,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579633696,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:402",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
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
      "addr": 18446744071579633696,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579640352,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:404",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
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
      "addr": 18446744071579640352,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579716960,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:404",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
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
      "addr": 18446744071579716960,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579819280,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:404",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
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
      "addr": 18446744071579819280,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579955616,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:405",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
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
      "addr": 18446744071579955616,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580005952,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:402",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
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
      "addr": 18446744071580005952,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580045616,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:402",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
        "kernel/module/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045616,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490789960,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:548",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
        "kernel/umh.c:fork_usermode_blob",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490789960,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224826324,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:548",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
        "kernel/umh.c:fork_usermode_blob",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224826324,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283614880,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:548",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
        "kernel/umh.c:fork_usermode_blob",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283614880,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271471014,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:548",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
        "kernel/umh.c:fork_usermode_blob",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271471014,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579600224,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:548",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
        "kernel/umh.c:fork_usermode_blob",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579600224,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579528864,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:548",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
        "kernel/umh.c:fork_usermode_blob",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528864,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579597504,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:548",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
        "kernel/umh.c:fork_usermode_blob",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597504,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
int call_usermodehelper_exec(struct subprocess_info * sub_info, int wait)
```

```json
{
  "name": "call_usermodehelper_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579631152,
      "name": "call_usermodehelper_exec",
      "external": true,
      "loc": "kernel/umh.c:548",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper",
        "kernel/umh.c:fork_usermode_blob",
        "kernel/kmod.c:__request_module",
        "fs/coredump.c:do_coredump",
        "security/keys/request_key.c:call_sbin_request_key",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631152,
      "name": "call_usermodehelper_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
