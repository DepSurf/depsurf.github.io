# Function: <code>mmc_send_adtc_data</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int mmc_send_adtc_data(struct mmc_card * card, struct mmc_host * host, u32 opcode, u32 args, void * buf, unsigned int len)
```

```json
{
  "name": "mmc_send_adtc_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589598432,
      "name": "mmc_send_adtc_data",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:254",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_spi_send_cxd",
        "drivers/mmc/core/sd.c:sd_busy_poweroff_notify_cb",
        "drivers/mmc/core/sd.c:sd_flush_cache",
        "drivers/mmc/core/sd.c:sd_read_ext_regs",
        "drivers/mmc/core/sd.c:sd_read_ext_regs",
        "drivers/mmc/core/sd.c:sd_read_ext_regs",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589598432,
      "name": "mmc_send_adtc_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int mmc_send_adtc_data(struct mmc_card * card, struct mmc_host * host, u32 opcode, u32 args, void * buf, unsigned int len)
```

```json
{
  "name": "mmc_send_adtc_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591094912,
      "name": "mmc_send_adtc_data",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:283",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_spi_send_cxd",
        "drivers/mmc/core/sd.c:sd_busy_poweroff_notify_cb",
        "drivers/mmc/core/sd.c:sd_flush_cache",
        "drivers/mmc/core/sd.c:sd_read_ext_regs",
        "drivers/mmc/core/sd.c:sd_parse_ext_reg",
        "drivers/mmc/core/sd.c:sd_parse_ext_reg",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591094912,
      "name": "mmc_send_adtc_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
int mmc_send_adtc_data(struct mmc_card * card, struct mmc_host * host, u32 opcode, u32 args, void * buf, unsigned int len)
```

```json
{
  "name": "mmc_send_adtc_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592813472,
      "name": "mmc_send_adtc_data",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:283",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_spi_send_cxd",
        "drivers/mmc/core/sd.c:sd_busy_poweroff_notify_cb",
        "drivers/mmc/core/sd.c:sd_flush_cache",
        "drivers/mmc/core/sd.c:sd_read_ext_regs",
        "drivers/mmc/core/sd.c:sd_parse_ext_reg",
        "drivers/mmc/core/sd.c:sd_parse_ext_reg",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592813472,
      "name": "mmc_send_adtc_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
int mmc_send_adtc_data(struct mmc_card * card, struct mmc_host * host, u32 opcode, u32 args, void * buf, unsigned int len)
```

```json
{
  "name": "mmc_send_adtc_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593250224,
      "name": "mmc_send_adtc_data",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:283",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_spi_send_cxd",
        "drivers/mmc/core/sd.c:sd_busy_poweroff_notify_cb",
        "drivers/mmc/core/sd.c:sd_flush_cache",
        "drivers/mmc/core/sd.c:sd_read_ext_regs",
        "drivers/mmc/core/sd.c:sd_parse_ext_reg",
        "drivers/mmc/core/sd.c:sd_parse_ext_reg",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593250224,
      "name": "mmc_send_adtc_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
int mmc_send_adtc_data(struct mmc_card * card, struct mmc_host * host, u32 opcode, u32 args, void * buf, unsigned int len)
```

```json
{
  "name": "mmc_send_adtc_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594005376,
      "name": "mmc_send_adtc_data",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:283",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/mmc_ops.c:mmc_spi_send_cxd",
        "drivers/mmc/core/sd.c:sd_busy_poweroff_notify_cb",
        "drivers/mmc/core/sd.c:sd_flush_cache",
        "drivers/mmc/core/sd.c:sd_read_ext_regs",
        "drivers/mmc/core/sd.c:sd_parse_ext_reg",
        "drivers/mmc/core/sd.c:sd_parse_ext_reg",
        "drivers/mmc/core/sd_ops.c:mmc_sd_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594005376,
      "name": "mmc_send_adtc_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
int mmc_send_adtc_data(struct mmc_card * card, struct mmc_host * host, u32 opcode, u32 args, void * buf, unsigned int len)
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
