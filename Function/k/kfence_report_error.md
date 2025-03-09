# Function: <code>kfence_report_error</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void kfence_report_error(long unsigned int address, bool is_write, struct pt_regs * regs, const struct kfence_metadata * meta, enum kfence_error_type type)
```

```json
{
  "name": "kfence_report_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kfence_report_error",
      "external": true,
      "loc": "mm/kfence/report.c:180",
      "file": "mm/kfence/report.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592222399,
      "name": "kfence_report_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1655
    },
    {
      "addr": 18446744071582240944,
      "name": "kfence_report_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void kfence_report_error(long unsigned int address, bool is_write, struct pt_regs * regs, const struct kfence_metadata * meta, enum kfence_error_type type)
```

```json
{
  "name": "kfence_report_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kfence_report_error",
      "external": true,
      "loc": "mm/kfence/report.c:180",
      "file": "mm/kfence/report.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_check_all_canary",
        "mm/kfence/core.c:kfence_check_all_canary",
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594001479,
      "name": "kfence_report_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1728
    },
    {
      "addr": 18446744071582713376,
      "name": "kfence_report_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void kfence_report_error(long unsigned int address, bool is_write, struct pt_regs * regs, const struct kfence_metadata * meta, enum kfence_error_type type)
```

```json
{
  "name": "kfence_report_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kfence_report_error",
      "external": true,
      "loc": "mm/kfence/report.c:186",
      "file": "mm/kfence/report.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_check_all_canary",
        "mm/kfence/core.c:kfence_check_all_canary",
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:kfence_guarded_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596046714,
      "name": "kfence_report_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583239360,
      "name": "kfence_report_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1492
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void kfence_report_error(long unsigned int address, bool is_write, struct pt_regs * regs, const struct kfence_metadata * meta, enum kfence_error_type type)
```

```json
{
  "name": "kfence_report_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kfence_report_error",
      "external": true,
      "loc": "mm/kfence/report.c:186",
      "file": "mm/kfence/report.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:check_canary",
        "mm/kfence/core.c:check_canary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596569256,
      "name": "kfence_report_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583458896,
      "name": "kfence_report_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1476
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void kfence_report_error(long unsigned int address, bool is_write, struct pt_regs * regs, const struct kfence_metadata * meta, enum kfence_error_type type)
```

```json
{
  "name": "kfence_report_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kfence_report_error",
      "external": true,
      "loc": "mm/kfence/report.c:185",
      "file": "mm/kfence/report.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_handle_page_fault",
        "mm/kfence/core.c:kfence_guarded_free",
        "mm/kfence/core.c:check_canary",
        "mm/kfence/core.c:check_canary"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597473390,
      "name": "kfence_report_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583651936,
      "name": "kfence_report_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1477
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void kfence_report_error(long unsigned int address, bool is_write, struct pt_regs * regs, const struct kfence_metadata * meta, enum kfence_error_type type)
```
</details>
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
