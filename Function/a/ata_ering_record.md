# Function: <code>ata_ering_record</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584964690,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:378",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
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
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585331890,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:378",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
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
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585532930,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:378",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
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
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585618930,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:378",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void ata_ering_record(struct ata_ering * ering, unsigned int eflags, unsigned int err_mask)
```

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586043632,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:378",
      "file": "drivers/ata/libata-eh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586043632,
      "name": "ata_ering_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void ata_ering_record(struct ata_ering * ering, unsigned int eflags, unsigned int err_mask)
```

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586291184,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:378",
      "file": "drivers/ata/libata-eh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586291184,
      "name": "ata_ering_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void ata_ering_record(struct ata_ering * ering, unsigned int eflags, unsigned int err_mask)
```

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586432752,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:378",
      "file": "drivers/ata/libata-eh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586432752,
      "name": "ata_ering_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void ata_ering_record(struct ata_ering * ering, unsigned int eflags, unsigned int err_mask)
```

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:361",
      "file": "drivers/ata/libata-eh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586677568,
      "name": "ata_ering_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071586700831,
      "name": "ata_ering_record.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586831618,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:361",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587637319,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:360",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_speed_down"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587698263,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:360",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_speed_down"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587577191,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:360",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_speed_down"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588159360,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:368",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_speed_down"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589539854,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:368",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_speed_down"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591130990,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:370",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_speed_down"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591488890,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:370",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_speed_down"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591837626,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:372",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_speed_down"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499761872,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:361",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232206548,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:361",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293107232,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:361",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276919038,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:361",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586590194,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:361",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586458706,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:361",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586786178,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:361",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ata_ering_record",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586892226,
      "name": "ata_ering_record",
      "external": false,
      "loc": "drivers/ata/libata-eh.c:361",
      "file": "drivers/ata/libata-eh.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_eh_schedule_probe",
        "drivers/ata/libata-eh.c:ata_eh_link_autopsy"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void ata_ering_record(struct ata_ering * ering, unsigned int eflags, unsigned int err_mask)
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
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
void ata_ering_record(struct ata_ering * ering, unsigned int eflags, unsigned int err_mask)
```
</details>
</li>
</ul>
