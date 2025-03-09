# Function: <code>ata_acpi_gtf_to_tf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585010774,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:548",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585378164,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:548",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
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
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585578996,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:548",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585662304,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:548",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585662304,
      "name": "ata_acpi_gtf_to_tf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586094528,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:548",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586094528,
      "name": "ata_acpi_gtf_to_tf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586342608,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:548",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586342608,
      "name": "ata_acpi_gtf_to_tf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586483856,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:548",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586483856,
      "name": "ata_acpi_gtf_to_tf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586729248,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:549",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586729248,
      "name": "ata_acpi_gtf_to_tf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586875744,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:549",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586875744,
      "name": "ata_acpi_gtf_to_tf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587684800,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:549",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587684800,
      "name": "ata_acpi_gtf_to_tf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587745424,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:549",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587745424,
      "name": "ata_acpi_gtf_to_tf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587624704,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:549",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587624704,
      "name": "ata_acpi_gtf_to_tf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588209856,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:549",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588209856,
      "name": "ata_acpi_gtf_to_tf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589594768,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:541",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589594768,
      "name": "ata_acpi_gtf_to_tf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591192664,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:541",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591551440,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:541",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591551440,
      "name": "ata_acpi_gtf_to_tf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591899856,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:541",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591899856,
      "name": "ata_acpi_gtf_to_tf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499810936,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:549",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499810936,
      "name": "ata_acpi_gtf_to_tf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586634272,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:549",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586634272,
      "name": "ata_acpi_gtf_to_tf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586502768,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:549",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586502768,
      "name": "ata_acpi_gtf_to_tf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586830304,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:549",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586830304,
      "name": "ata_acpi_gtf_to_tf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```

```json
{
  "name": "ata_acpi_gtf_to_tf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586936416,
      "name": "ata_acpi_gtf_to_tf",
      "external": false,
      "loc": "drivers/ata/libata-acpi.c:549",
      "file": "drivers/ata/libata-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf",
        "drivers/ata/libata-acpi.c:ata_acpi_run_tf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586936416,
      "name": "ata_acpi_gtf_to_tf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```
</details>
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
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```
</details>
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
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void ata_acpi_gtf_to_tf(struct ata_device * dev, const struct ata_acpi_gtf * gtf, struct ata_taskfile * tf)
```
</details>
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
