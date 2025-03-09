# Function: <code>ncsi_channel_has_link</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589335135,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:31",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589331408,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589790239,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:27",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589786656,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590013519,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:26",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590009984,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591045327,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:28",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_tx",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_tx",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_tx",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591042480,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591108943,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:28",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_tx",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_tx",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_tx",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591106112,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591039342,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:28",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591036528,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591881644,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:28",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591877808,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593600967,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:28",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593596720,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595528792,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:28",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595524272,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596037336,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:28",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596032816,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596902008,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:28",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596897392,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503761272,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:26",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503755920,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236385664,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:26",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236381932,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297602148,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:26",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297597040,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279676846,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:26",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279673448,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589617119,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:26",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589613584,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589341647,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:26",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589338112,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590059151,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:26",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590055616,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```

```json
{
  "name": "ncsi_channel_has_link",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590109247,
      "name": "ncsi_channel_has_link",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:26",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_update_tx_channel",
        "net/ncsi/ncsi-manage.c:ncsi_report_link",
        "net/ncsi/ncsi-manage.c:ncsi_channel_is_last"
      ],
      "caller_func": [
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590105712,
      "name": "ncsi_channel_has_link",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
bool ncsi_channel_has_link(struct ncsi_channel * channel)
```
</details>
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
