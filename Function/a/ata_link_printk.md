# Function: <code>ata_link_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584912192,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6829",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584912192,
      "name": "ata_link_printk",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585274576,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7033",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585274576,
      "name": "ata_link_printk",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585474128,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7075",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_report",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474128,
      "name": "ata_link_printk",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585557616,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7161",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585557616,
      "name": "ata_link_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585989328,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7191",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585989328,
      "name": "ata_link_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586262688,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7238",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586262688,
      "name": "ata_link_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586403152,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7242",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586403152,
      "name": "ata_link_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586647359,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7227",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586647359,
      "name": "ata_link_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586794813,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7274",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586794813,
      "name": "ata_link_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587598261,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6451",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_prereset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:ata_force_link_limits",
        "drivers/ata/libata-core.c:ata_force_link_limits",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_set_lpm",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587598261,
      "name": "ata_link_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591522248,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6451",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_prereset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:sata_print_link_status",
        "drivers/ata/libata-core.c:ata_force_link_limits",
        "drivers/ata/libata-core.c:ata_force_link_limits",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_set_lpm",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591522248,
      "name": "ata_link_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591464208,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6451",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_prereset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_set_lpm",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591464208,
      "name": "ata_link_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592531385,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:6513",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_prereset",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-core.c:sata_down_spd_limit",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_set_lpm",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sata.c:sata_link_hardreset",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sata.c:sata_link_resume",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592531385,
      "name": "ata_link_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499722092,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7274",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read",
        "drivers/ata/libahci.c:ahci_pmp_retry_softreset",
        "drivers/ata/libahci.c:ahci_do_softreset",
        "drivers/ata/libahci.c:ahci_do_softreset",
        "drivers/ata/libahci.c:ahci_do_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499722092,
      "name": "ata_link_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232169072,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7274",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read",
        "drivers/ata/libahci.c:ahci_pmp_retry_softreset",
        "drivers/ata/libahci.c:ahci_do_softreset",
        "drivers/ata/libahci.c:ahci_do_softreset",
        "drivers/ata/libahci.c:ahci_do_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232169072,
      "name": "ata_link_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293058416,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7274",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293058416,
      "name": "ata_link_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276886508,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7274",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276886508,
      "name": "ata_link_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586553421,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7274",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586553421,
      "name": "ata_link_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586421997,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7274",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586421997,
      "name": "ata_link_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586749373,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7274",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586749373,
      "name": "ata_link_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
```

```json
{
  "name": "ata_link_printk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586855437,
      "name": "ata_link_printk",
      "external": true,
      "loc": "drivers/ata/libata-core.c:7274",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:ata_std_postreset",
        "drivers/ata/libata-core.c:sata_link_hardreset",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:sata_link_resume",
        "drivers/ata/libata-core.c:ata_wait_ready",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_recover",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_link_report",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error",
        "drivers/ata/libata-sff.c:ata_sff_softreset",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_eh_recover",
        "drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_write",
        "drivers/ata/libata-pmp.c:sata_pmp_scr_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586855437,
      "name": "ata_link_printk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void ata_link_printk(const struct ata_link * link, const char * level, const char * fmt, void (anon))
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
