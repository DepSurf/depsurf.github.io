# Function: <code>flush_signal_handlers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426016,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:479",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "fs/exec.c:setup_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426016,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579438432,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:479",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "fs/exec.c:setup_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579438432,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579458784,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:481",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "fs/exec.c:setup_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579458784,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579446416,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:487",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "fs/exec.c:setup_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579446416,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579474800,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:489",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:setup_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579474800,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579491136,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:491",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:setup_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491136,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579524688,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:523",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:setup_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524688,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544352,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:533",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:setup_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544352,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579570464,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:538",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:setup_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570464,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579609024,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:538",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_sighand",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:begin_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579609024,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579589248,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:539",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_sighand",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:begin_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579589248,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579596416,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:538",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_sighand",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:begin_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579596416,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671248,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:539",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_sighand",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:begin_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671248,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579768096,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:539",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:begin_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768096,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899856,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:539",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_sighand",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:begin_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899856,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579949408,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:540",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_sighand",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:begin_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949408,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579988640,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:531",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_sighand",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:begin_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988640,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490732776,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:538",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:setup_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490732776,
      "name": "flush_signal_handlers",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224784744,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:538",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:setup_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224784744,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283555392,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:538",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:setup_new_exec",
        "fs/exec.c:setup_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283555392,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271442614,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:538",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:setup_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271442614,
      "name": "flush_signal_handlers",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546768,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:538",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:setup_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546768,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579475504,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:538",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:setup_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579475504,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544048,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:538",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:setup_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544048,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void flush_signal_handlers(struct task_struct * t, int force_default)
```

```json
{
  "name": "flush_signal_handlers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579577040,
      "name": "flush_signal_handlers",
      "external": true,
      "loc": "kernel/signal.c:538",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:setup_new_exec",
        "security/selinux/hooks.c:selinux_bprm_committed_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577040,
      "name": "flush_signal_handlers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
