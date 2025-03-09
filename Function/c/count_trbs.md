# Function: <code>count_trbs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585897665,
      "name": "count_trbs",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2963",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586086705,
      "name": "count_trbs",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2864",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586169165,
      "name": "count_trbs",
      "external": false,
      "loc": "drivers/usb/host/xhci-ring.c:2964",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586614460,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:2968",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586610784,
      "name": "count_trbs",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586881390,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:2887",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586877760,
      "name": "count_trbs",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587036958,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:2951",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587033264,
      "name": "count_trbs",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587300598,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:2997",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587296368,
      "name": "count_trbs",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587501798,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3024",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587497344,
      "name": "count_trbs",
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
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588370694,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3070",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588368064,
      "name": "count_trbs",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588400886,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3080",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588398224,
      "name": "count_trbs",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588287328,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3269",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588284560,
      "name": "count_trbs",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588940779,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3339",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588937776,
      "name": "count_trbs",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590372226,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3274",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590369008,
      "name": "count_trbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592005938,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3281",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592002560,
      "name": "count_trbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592426674,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3301",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592423312,
      "name": "count_trbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593170418,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3344",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593167056,
      "name": "count_trbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500642776,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3024",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500638520,
      "name": "count_trbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233101800,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3024",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233097396,
      "name": "count_trbs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294063264,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3024",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294058288,
      "name": "count_trbs",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277507314,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3024",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277503652,
      "name": "count_trbs",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587207830,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3024",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587203376,
      "name": "count_trbs",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586966582,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3024",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586962128,
      "name": "count_trbs",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587456358,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3024",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587451904,
      "name": "count_trbs",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
unsigned int count_trbs(u64 addr, u64 len)
```

```json
{
  "name": "count_trbs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587563750,
      "name": "count_trbs",
      "external": true,
      "loc": "drivers/usb/host/xhci-ring.c:3024",
      "file": "drivers/usb/host/xhci-ring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare",
        "drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx",
        "drivers/usb/host/xhci-ring.c:xhci_queue_bulk_tx"
      ],
      "caller_func": [
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587559200,
      "name": "count_trbs",
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
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
unsigned int count_trbs(u64 addr, u64 len)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
