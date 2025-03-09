# Function: <code>mmc_retune_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585931712,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:93",
      "file": "drivers/mmc/core/host.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_start_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585931712,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586336488,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:116",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586336576,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586545256,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:116",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_req",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586545344,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586668840,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:114",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_areq",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_start_bkops",
        "drivers/mmc/core/mmc_ops.c:mmc_start_bkops",
        "drivers/mmc/core/mmc_ops.c:mmc_stop_bkops",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586668016,
      "name": "mmc_retune_release.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586668928,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587153048,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:114",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_start_areq",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_stop_bkops",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587152000,
      "name": "mmc_retune_release.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071587152016,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587452545,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:114",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_stop_bkops",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587451504,
      "name": "mmc_retune_release.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071587451520,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587632689,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:114",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587631648,
      "name": "mmc_retune_release.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071587631664,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587910497,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:111",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sdio_io.c:sdio_retune_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587910874,
      "name": "mmc_retune_release.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587910899,
      "name": "mmc_retune_release.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071587909440,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588116449,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:111",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sdio_io.c:sdio_retune_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588115376,
      "name": "mmc_retune_release.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071588115392,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588979009,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:111",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/mmc.c:mmc_sleep",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sdio_io.c:sdio_retune_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588978800,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588990349,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:113",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/mmc.c:mmc_sleep",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sdio_io.c:sdio_retune_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588990032,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588877729,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:152",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sdio_io.c:sdio_retune_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588876848,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589580113,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:170",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sdio_io.c:sdio_retune_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589576608,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591075345,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:170",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sdio_io.c:sdio_retune_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591071664,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592791217,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:170",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sdio_io.c:sdio_retune_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592786992,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593227793,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:170",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sdio_io.c:sdio_retune_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593223376,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593982689,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:169",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:mmc_sanitize",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio_io.c:sdio_retune_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593978224,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501369708,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:111",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sdio_io.c:sdio_retune_release",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:mmc_blk_fix_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501368552,
      "name": "mmc_retune_release.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446603336501368584,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233859532,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:111",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sdio_io.c:sdio_retune_release",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:mmc_blk_fix_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233858468,
      "name": "mmc_retune_release.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 3233858516,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294925324,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:111",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sdio_io.c:sdio_retune_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294923904,
      "name": "mmc_retune_release.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 13835058055294923920,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277980512,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:111",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sdio_io.c:sdio_retune_release",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery",
        "drivers/mmc/core/block.c:mmc_blk_fix_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277979442,
      "name": "mmc_retune_release.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446743936277979470,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587738017,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:111",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sdio_io.c:sdio_retune_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587736944,
      "name": "mmc_retune_release.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071587736960,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588070977,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:111",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sdio_io.c:sdio_retune_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588069904,
      "name": "mmc_retune_release.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071588069920,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mmc_retune_release(struct mmc_host * host)
```

```json
{
  "name": "mmc_retune_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588188513,
      "name": "mmc_retune_release",
      "external": true,
      "loc": "drivers/mmc/core/host.c:111",
      "file": "drivers/mmc/core/host.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": [
        "drivers/mmc/core/core.c:mmc_do_erase",
        "drivers/mmc/core/core.c:mmc_cqe_recovery",
        "drivers/mmc/core/core.c:mmc_wait_for_req_done",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc.c:_mmc_suspend",
        "drivers/mmc/core/mmc_ops.c:__mmc_switch",
        "drivers/mmc/core/sdio_io.c:sdio_retune_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588187440,
      "name": "mmc_retune_release.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071588187456,
      "name": "mmc_retune_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void mmc_retune_release(struct mmc_host * host)
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
