# Function: <code>dwc2_desc_list_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585326320,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:113",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585326320,
      "name": "dwc2_desc_list_free.isra.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585721136,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:122",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585721136,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585909744,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:122",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585909744,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585991760,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:122",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585991760,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586435744,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:123",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586435744,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586700368,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:123",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586700368,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586857520,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:123",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586857520,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587116304,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:123",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587116304,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587316464,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:123",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587316464,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588174768,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:123",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588174768,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588210480,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:123",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588210480,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588093744,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:123",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588093744,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588727120,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:123",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588727120,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590145520,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:123",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590145520,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591759888,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:93",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591759888,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592183184,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:93",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592183184,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592923904,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:93",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592923904,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500434248,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:123",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500434248,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232888328,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:123",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232888328,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293782640,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:123",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293782640,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277323636,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:123",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277323636,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587022544,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:123",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587022544,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587271024,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:123",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587271024,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_desc_list_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587377792,
      "name": "dwc2_desc_list_free",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_ddma.c:123",
      "file": "drivers/usb/dwc2/hcd_ddma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_free_ddma",
        "drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_qh_init_ddma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587377792,
      "name": "dwc2_desc_list_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```
</details>
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
void dwc2_desc_list_free(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
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
