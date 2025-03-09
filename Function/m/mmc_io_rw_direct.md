# Function: <code>mmc_io_rw_direct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585964736,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:114",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585964736,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586370176,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:114",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586370176,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586579008,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:112",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586579008,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586704112,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:112",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586704112,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587188880,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:112",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587188880,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587489152,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:112",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587489152,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587669296,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:112",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587669296,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587947552,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:108",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587947552,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588153520,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:108",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588153520,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589017808,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:108",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode",
        "drivers/mmc/core/sdio.c:sdio_select_driver_type",
        "drivers/mmc/core/sdio.c:sdio_select_driver_type",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_fbr",
        "drivers/mmc/core/sdio.c:sdio_read_fbr",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_get_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:sdio_get_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589017808,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589027152,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:108",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode",
        "drivers/mmc/core/sdio.c:sdio_select_driver_type",
        "drivers/mmc/core/sdio.c:sdio_select_driver_type",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_fbr",
        "drivers/mmc/core/sdio.c:sdio_read_fbr",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_get_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:sdio_get_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589027152,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588914448,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:108",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588914448,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589621328,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:108",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589621328,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591119968,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:108",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode",
        "drivers/mmc/core/sdio.c:mmc_sdio_switch_hs",
        "drivers/mmc/core/sdio.c:mmc_sdio_switch_hs",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591119968,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592842064,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:108",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode",
        "drivers/mmc/core/sdio.c:mmc_sdio_switch_hs",
        "drivers/mmc/core/sdio.c:mmc_sdio_switch_hs",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592842064,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593278720,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:108",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode",
        "drivers/mmc/core/sdio.c:mmc_sdio_switch_hs",
        "drivers/mmc/core/sdio.c:mmc_sdio_switch_hs",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593278720,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594034656,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:108",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode",
        "drivers/mmc/core/sdio.c:sdio_set_bus_speed_mode",
        "drivers/mmc/core/sdio.c:mmc_sdio_switch_hs",
        "drivers/mmc/core/sdio.c:mmc_sdio_switch_hs",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio.c:sdio_read_cccr",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594034656,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501406304,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:108",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501406304,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233895476,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:108",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233895476,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294973056,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:108",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294973056,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278012886,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:108",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278012886,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587775088,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:108",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587775088,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588108048,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:108",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588108048,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
```

```json
{
  "name": "mmc_io_rw_direct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588225584,
      "name": "mmc_io_rw_direct",
      "external": true,
      "loc": "drivers/mmc/core/sdio_ops.c:108",
      "file": "drivers/mmc/core/sdio_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_attach_sdio",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio.c:mmc_sdio_init_card",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_cis.c:sdio_read_cis",
        "drivers/mmc/core/sdio_io.c:sdio_f0_readb",
        "drivers/mmc/core/sdio_io.c:sdio_writeb_readb",
        "drivers/mmc/core/sdio_io.c:sdio_readb",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_set_block_size",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_disable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_io.c:sdio_enable_func",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs",
        "drivers/mmc/core/sdio_irq.c:process_sdio_pending_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588225584,
      "name": "mmc_io_rw_direct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
int mmc_io_rw_direct(struct mmc_card * card, int write, unsigned int fn, unsigned int addr, u8 in, u8 * out)
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
