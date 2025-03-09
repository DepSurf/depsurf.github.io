# Function: <code>mmc_wait_for_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585920080,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:734",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_set_blockcount",
        "drivers/mmc/core/core.c:mmc_set_signal_voltage",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_send_status",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_all_send_cid",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585920080,
      "name": "mmc_wait_for_cmd",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586324048,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:735",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blockcount",
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_signal_voltage",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_all_send_cid",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_status",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586324048,
      "name": "mmc_wait_for_cmd",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586532864,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:808",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blockcount",
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_signal_voltage",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_all_send_cid",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:mmc_deselect_cards",
        "drivers/mmc/core/mmc_ops.c:mmc_select_card",
        "drivers/mmc/core/mmc_ops.c:mmc_send_status",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586532864,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586654608,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:687",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blockcount",
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:mmc_deselect_cards",
        "drivers/mmc/core/mmc_ops.c:mmc_select_card",
        "drivers/mmc/core/mmc_ops.c:__mmc_send_status",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586654608,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587136768,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:841",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blockcount",
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:mmc_deselect_cards",
        "drivers/mmc/core/mmc_ops.c:mmc_select_card",
        "drivers/mmc/core/mmc_ops.c:__mmc_send_status",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587136768,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587436784,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:640",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blockcount",
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:mmc_deselect_cards",
        "drivers/mmc/core/mmc_ops.c:mmc_select_card",
        "drivers/mmc/core/mmc_ops.c:__mmc_send_status",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587436784,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587616976,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:640",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:mmc_deselect_cards",
        "drivers/mmc/core/mmc_ops.c:mmc_select_card",
        "drivers/mmc/core/mmc_ops.c:__mmc_send_status",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587616976,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:638",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:_mmc_select_card",
        "drivers/mmc/core/mmc_ops.c:__mmc_send_status",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587904914,
      "name": "mmc_wait_for_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071587894560,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588100112,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:638",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:_mmc_select_card",
        "drivers/mmc/core/mmc_ops.c:__mmc_send_status",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588100112,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588962016,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:621",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:mmc_sleep",
        "drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:mmc_deselect_cards",
        "drivers/mmc/core/mmc_ops.c:mmc_select_card",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:sdio_reset",
        "drivers/mmc/core/sdio_ops.c:sdio_reset",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588962016,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588973712,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:621",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:mmc_sleep",
        "drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_send_hpi_cmd",
        "drivers/mmc/core/mmc_ops.c:mmc_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:mmc_deselect_cards",
        "drivers/mmc/core/mmc_ops.c:mmc_select_card",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:sdio_reset",
        "drivers/mmc/core/sdio_ops.c:sdio_reset",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588973712,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588862304,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:622",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:mmc_deselect_cards",
        "drivers/mmc/core/mmc_ops.c:mmc_select_card",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:sdio_reset",
        "drivers/mmc/core/sdio_ops.c:sdio_reset",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588862304,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589564384,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:622",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_send_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:mmc_deselect_cards",
        "drivers/mmc/core/mmc_ops.c:mmc_select_card",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:sdio_reset",
        "drivers/mmc/core/sdio_ops.c:sdio_reset",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589564384,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591059600,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:622",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_send_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:__mmc_send_op_cond_cb",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:mmc_deselect_cards",
        "drivers/mmc/core/mmc_ops.c:mmc_select_card",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:sdio_reset",
        "drivers/mmc/core/sdio_ops.c:sdio_reset",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591059600,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592772592,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:621",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_send_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:__mmc_send_op_cond_cb",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:mmc_deselect_cards",
        "drivers/mmc/core/mmc_ops.c:mmc_select_card",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:sdio_reset",
        "drivers/mmc/core/sdio_ops.c:sdio_reset",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592772592,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593209072,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:621",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_send_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:__mmc_send_op_cond_cb",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:mmc_deselect_cards",
        "drivers/mmc/core/mmc_ops.c:mmc_select_card",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:sdio_reset",
        "drivers/mmc/core/sdio_ops.c:sdio_reset",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593209072,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593963648,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:626",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_send_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:__mmc_send_op_cond_cb",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:mmc_deselect_cards",
        "drivers/mmc/core/mmc_ops.c:mmc_select_card",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:sdio_reset",
        "drivers/mmc/core/sdio_ops.c:sdio_reset",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593963648,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501349776,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:638",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:_mmc_select_card",
        "drivers/mmc/core/mmc_ops.c:__mmc_send_status",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond",
        "drivers/mmc/core/block.c:mmc_blk_fix_state",
        "drivers/mmc/core/block.c:mmc_sd_num_wr_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501349776,
      "name": "mmc_wait_for_cmd",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233841348,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:638",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:_mmc_select_card",
        "drivers/mmc/core/mmc_ops.c:__mmc_send_status",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond",
        "drivers/mmc/core/block.c:mmc_blk_fix_state",
        "drivers/mmc/core/block.c:mmc_sd_num_wr_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233841348,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294901248,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:638",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:_mmc_select_card",
        "drivers/mmc/core/mmc_ops.c:__mmc_send_status",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294901248,
      "name": "mmc_wait_for_cmd",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277966278,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:638",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:_mmc_select_card",
        "drivers/mmc/core/mmc_ops.c:__mmc_send_status",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond",
        "drivers/mmc/core/block.c:mmc_blk_fix_state",
        "drivers/mmc/core/block.c:mmc_sd_num_wr_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277966278,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587721680,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:638",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:_mmc_select_card",
        "drivers/mmc/core/mmc_ops.c:__mmc_send_status",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587721680,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588054640,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:638",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:_mmc_select_card",
        "drivers/mmc/core/mmc_ops.c:__mmc_send_status",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588054640,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```

```json
{
  "name": "mmc_wait_for_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588172176,
      "name": "mmc_wait_for_cmd",
      "external": true,
      "loc": "drivers/mmc/core/core.c:638",
      "file": "drivers/mmc/core/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_set_blocklen",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_set_uhs_voltage",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi",
        "drivers/mmc/core/mmc_ops.c:mmc_abort_tuning",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_set_crc",
        "drivers/mmc/core/mmc_ops.c:mmc_spi_read_ocr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_cxd_native",
        "drivers/mmc/core/mmc_ops.c:mmc_set_relative_addr",
        "drivers/mmc/core/mmc_ops.c:mmc_send_op_cond",
        "drivers/mmc/core/mmc_ops.c:mmc_go_idle",
        "drivers/mmc/core/mmc_ops.c:mmc_set_dsr",
        "drivers/mmc/core/mmc_ops.c:_mmc_select_card",
        "drivers/mmc/core/mmc_ops.c:__mmc_send_status",
        "drivers/mmc/core/sd_ops.c:mmc_send_relative_addr",
        "drivers/mmc/core/sd_ops.c:mmc_send_if_cond",
        "drivers/mmc/core/sd_ops.c:mmc_app_cmd",
        "drivers/mmc/core/sdio_ops.c:mmc_io_rw_direct_host",
        "drivers/mmc/core/sdio_ops.c:mmc_send_io_op_cond"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588172176,
      "name": "mmc_wait_for_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int mmc_wait_for_cmd(struct mmc_host * host, struct mmc_command * cmd, int retries)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
