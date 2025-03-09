# Function: <code>__printk_safe_exit</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579783120,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:359",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:devkmsg_poll",
        "kernel/printk/printk.c:devkmsg_llseek",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579783120,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579816496,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:356",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:devkmsg_poll",
        "kernel/printk/printk.c:devkmsg_llseek",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579816496,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579849984,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:368",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/printk/printk.c:devkmsg_poll",
        "kernel/printk/printk.c:devkmsg_llseek",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849984,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579896992,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:368",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/printk/printk.c:devkmsg_poll",
        "kernel/printk/printk.c:devkmsg_llseek",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579896992,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579931712,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:356",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/printk/printk.c:devkmsg_poll",
        "kernel/printk/printk.c:devkmsg_llseek",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931712,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579981840,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:356",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/printk/printk.c:devkmsg_poll",
        "kernel/printk/printk.c:devkmsg_llseek",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981840,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580029360,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:357",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:console_trylock_spinning",
        "kernel/printk/printk.c:console_trylock_spinning",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print",
        "kernel/printk/printk.c:syslog_print",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/printk/printk.c:devkmsg_poll",
        "kernel/printk/printk.c:devkmsg_llseek",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029360,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580007984,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:365",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:console_trylock_spinning",
        "kernel/printk/printk.c:console_trylock_spinning",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print",
        "kernel/printk/printk.c:syslog_print",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/printk/printk.c:devkmsg_poll",
        "kernel/printk/printk.c:devkmsg_llseek",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007984,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580008972,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:355",
      "file": "kernel/printk/printk_safe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_safe.c:vprintk"
      ],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print",
        "kernel/printk/printk.c:syslog_print",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/printk/printk.c:devkmsg_poll",
        "kernel/printk/printk.c:devkmsg_llseek",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009360,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580140608,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:24",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580140608,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580284368,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:24",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/workqueue.c:show_one_workqueue",
        "kernel/printk/printk.c:console_trylock_spinning",
        "kernel/printk/printk.c:console_trylock_spinning"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580284368,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580494080,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:24",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/workqueue.c:show_one_workqueue",
        "kernel/printk/printk.c:console_trylock_spinning",
        "kernel/printk/printk.c:console_trylock_spinning"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494080,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580565920,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:24",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/workqueue.c:show_one_workqueue",
        "kernel/printk/printk.c:console_emit_next_record",
        "kernel/printk/printk.c:console_trylock_spinning",
        "kernel/printk/printk.c:console_trylock_spinning",
        "mm/page_alloc.c:__build_all_zonelists"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580565920,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580628944,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:24",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/workqueue.c:show_one_workqueue",
        "kernel/printk/printk.c:console_emit_next_record",
        "kernel/printk/printk.c:console_trylock_spinning",
        "kernel/printk/printk.c:console_trylock_spinning",
        "mm/page_alloc.c:__build_all_zonelists",
        "lib/stackdepot.c:stack_depot_save_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628944,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491167624,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:356",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print",
        "kernel/printk/printk.c:syslog_print",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/printk/printk.c:devkmsg_poll",
        "kernel/printk/printk.c:devkmsg_llseek",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491167624,
      "name": "__printk_safe_exit",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225193740,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:356",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:syslog_print_all",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/printk/printk.c:devkmsg_poll",
        "kernel/printk/printk.c:devkmsg_llseek",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225193740,
      "name": "__printk_safe_exit",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284066480,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:356",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/printk/printk.c:devkmsg_poll",
        "kernel/printk/printk.c:devkmsg_llseek",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284066480,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271720246,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:356",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/printk/printk.c:devkmsg_poll",
        "kernel/printk/printk.c:devkmsg_llseek",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271720246,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579950576,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:356",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/printk/printk.c:devkmsg_poll",
        "kernel/printk/printk.c:devkmsg_llseek",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579950576,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579888464,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:356",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/printk/printk.c:devkmsg_poll",
        "kernel/printk/printk.c:devkmsg_llseek",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888464,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579942112,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:356",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/printk/printk.c:devkmsg_poll",
        "kernel/printk/printk.c:devkmsg_llseek",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942112,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void __printk_safe_exit()
```

```json
{
  "name": "__printk_safe_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579988464,
      "name": "__printk_safe_exit",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:356",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:kmsg_dump_rewind",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_buffer",
        "kernel/printk/printk.c:kmsg_dump_get_line",
        "kernel/printk/printk.c:kmsg_dump",
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:devkmsg_open",
        "kernel/printk/printk.c:devkmsg_poll",
        "kernel/printk/printk.c:devkmsg_llseek",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:setup_log_buf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579988464,
      "name": "__printk_safe_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void __printk_safe_exit()
```
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
