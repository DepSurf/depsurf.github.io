# Function: <code>nvdimm_get_config_data</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```

```json
{
  "name": "nvdimm_get_config_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586143136,
      "name": "nvdimm_get_config_data",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:88",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586143136,
      "name": "nvdimm_get_config_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```

```json
{
  "name": "nvdimm_get_config_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvdimm_get_config_data",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:85",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586382198,
      "name": "nvdimm_get_config_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071586378624,
      "name": "nvdimm_get_config_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```

```json
{
  "name": "nvdimm_get_config_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586527200,
      "name": "nvdimm_get_config_data",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:85",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586527200,
      "name": "nvdimm_get_config_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```

```json
{
  "name": "nvdimm_get_config_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587308256,
      "name": "nvdimm_get_config_data",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:85",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587308256,
      "name": "nvdimm_get_config_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```

```json
{
  "name": "nvdimm_get_config_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587370288,
      "name": "nvdimm_get_config_data",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:85",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587370288,
      "name": "nvdimm_get_config_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```

```json
{
  "name": "nvdimm_get_config_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587252320,
      "name": "nvdimm_get_config_data",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:85",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587252320,
      "name": "nvdimm_get_config_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```

```json
{
  "name": "nvdimm_get_config_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587819152,
      "name": "nvdimm_get_config_data",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:85",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587819152,
      "name": "nvdimm_get_config_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```

```json
{
  "name": "nvdimm_get_config_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589168032,
      "name": "nvdimm_get_config_data",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:81",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589168032,
      "name": "nvdimm_get_config_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```

```json
{
  "name": "nvdimm_get_config_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590720128,
      "name": "nvdimm_get_config_data",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:81",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590720128,
      "name": "nvdimm_get_config_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```

```json
{
  "name": "nvdimm_get_config_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591061280,
      "name": "nvdimm_get_config_data",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:81",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591061280,
      "name": "nvdimm_get_config_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```

```json
{
  "name": "nvdimm_get_config_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591406032,
      "name": "nvdimm_get_config_data",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:83",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591406032,
      "name": "nvdimm_get_config_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```

```json
{
  "name": "nvdimm_get_config_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499413304,
      "name": "nvdimm_get_config_data",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:85",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499413304,
      "name": "nvdimm_get_config_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```

```json
{
  "name": "nvdimm_get_config_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292655264,
      "name": "nvdimm_get_config_data",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:85",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292655264,
      "name": "nvdimm_get_config_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```

```json
{
  "name": "nvdimm_get_config_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276642194,
      "name": "nvdimm_get_config_data",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:85",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276642194,
      "name": "nvdimm_get_config_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```

```json
{
  "name": "nvdimm_get_config_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586217680,
      "name": "nvdimm_get_config_data",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:85",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586217680,
      "name": "nvdimm_get_config_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```

```json
{
  "name": "nvdimm_get_config_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586036048,
      "name": "nvdimm_get_config_data",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:85",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586036048,
      "name": "nvdimm_get_config_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```

```json
{
  "name": "nvdimm_get_config_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586475168,
      "name": "nvdimm_get_config_data",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:85",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586475168,
      "name": "nvdimm_get_config_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```

```json
{
  "name": "nvdimm_get_config_data",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586586848,
      "name": "nvdimm_get_config_data",
      "external": true,
      "loc": "drivers/nvdimm/dimm_devs.c:85",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/label.c:nd_label_data_init",
        "drivers/nvdimm/label.c:nd_label_data_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586586848,
      "name": "nvdimm_get_config_data",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int nvdimm_get_config_data(struct nvdimm_drvdata * ndd, void * buf, size_t offset, size_t len)
```
</details>
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
