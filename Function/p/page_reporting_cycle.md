# Function: <code>page_reporting_cycle</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int page_reporting_cycle(struct page_reporting_dev_info * prdev, struct zone * zone, unsigned int order, unsigned int mt, struct scatterlist * sgl, unsigned int * offset)
```

```json
{
  "name": "page_reporting_cycle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582044224,
      "name": "page_reporting_cycle",
      "external": false,
      "loc": "mm/page_reporting.c:109",
      "file": "mm/page_reporting.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_reporting.c:page_reporting_process_zone",
        "mm/page_reporting.c:page_reporting_process_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582044224,
      "name": "page_reporting_cycle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
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
int page_reporting_cycle(struct page_reporting_dev_info * prdev, struct zone * zone, unsigned int order, unsigned int mt, struct scatterlist * sgl, unsigned int * offset)
```

```json
{
  "name": "page_reporting_cycle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582093200,
      "name": "page_reporting_cycle",
      "external": false,
      "loc": "mm/page_reporting.c:109",
      "file": "mm/page_reporting.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_reporting.c:page_reporting_process_zone",
        "mm/page_reporting.c:page_reporting_process_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582093200,
      "name": "page_reporting_cycle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 777
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
int page_reporting_cycle(struct page_reporting_dev_info * prdev, struct zone * zone, unsigned int order, unsigned int mt, struct scatterlist * sgl, unsigned int * offset)
```

```json
{
  "name": "page_reporting_cycle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582118272,
      "name": "page_reporting_cycle",
      "external": false,
      "loc": "mm/page_reporting.c:109",
      "file": "mm/page_reporting.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_reporting.c:page_reporting_process",
        "mm/page_reporting.c:page_reporting_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582118272,
      "name": "page_reporting_cycle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 774
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
int page_reporting_cycle(struct page_reporting_dev_info * prdev, struct zone * zone, unsigned int order, unsigned int mt, struct scatterlist * sgl, unsigned int * offset)
```

```json
{
  "name": "page_reporting_cycle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_reporting_cycle",
      "external": false,
      "loc": "mm/page_reporting.c:114",
      "file": "mm/page_reporting.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_reporting.c:page_reporting_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582434656,
      "name": "page_reporting_cycle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 859
    },
    {
      "addr": 18446744071592228682,
      "name": "page_reporting_cycle.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int page_reporting_cycle(struct page_reporting_dev_info * prdev, struct zone * zone, unsigned int order, unsigned int mt, struct scatterlist * sgl, unsigned int * offset)
```

```json
{
  "name": "page_reporting_cycle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_reporting_cycle",
      "external": false,
      "loc": "mm/page_reporting.c:114",
      "file": "mm/page_reporting.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_reporting.c:page_reporting_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582951264,
      "name": "page_reporting_cycle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 917
    },
    {
      "addr": 18446744071594008149,
      "name": "page_reporting_cycle.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int page_reporting_cycle(struct page_reporting_dev_info * prdev, struct zone * zone, unsigned int order, unsigned int mt, struct scatterlist * sgl, unsigned int * offset)
```

```json
{
  "name": "page_reporting_cycle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_reporting_cycle",
      "external": false,
      "loc": "mm/page_reporting.c:146",
      "file": "mm/page_reporting.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_reporting.c:page_reporting_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583508736,
      "name": "page_reporting_cycle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 917
    },
    {
      "addr": 18446744071596050097,
      "name": "page_reporting_cycle.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int page_reporting_cycle(struct page_reporting_dev_info * prdev, struct zone * zone, unsigned int order, unsigned int mt, struct scatterlist * sgl, unsigned int * offset)
```

```json
{
  "name": "page_reporting_cycle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_reporting_cycle",
      "external": false,
      "loc": "mm/page_reporting.c:146",
      "file": "mm/page_reporting.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_reporting.c:page_reporting_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583723632,
      "name": "page_reporting_cycle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 916
    },
    {
      "addr": 18446744071596572596,
      "name": "page_reporting_cycle.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int page_reporting_cycle(struct page_reporting_dev_info * prdev, struct zone * zone, unsigned int order, unsigned int mt, struct scatterlist * sgl, unsigned int * offset)
```

```json
{
  "name": "page_reporting_cycle",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_reporting_cycle",
      "external": false,
      "loc": "mm/page_reporting.c:146",
      "file": "mm/page_reporting.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_reporting.c:page_reporting_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583924336,
      "name": "page_reporting_cycle",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 916
    },
    {
      "addr": 18446744071597477086,
      "name": "page_reporting_cycle.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int page_reporting_cycle(struct page_reporting_dev_info * prdev, struct zone * zone, unsigned int order, unsigned int mt, struct scatterlist * sgl, unsigned int * offset)
```
</details>
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
