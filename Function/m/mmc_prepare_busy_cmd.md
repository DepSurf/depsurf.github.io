# Function: <code>mmc_prepare_busy_cmd</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mmc_prepare_busy_cmd(struct mmc_host * host, struct mmc_command * cmd, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_prepare_busy_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589596360,
      "name": "mmc_prepare_busy_cmd",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:528",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/mmc.c:_mmc_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589599568,
      "name": "mmc_prepare_busy_cmd",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mmc_prepare_busy_cmd(struct mmc_host * host, struct mmc_command * cmd, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_prepare_busy_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591093631,
      "name": "mmc_prepare_busy_cmd",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:558",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/mmc.c:_mmc_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591096288,
      "name": "mmc_prepare_busy_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
bool mmc_prepare_busy_cmd(struct mmc_host * host, struct mmc_command * cmd, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_prepare_busy_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592812032,
      "name": "mmc_prepare_busy_cmd",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:558",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/mmc.c:_mmc_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592814976,
      "name": "mmc_prepare_busy_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
bool mmc_prepare_busy_cmd(struct mmc_host * host, struct mmc_command * cmd, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_prepare_busy_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593248822,
      "name": "mmc_prepare_busy_cmd",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:558",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/mmc.c:_mmc_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593245184,
      "name": "mmc_prepare_busy_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
bool mmc_prepare_busy_cmd(struct mmc_host * host, struct mmc_command * cmd, unsigned int timeout_ms)
```

```json
{
  "name": "mmc_prepare_busy_cmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594003974,
      "name": "mmc_prepare_busy_cmd",
      "external": true,
      "loc": "drivers/mmc/core/mmc_ops.c:558",
      "file": "drivers/mmc/core/mmc_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/mmc.c:_mmc_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594000336,
      "name": "mmc_prepare_busy_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
bool mmc_prepare_busy_cmd(struct mmc_host * host, struct mmc_command * cmd, unsigned int timeout_ms)
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
