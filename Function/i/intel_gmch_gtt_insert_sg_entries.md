# Function: <code>intel_gmch_gtt_insert_sg_entries</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void intel_gmch_gtt_insert_sg_entries(struct sg_table * st, unsigned int pg_start, unsigned int flags)
```

```json
{
  "name": "intel_gmch_gtt_insert_sg_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589996480,
      "name": "intel_gmch_gtt_insert_sg_entries",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:855",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589996480,
      "name": "intel_gmch_gtt_insert_sg_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void intel_gmch_gtt_insert_sg_entries(struct sg_table * st, unsigned int pg_start, unsigned int flags)
```

```json
{
  "name": "intel_gmch_gtt_insert_sg_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590305952,
      "name": "intel_gmch_gtt_insert_sg_entries",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:855",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590305952,
      "name": "intel_gmch_gtt_insert_sg_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void intel_gmch_gtt_insert_sg_entries(struct sg_table * st, unsigned int pg_start, unsigned int flags)
```

```json
{
  "name": "intel_gmch_gtt_insert_sg_entries",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590647264,
      "name": "intel_gmch_gtt_insert_sg_entries",
      "external": true,
      "loc": "drivers/char/agp/intel-gtt.c:855",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/agp/intel-gtt.c:intel_fake_agp_insert_entries"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590647264,
      "name": "intel_gmch_gtt_insert_sg_entries",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void intel_gmch_gtt_insert_sg_entries(struct sg_table * st, unsigned int pg_start, unsigned int flags)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
