# Function: <code>sd_parse_ext_reg</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sd_parse_ext_reg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589606852,
      "name": "sd_parse_ext_reg",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:1180",
      "file": "drivers/mmc/core/sd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/sd.c:sd_read_ext_regs"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int sd_parse_ext_reg(struct mmc_card * card, u8 * gen_info_buf, u16 * next_ext_addr)
```

```json
{
  "name": "sd_parse_ext_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sd_parse_ext_reg",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:1187",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:sd_read_ext_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591104288,
      "name": "sd_parse_ext_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
    },
    {
      "addr": 18446744071594550988,
      "name": "sd_parse_ext_reg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
int sd_parse_ext_reg(struct mmc_card * card, u8 * gen_info_buf, u16 * next_ext_addr)
```

```json
{
  "name": "sd_parse_ext_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592824240,
      "name": "sd_parse_ext_reg",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:1189",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:sd_read_ext_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592824240,
      "name": "sd_parse_ext_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 725
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
int sd_parse_ext_reg(struct mmc_card * card, u8 * gen_info_buf, u16 * next_ext_addr)
```

```json
{
  "name": "sd_parse_ext_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593260848,
      "name": "sd_parse_ext_reg",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:1189",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:sd_read_ext_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593260848,
      "name": "sd_parse_ext_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 690
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
int sd_parse_ext_reg(struct mmc_card * card, u8 * gen_info_buf, u16 * next_ext_addr)
```

```json
{
  "name": "sd_parse_ext_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594016320,
      "name": "sd_parse_ext_reg",
      "external": false,
      "loc": "drivers/mmc/core/sd.c:1189",
      "file": "drivers/mmc/core/sd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sd.c:sd_read_ext_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594016320,
      "name": "sd_parse_ext_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int sd_parse_ext_reg(struct mmc_card * card, u8 * gen_info_buf, u16 * next_ext_addr)
```
</details>
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
