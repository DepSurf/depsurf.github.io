# Function: <code>sata_scr_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584908992,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5138",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_set_spd",
        "drivers/ata/libata-core.c:sata_link_scr_lpm",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-core.c:ata_phys_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_phys_link_offline",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584908992,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585271264,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5330",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_phys_link_offline",
        "drivers/ata/libata-core.c:ata_phys_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_scr_lpm",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_set_spd",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585271264,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585470816,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5372",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_phys_link_offline",
        "drivers/ata/libata-core.c:ata_phys_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_scr_lpm",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_set_spd",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585470816,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585554384,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5458",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_phys_link_offline",
        "drivers/ata/libata-core.c:ata_phys_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_scr_lpm",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_set_spd",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585554384,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585986048,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5489",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_phys_link_offline",
        "drivers/ata/libata-core.c:ata_phys_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_scr_lpm",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_set_spd",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585986048,
      "name": "sata_scr_read",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586234416,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5505",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_phys_link_offline",
        "drivers/ata/libata-core.c:ata_phys_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_scr_lpm",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_set_spd",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586234416,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586374832,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5509",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_phys_link_offline",
        "drivers/ata/libata-core.c:ata_phys_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_scr_lpm",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_set_spd",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586374832,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586618528,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5494",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_phys_link_offline",
        "drivers/ata/libata-core.c:ata_phys_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_scr_lpm",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_set_spd",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586618528,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586766080,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5518",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_phys_link_offline",
        "drivers/ata/libata-core.c:ata_phys_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_scr_lpm",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_set_spd",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586766080,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587657104,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:63",
      "file": "drivers/ata/libata-sata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:sata_set_spd"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_link_offline",
        "drivers/ata/libata-core.c:ata_link_offline",
        "drivers/ata/libata-core.c:ata_link_online",
        "drivers/ata/libata-core.c:ata_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_prereset",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_scr_lpm",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_debounce",
        "drivers/ata/libata-sata.c:sata_link_debounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587657104,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587718048,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:63",
      "file": "drivers/ata/libata-sata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:sata_set_spd"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_link_offline",
        "drivers/ata/libata-core.c:ata_link_offline",
        "drivers/ata/libata-core.c:ata_link_online",
        "drivers/ata/libata-core.c:ata_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_prereset",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_scr_lpm",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_debounce",
        "drivers/ata/libata-sata.c:sata_link_debounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587718048,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587597264,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:63",
      "file": "drivers/ata/libata-sata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:sata_set_spd"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_link_offline",
        "drivers/ata/libata-core.c:ata_link_offline",
        "drivers/ata/libata-core.c:ata_link_online",
        "drivers/ata/libata-core.c:ata_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_prereset",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_scr_lpm",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_debounce",
        "drivers/ata/libata-sata.c:sata_link_debounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587597264,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588181344,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:63",
      "file": "drivers/ata/libata-sata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:sata_set_spd"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_link_offline",
        "drivers/ata/libata-core.c:ata_link_offline",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_prereset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_scr_lpm",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_debounce",
        "drivers/ata/libata-sata.c:sata_link_debounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588181344,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589568972,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:63",
      "file": "drivers/ata/libata-sata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:sata_set_spd"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_link_offline",
        "drivers/ata/libata-core.c:ata_link_offline",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_prereset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-sata.c:sata_async_notification",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_scr_lpm",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_debounce",
        "drivers/ata/libata-sata.c:sata_link_debounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589563584,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591163276,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:63",
      "file": "drivers/ata/libata-sata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:sata_set_spd"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_link_offline",
        "drivers/ata/libata-core.c:ata_link_offline",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_prereset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-sata.c:sata_async_notification",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_scr_lpm",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_debounce",
        "drivers/ata/libata-sata.c:sata_link_debounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591156976,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591522428,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:65",
      "file": "drivers/ata/libata-sata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:sata_set_spd"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_link_offline",
        "drivers/ata/libata-core.c:ata_link_offline",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_prereset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-sata.c:sata_async_notification",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_scr_lpm",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_debounce",
        "drivers/ata/libata-sata.c:sata_link_debounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591515456,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591870844,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-sata.c:65",
      "file": "drivers/ata/libata-sata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sata.c:sata_set_spd"
      ],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_link_offline",
        "drivers/ata/libata-core.c:ata_link_offline",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_prereset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-sata.c:sata_async_notification",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_scr_lpm",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_debounce",
        "drivers/ata/libata-sata.c:sata_link_debounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591864032,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499686320,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5518",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_phys_link_offline",
        "drivers/ata/libata-core.c:ata_phys_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_scr_lpm",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_set_spd",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499686320,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232133712,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5518",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_phys_link_offline",
        "drivers/ata/libata-core.c:ata_phys_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_scr_lpm",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_set_spd",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/sata_highbank.c:ahci_highbank_hardreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232133712,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293016256,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5518",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_phys_link_offline",
        "drivers/ata/libata-core.c:ata_phys_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_scr_lpm",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_set_spd",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293016256,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276857058,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5518",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_phys_link_offline",
        "drivers/ata/libata-core.c:ata_phys_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_scr_lpm",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_set_spd",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276857058,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586524816,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5518",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_phys_link_offline",
        "drivers/ata/libata-core.c:ata_phys_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_scr_lpm",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_set_spd",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586524816,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586393392,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5518",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_phys_link_offline",
        "drivers/ata/libata-core.c:ata_phys_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_scr_lpm",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_set_spd",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586393392,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586720640,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5518",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_phys_link_offline",
        "drivers/ata/libata-core.c:ata_phys_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_scr_lpm",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_set_spd",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586720640,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int sata_scr_read(struct ata_link * link, int reg, u32 * val)
```

```json
{
  "name": "sata_scr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586826816,
      "name": "sata_scr_read",
      "external": true,
      "loc": "drivers/ata/libata-core.c:5518",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_phys_link_offline",
        "drivers/ata/libata-core.c:ata_phys_link_online",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_scr_lpm",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_link_debounce",
        "drivers/ata/libata-core.c:sata_set_spd",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy",
        "drivers/ata/libata-eh.c:sata_async_notification",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586826816,
      "name": "sata_scr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
