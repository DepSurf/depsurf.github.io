# Function: <code>hvc_instantiate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584081680,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:272",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584081680,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584412240,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:272",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584412240,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584594640,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:272",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584594640,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584677168,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:271",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584677168,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585089584,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:258",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585089584,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585323216,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:258",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585323216,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585446848,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585446848,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585662688,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585662688,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585803664,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585803664,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586533856,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586533856,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586644960,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586644960,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586528912,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586528912,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587066832,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587066832,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588369776,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588369776,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589792256,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589792256,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590097328,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590097328,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590436624,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590436624,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498521440,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498521440,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231174968,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231174968,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291741712,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_vio.c:hvc_vio_init_early",
        "drivers/tty/hvc/hvc_opal.c:hvc_opal_init_early",
        "drivers/tty/hvc/hvc_opal.c:hvc_opal_probe",
        "drivers/tty/hvc/hvc_opal.c:hvc_opal_probe",
        "drivers/tty/hvc/hvc_rtas.c:hvc_rtas_console_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291741712,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276148214,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_riscv_sbi.c:hvc_sbi_console_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276148214,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585564656,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585564656,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585434480,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585434480,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585754064,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585754064,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int hvc_instantiate(uint32_t vtermno, int index, const struct hv_ops * ops)
```

```json
{
  "name": "hvc_instantiate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585862016,
      "name": "hvc_instantiate",
      "external": true,
      "loc": "drivers/tty/hvc/hvc_console.c:285",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_xen.c:xen_cons_init",
        "drivers/char/virtio_console.c:virtio_cons_early_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585862016,
      "name": "hvc_instantiate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
