# Function: <code>genpd_finish_resume</code>

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
int genpd_finish_resume(struct device * dev, int (*)(struct device *) resume_noirq)
```

```json
{
  "name": "genpd_finish_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590426256,
      "name": "genpd_finish_resume",
      "external": false,
      "loc": "drivers/base/power/domain.c:1277",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_restore_noirq",
        "drivers/base/power/domain.c:genpd_thaw_noirq",
        "drivers/base/power/domain.c:genpd_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590426256,
      "name": "genpd_finish_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int genpd_finish_resume(struct device * dev, int (*)(struct device *) resume_noirq)
```

```json
{
  "name": "genpd_finish_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590745808,
      "name": "genpd_finish_resume",
      "external": false,
      "loc": "drivers/base/power/domain.c:1303",
      "file": "drivers/base/power/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/domain.c:genpd_restore_noirq",
        "drivers/base/power/domain.c:genpd_thaw_noirq",
        "drivers/base/power/domain.c:genpd_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590745808,
      "name": "genpd_finish_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int genpd_finish_resume(struct device * dev, int (*)(struct device *) resume_noirq)
```

```json
{
  "name": "genpd_finish_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589990544,
      "name": "genpd_finish_resume",
      "external": false,
      "loc": "drivers/pmdomain/core.c:1310",
      "file": "drivers/pmdomain/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pmdomain/core.c:genpd_restore_noirq",
        "drivers/pmdomain/core.c:genpd_thaw_noirq",
        "drivers/pmdomain/core.c:genpd_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589990544,
      "name": "genpd_finish_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int genpd_finish_resume(struct device * dev, int (*)(struct device *) resume_noirq)
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
