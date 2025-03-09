# Function: <code>tpm_transmit_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, void * cmd, int len, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584234400,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:403",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_gen_interrupt",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_continue_selftest",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_getcap",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read_dev",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584234400,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, void * cmd, int len, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584574160,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:403",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read_dev",
        "drivers/char/tpm/tpm-interface.c:tpm_continue_selftest",
        "drivers/char/tpm/tpm-interface.c:tpm_gen_interrupt",
        "drivers/char/tpm/tpm-interface.c:tpm_getcap",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584574160,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, const void * cmd, int len, unsigned int flags, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584756112,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:415",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read_dev",
        "drivers/char/tpm/tpm-interface.c:tpm_continue_selftest",
        "drivers/char/tpm/tpm-interface.c:tpm_getcap",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756112,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_space * space, const void * buf, size_t bufsiz, size_t min_rsp_body_length, unsigned int flags, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584837344,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:516",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read_dev",
        "drivers/char/tpm/tpm-interface.c:tpm_continue_selftest",
        "drivers/char/tpm/tpm-interface.c:tpm_getcap",
        "drivers/char/tpm/tpm-interface.c:tpm_startup",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584837344,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_space * space, const void * buf, size_t bufsiz, size_t min_rsp_body_length, unsigned int flags, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585258624,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:534",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read_dev",
        "drivers/char/tpm/tpm-interface.c:tpm_continue_selftest",
        "drivers/char/tpm/tpm-interface.c:tpm_getcap",
        "drivers/char/tpm/tpm-interface.c:tpm_startup",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585258624,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t bufsiz, size_t min_rsp_body_length, unsigned int flags, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585495440,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:653",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_get_random",
        "drivers/char/tpm/tpm-interface.c:tpm_pm_suspend",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm-interface.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm-interface.c:tpm_pcr_read_dev",
        "drivers/char/tpm/tpm-interface.c:tpm_continue_selftest",
        "drivers/char/tpm/tpm-interface.c:tpm_getcap",
        "drivers/char/tpm/tpm-interface.c:tpm_startup",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585495440,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_space * space, void * buf, size_t bufsiz, size_t min_rsp_body_length, unsigned int flags, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585623264,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:394",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context_cmd",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585623264,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_buf * buf, size_t min_rsp_body_length, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:212",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585843591,
      "name": "tpm_transmit_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585842928,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_buf * buf, size_t min_rsp_body_length, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:212",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585986151,
      "name": "tpm_transmit_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585985616,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_buf * buf, size_t min_rsp_body_length, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:213",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_save_context",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586727149,
      "name": "tpm_transmit_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586726624,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_buf * buf, size_t min_rsp_body_length, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:213",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd",
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd",
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_save_context",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591470154,
      "name": "tpm_transmit_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586822192,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_buf * buf, size_t min_rsp_body_length, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:213",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd",
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd",
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_save_context",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591411421,
      "name": "tpm_transmit_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586702176,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_buf * buf, size_t min_rsp_body_length, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:213",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd",
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd",
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_save_context",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592463255,
      "name": "tpm_transmit_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587251552,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_buf * buf, size_t min_rsp_body_length, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:213",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd",
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd",
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_save_context",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594333054,
      "name": "tpm_transmit_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588560624,
      "name": "tpm_transmit_cmd",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_buf * buf, size_t min_rsp_body_length, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590013808,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:213",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd",
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd",
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_save_context",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590013808,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_buf * buf, size_t min_rsp_body_length, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590323120,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:213",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd",
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd",
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_save_context",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590323120,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_buf * buf, size_t min_rsp_body_length, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590664512,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:213",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_cmd",
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_load_cmd",
        "security/keys/trusted-keys/trusted_tpm2.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_cc_attrs_tbl",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_save_context",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590664512,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_buf * buf, size_t min_rsp_body_length, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498780648,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:212",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498780648,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_buf * buf, size_t min_rsp_body_length, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231395360,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:212",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231395360,
      "name": "tpm_transmit_cmd",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_buf * buf, size_t min_rsp_body_length, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291972176,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:212",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291972176,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_buf * buf, size_t min_rsp_body_length, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276274768,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:212",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276274768,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_buf * buf, size_t min_rsp_body_length, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:212",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585747127,
      "name": "tpm_transmit_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585746592,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_buf * buf, size_t min_rsp_body_length, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:212",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585606311,
      "name": "tpm_transmit_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585605776,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_buf * buf, size_t min_rsp_body_length, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:212",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585936167,
      "name": "tpm_transmit_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585935632,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
ssize_t tpm_transmit_cmd(struct tpm_chip * chip, struct tpm_buf * buf, size_t min_rsp_body_length, const char * desc)
```

```json
{
  "name": "tpm_transmit_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_transmit_cmd",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:212",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-interface.c:tpm_send",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_random",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_getcap",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_probe",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_random",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read",
        "drivers/char/tpm/tpm2-space.c:tpm2_load_context",
        "drivers/char/tpm/tpm-sysfs.c:pubek_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586044151,
      "name": "tpm_transmit_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586043616,
      "name": "tpm_transmit_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>chip, cmd, len, desc</code> ➡️ <code>chip, cmd, len, flags, desc</code>
</li>
<li>
<b>Param type changed. </b>
<code>void * cmd</code> ➡️ <code>const void * cmd</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tpm_space * space</code>
</li>
<li>
<b>Param added. </b>
<code>const void * buf</code>
</li>
<li>
<b>Param added. </b>
<code>size_t bufsiz</code>
</li>
<li>
<b>Param added. </b>
<code>size_t min_rsp_body_length</code>
</li>
<li>
<b>Param removed. </b>
<code>const void * cmd</code>
</li>
<li>
<b>Param removed. </b>
<code>int len</code>
</li>
<li>
<b>Param reordered. </b>
<code>chip, cmd, len, flags, desc</code> ➡️ <code>chip, space, buf, bufsiz, min_rsp_body_length, flags, desc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const void * buf</code> ➡️ <code>void * buf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct tpm_space * space</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t bufsiz</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>chip, space, buf, bufsiz, min_rsp_body_length, flags, desc</code> ➡️ <code>chip, buf, min_rsp_body_length, desc</code>
</li>
<li>
<b>Param type changed. </b>
<code>void * buf</code> ➡️ <code>struct tpm_buf * buf</code>
</li>
</ul>
</details>
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
