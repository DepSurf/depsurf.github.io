# Function: <code>ata_exec_internal_sg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584921232,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1553",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_do_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584921232,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1528
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
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585283648,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1556",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585283648,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1557
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
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585483200,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1563",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585483200,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1586
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
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585566576,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1563",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585566576,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1602
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
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585998288,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1563",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585998288,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1600
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1563",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586263512,
      "name": "ata_exec_internal_sg.cold.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586245856,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1408
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1563",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586403976,
      "name": "ata_exec_internal_sg.cold.54",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586386320,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1408
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
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1547",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586648282,
      "name": "ata_exec_internal_sg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586629968,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1547",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586795736,
      "name": "ata_exec_internal_sg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586777536,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1491",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_dev_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587599665,
      "name": "ata_exec_internal_sg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587583216,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1491",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_dev_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591523652,
      "name": "ata_exec_internal_sg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587649376,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1491",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_dev_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591465329,
      "name": "ata_exec_internal_sg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587529216,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1494",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_dev_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592532600,
      "name": "ata_exec_internal_sg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588106832,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1404
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
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589485072,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1470",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_dev_set_mode",
        "drivers/ata/libata-core.c:ata_read_log_page",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_set_max_sectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589485072,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1446
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
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591066592,
      "name": "ata_exec_internal_sg",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1470",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_dev_set_mode",
        "drivers/ata/libata-core.c:ata_read_log_page",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_set_max_sectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591066592,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1377
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
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591422080,
      "name": "ata_exec_internal_sg",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1504",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_dev_set_mode",
        "drivers/ata/libata-core.c:ata_read_log_page",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_set_max_sectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591422080,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1377
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
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591773552,
      "name": "ata_exec_internal_sg",
      "external": false,
      "loc": "drivers/ata/libata-core.c:1504",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_dev_set_mode",
        "drivers/ata/libata-core.c:ata_read_log_page",
        "drivers/ata/libata-core.c:ata_dev_power_set_active",
        "drivers/ata/libata-core.c:ata_dev_power_set_standby",
        "drivers/ata/libata-core.c:ata_dev_power_is_active",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_hpa_resize",
        "drivers/ata/libata-core.c:ata_set_max_sectors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591773552,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1308
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
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499701368,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1547",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499701368,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1412
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
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232147756,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1547",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-core.c:ata_dev_configure",
        "drivers/ata/libata-core.c:ata_dev_read_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232147756,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1296
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
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293033488,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1547",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293033488,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1496
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
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276869022,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1547",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276869022,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1064
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1547",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586554344,
      "name": "ata_exec_internal_sg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586536192,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1547",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586422920,
      "name": "ata_exec_internal_sg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586404768,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1547",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586750296,
      "name": "ata_exec_internal_sg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586732096,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
unsigned int ata_exec_internal_sg(struct ata_device * dev, struct ata_taskfile * tf, const u8 * cdb, int dma_dir, struct scatterlist * sgl, unsigned int n_elem, long unsigned int timeout)
```

```json
{
  "name": "ata_exec_internal_sg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_exec_internal_sg",
      "external": true,
      "loc": "drivers/ata/libata-core.c:1547",
      "file": "drivers/ata/libata-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-core.c:ata_dev_set_feature",
        "drivers/ata/libata-core.c:ata_do_set_mode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/ata/libata-core.c:ata_set_max_sectors",
        "drivers/ata/libata-core.c:ata_read_native_max_address",
        "drivers/ata/libata-core.c:ata_read_native_max_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586856360,
      "name": "ata_exec_internal_sg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071586838160,
      "name": "ata_exec_internal_sg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1406
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int timeout</code> ➡️ <code>unsigned int timeout</code>
</li>
</ul>
</details>
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
