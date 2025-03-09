# Function: <code>pmc_core_lpm_latch_mode_write</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t pmc_core_lpm_latch_mode_write(struct file * file, const char * userbuf, size_t count, loff_t * ppos)
```

```json
{
  "name": "pmc_core_lpm_latch_mode_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588975104,
      "name": "pmc_core_lpm_latch_mode_write",
      "external": false,
      "loc": "drivers/platform/x86/intel_pmc_core.c:1355",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588975104,
      "name": "pmc_core_lpm_latch_mode_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 462
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
ssize_t pmc_core_lpm_latch_mode_write(struct file * file, const char * userbuf, size_t count, loff_t * ppos)
```

```json
{
  "name": "pmc_core_lpm_latch_mode_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmc_core_lpm_latch_mode_write",
      "external": false,
      "loc": "drivers/platform/x86/intel/pmc/core.c:1655",
      "file": "drivers/platform/x86/intel/pmc/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589684480,
      "name": "pmc_core_lpm_latch_mode_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
    },
    {
      "addr": 18446744071592676901,
      "name": "pmc_core_lpm_latch_mode_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
ssize_t pmc_core_lpm_latch_mode_write(struct file * file, const char * userbuf, size_t count, loff_t * ppos)
```

```json
{
  "name": "pmc_core_lpm_latch_mode_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmc_core_lpm_latch_mode_write",
      "external": false,
      "loc": "drivers/platform/x86/intel/pmc/core.c:1655",
      "file": "drivers/platform/x86/intel/pmc/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591193072,
      "name": "pmc_core_lpm_latch_mode_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
    },
    {
      "addr": 18446744071594562530,
      "name": "pmc_core_lpm_latch_mode_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
ssize_t pmc_core_lpm_latch_mode_write(struct file * file, const char * userbuf, size_t count, loff_t * ppos)
```

```json
{
  "name": "pmc_core_lpm_latch_mode_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmc_core_lpm_latch_mode_write",
      "external": false,
      "loc": "drivers/platform/x86/intel/pmc/core.c:763",
      "file": "drivers/platform/x86/intel/pmc/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592930400,
      "name": "pmc_core_lpm_latch_mode_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
    },
    {
      "addr": 18446744071596318976,
      "name": "pmc_core_lpm_latch_mode_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
ssize_t pmc_core_lpm_latch_mode_write(struct file * file, const char * userbuf, size_t count, loff_t * ppos)
```

```json
{
  "name": "pmc_core_lpm_latch_mode_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pmc_core_lpm_latch_mode_write",
      "external": false,
      "loc": "drivers/platform/x86/intel/pmc/core.c:841",
      "file": "drivers/platform/x86/intel/pmc/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593374960,
      "name": "pmc_core_lpm_latch_mode_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
    },
    {
      "addr": 18446744071596848503,
      "name": "pmc_core_lpm_latch_mode_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
ssize_t pmc_core_lpm_latch_mode_write(struct file * file, const char * userbuf, size_t count, loff_t * ppos)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
ssize_t pmc_core_lpm_latch_mode_write(struct file * file, const char * userbuf, size_t count, loff_t * ppos)
```
</details>
</li>
</ul>
