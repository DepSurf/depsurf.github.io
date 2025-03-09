# Function: <code>tty_kref_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583959648,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1665",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:proc_clear_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open"
      ],
      "caller_func": [
        "kernel/exit.c:release_task",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_wakeup",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:hvc_poll",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583959648,
      "name": "tty_kref_put",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584305135,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1667",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:proc_clear_tty"
      ],
      "caller_func": [
        "kernel/exit.c:release_task",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_wakeup",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584293232,
      "name": "tty_kref_put",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584487198,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1667",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:proc_clear_tty"
      ],
      "caller_func": [
        "kernel/exit.c:release_task",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_wakeup",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584475296,
      "name": "tty_kref_put",
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
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584554528,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1435",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:proc_clear_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584554528,
      "name": "tty_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584979725,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1453",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "kernel/exit.c:release_task",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:proc_clear_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584974672,
      "name": "tty_kref_put",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585213069,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1471",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:proc_clear_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204544,
      "name": "tty_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585332013,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1483",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:proc_clear_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585323632,
      "name": "tty_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585544751,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1485",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/audit.c:audit_set_loginuid",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:proc_clear_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585535520,
      "name": "tty_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585685663,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1485",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/audit.c:audit_set_loginuid",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:proc_clear_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585676400,
      "name": "tty_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586414850,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1489",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "kernel/exit.c:__exit_signal",
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_log_multicast",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:session_clear_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586403072,
      "name": "tty_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586530494,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1570",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "kernel/exit.c:__exit_signal",
        "kernel/audit.c:audit_log_set_loginuid",
        "kernel/audit.c:audit_log_multicast",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:tty_jobctrl_ioctl",
        "drivers/tty/tty_jobctrl.c:session_clear_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586518192,
      "name": "tty_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586414717,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1585",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "kernel/exit.c:__exit_signal",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_multicast",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586403136,
      "name": "tty_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586941725,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1578",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "kernel/exit.c:__exit_signal",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_multicast",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586929920,
      "name": "tty_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588236007,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1567",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "kernel/exit.c:__exit_signal",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588222992,
      "name": "tty_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589646615,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1562",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "kernel/exit.c:__exit_signal",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589632160,
      "name": "tty_kref_put",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589950487,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1571",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "kernel/exit.c:__exit_signal",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:serial_core_remove_one_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589935824,
      "name": "tty_kref_put",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590288982,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1569",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "kernel/exit.c:__exit_signal",
        "kernel/audit.c:audit_set_loginuid",
        "kernel/audit.c:audit_log_task_info",
        "kernel/audit.c:audit_log_multicast",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/selinux/hooks.c:selinux_bprm_committing_creds",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock_slave",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:no_tty",
        "drivers/tty/tty_jobctrl.c:session_clear_tty",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:serial_core_remove_one_port",
        "drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590274368,
      "name": "tty_kref_put",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498363548,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1485",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/audit.c:audit_set_loginuid",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:proc_clear_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498344672,
      "name": "tty_kref_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446603336498344776,
      "name": "tty_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231049016,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1485",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/audit.c:audit_set_loginuid",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:proc_clear_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231036888,
      "name": "tty_kref_put.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 3231036988,
      "name": "tty_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291525552,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1485",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/audit.c:audit_set_loginuid",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:proc_clear_tty",
        "drivers/tty/hvc/hvsi_lib.c:hvsilib_close",
        "drivers/tty/hvc/hvsi_lib.c:hvsilib_close",
        "drivers/tty/hvc/hvsi.c:hvsi_interrupt",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291525552,
      "name": "tty_kref_put",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276038388,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1485",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/audit.c:audit_set_loginuid",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:proc_clear_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276025124,
      "name": "tty_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585446687,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1485",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/audit.c:audit_set_loginuid",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:proc_clear_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585437424,
      "name": "tty_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585316719,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1485",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/audit.c:audit_set_loginuid",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:proc_clear_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585307472,
      "name": "tty_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585636063,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1485",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/audit.c:audit_set_loginuid",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:proc_clear_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585626800,
      "name": "tty_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void tty_kref_put(struct tty_struct * tty)
```

```json
{
  "name": "tty_kref_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585744191,
      "name": "tty_kref_put",
      "external": true,
      "loc": "drivers/tty/tty_io.c:1485",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ],
      "caller_func": [
        "kernel/exit.c:release_task",
        "kernel/audit.c:audit_set_loginuid",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "security/apparmor/file.c:aa_inherit_files",
        "drivers/tty/tty_port.c:tty_port_tty_hangup",
        "drivers/tty/tty_port.c:tty_port_hangup",
        "drivers/tty/tty_port.c:tty_port_tty_set",
        "drivers/tty/tty_port.c:tty_port_default_wakeup",
        "drivers/tty/tty_mutex.c:tty_unlock",
        "drivers/tty/tty_mutex.c:tty_lock_interruptible",
        "drivers/tty/tty_jobctrl.c:__proc_set_tty",
        "drivers/tty/tty_jobctrl.c:proc_clear_tty",
        "drivers/tty/hvc/hvc_console.c:hvc_remove",
        "drivers/tty/hvc/hvc_console.c:__hvc_poll",
        "drivers/tty/hvc/hvc_console.c:hvc_set_winsz",
        "drivers/tty/serial/serial_core.c:uart_remove_one_port",
        "drivers/tty/serdev/serdev-ttyport.c:ttyport_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585738576,
      "name": "tty_kref_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
