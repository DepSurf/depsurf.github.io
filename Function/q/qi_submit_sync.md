# Function: <code>qi_submit_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int qi_submit_sync(struct qi_desc * desc, struct intel_iommu * iommu)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584303472,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1192",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:qi_global_iec",
        "drivers/iommu/dmar.c:qi_flush_context",
        "drivers/iommu/dmar.c:qi_flush_iotlb",
        "drivers/iommu/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/intel-svm.c:intel_mm_release",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/iommu/intel_irq_remapping.c:modify_irte",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584303472,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 983
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
int qi_submit_sync(struct qi_desc * desc, struct intel_iommu * iommu)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584649776,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1208",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/dmar.c:qi_flush_iotlb",
        "drivers/iommu/dmar.c:qi_flush_context",
        "drivers/iommu/dmar.c:qi_global_iec",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/iommu/intel-svm.c:intel_mm_release",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources",
        "drivers/iommu/intel_irq_remapping.c:modify_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584649776,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 875
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
int qi_submit_sync(struct qi_desc * desc, struct intel_iommu * iommu)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584835824,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1209",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/dmar.c:qi_flush_iotlb",
        "drivers/iommu/dmar.c:qi_flush_context",
        "drivers/iommu/dmar.c:qi_global_iec",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/iommu/intel-svm.c:intel_mm_release",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources",
        "drivers/iommu/intel_irq_remapping.c:modify_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584835824,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 875
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
int qi_submit_sync(struct qi_desc * desc, struct intel_iommu * iommu)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584925520,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1218",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/dmar.c:qi_flush_iotlb",
        "drivers/iommu/dmar.c:qi_flush_context",
        "drivers/iommu/dmar.c:qi_global_iec",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/iommu/intel-svm.c:intel_mm_release",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources",
        "drivers/iommu/intel_irq_remapping.c:modify_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584925520,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
int qi_submit_sync(struct qi_desc * desc, struct intel_iommu * iommu)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585346880,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1221",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/dmar.c:qi_flush_iotlb",
        "drivers/iommu/dmar.c:qi_flush_context",
        "drivers/iommu/dmar.c:qi_global_iec",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/iommu/intel-svm.c:intel_mm_release",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources",
        "drivers/iommu/intel_irq_remapping.c:modify_irte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585346880,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 859
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
int qi_submit_sync(struct qi_desc * desc, struct intel_iommu * iommu)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1221",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/dmar.c:qi_flush_iotlb",
        "drivers/iommu/dmar.c:qi_flush_context",
        "drivers/iommu/dmar.c:qi_global_iec",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/iommu/intel-svm.c:intel_mm_release",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585592433,
      "name": "qi_submit_sync.cold.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071585588976,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 784
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
int qi_submit_sync(struct qi_desc * desc, struct intel_iommu * iommu)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1228",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/dmar.c:qi_flush_iotlb",
        "drivers/iommu/dmar.c:qi_flush_context",
        "drivers/iommu/dmar.c:qi_global_iec",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585716689,
      "name": "qi_submit_sync.cold.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071585712928,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1001
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
int qi_submit_sync(struct qi_desc * desc, struct intel_iommu * iommu)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1217",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/dmar.c:qi_flush_iotlb",
        "drivers/iommu/dmar.c:qi_flush_context",
        "drivers/iommu/dmar.c:qi_global_iec",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585944577,
      "name": "qi_submit_sync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071585940832,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 987
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
int qi_submit_sync(struct qi_desc * desc, struct intel_iommu * iommu)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1227",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/dmar.c:qi_flush_iotlb",
        "drivers/iommu/dmar.c:qi_flush_context",
        "drivers/iommu/dmar.c:qi_global_iec",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586087736,
      "name": "qi_submit_sync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071586084016,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 987
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
int qi_submit_sync(struct intel_iommu * iommu, struct qi_desc * desc, unsigned int count, long unsigned int options)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586831664,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1235",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:qi_flush_pasid_cache",
        "drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid",
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_iotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_context",
        "drivers/iommu/intel/dmar.c:qi_global_iec",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586831664,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
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
int qi_submit_sync(struct intel_iommu * iommu, struct qi_desc * desc, unsigned int count, long unsigned int options)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586888336,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1274",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:qi_flush_pasid_cache",
        "drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid",
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_iotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_context",
        "drivers/iommu/intel/dmar.c:qi_global_iec",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586888336,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
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
int qi_submit_sync(struct intel_iommu * iommu, struct qi_desc * desc, unsigned int count, long unsigned int options)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586769136,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1341",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:qi_flush_pasid_cache",
        "drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid",
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_iotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_context",
        "drivers/iommu/intel/dmar.c:qi_global_iec",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586769136,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1061
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
int qi_submit_sync(struct intel_iommu * iommu, struct qi_desc * desc, unsigned int count, long unsigned int options)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587324288,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1340",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:qi_flush_pasid_cache",
        "drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid",
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_iotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_context",
        "drivers/iommu/intel/dmar.c:qi_global_iec",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587324288,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1061
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
int qi_submit_sync(struct intel_iommu * iommu, struct qi_desc * desc, unsigned int count, long unsigned int options)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588638816,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1336",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:qi_flush_pasid_cache",
        "drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid",
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_iotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_context",
        "drivers/iommu/intel/dmar.c:qi_global_iec",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588638816,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1185
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
int qi_submit_sync(struct intel_iommu * iommu, struct qi_desc * desc, unsigned int count, long unsigned int options)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590109024,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1325",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:qi_flush_pasid_cache",
        "drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid",
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_iotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_context",
        "drivers/iommu/intel/dmar.c:qi_global_iec",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590109024,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1198
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
int qi_submit_sync(struct intel_iommu * iommu, struct qi_desc * desc, unsigned int count, long unsigned int options)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590422768,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1346",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:qi_flush_pasid_cache",
        "drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid",
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_iotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_context",
        "drivers/iommu/intel/dmar.c:qi_global_iec",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590422768,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1198
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
int qi_submit_sync(struct intel_iommu * iommu, struct qi_desc * desc, unsigned int count, long unsigned int options)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590766912,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1346",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/dmar.c:qi_flush_pasid_cache",
        "drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid",
        "drivers/iommu/intel/dmar.c:qi_flush_piotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_iotlb",
        "drivers/iommu/intel/dmar.c:qi_flush_context",
        "drivers/iommu/intel/dmar.c:qi_global_iec",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_dirty_tracking",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/svm.c:intel_svm_page_response",
        "drivers/iommu/intel/svm.c:intel_drain_pasid_prq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590766912,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1198
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int qi_submit_sync(struct qi_desc * desc, struct intel_iommu * iommu)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1227",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/dmar.c:qi_flush_iotlb",
        "drivers/iommu/dmar.c:qi_flush_context",
        "drivers/iommu/dmar.c:qi_global_iec",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585848856,
      "name": "qi_submit_sync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071585845136,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 987
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
int qi_submit_sync(struct qi_desc * desc, struct intel_iommu * iommu)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1227",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/dmar.c:qi_flush_iotlb",
        "drivers/iommu/dmar.c:qi_flush_context",
        "drivers/iommu/dmar.c:qi_global_iec",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585707896,
      "name": "qi_submit_sync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071585704176,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 987
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
int qi_submit_sync(struct qi_desc * desc, struct intel_iommu * iommu)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1227",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/dmar.c:qi_flush_iotlb",
        "drivers/iommu/dmar.c:qi_flush_context",
        "drivers/iommu/dmar.c:qi_global_iec",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586037752,
      "name": "qi_submit_sync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071586034032,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 987
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
int qi_submit_sync(struct qi_desc * desc, struct intel_iommu * iommu)
```

```json
{
  "name": "qi_submit_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_submit_sync",
      "external": true,
      "loc": "drivers/iommu/dmar.c:1227",
      "file": "drivers/iommu/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dmar.c:qi_flush_dev_iotlb",
        "drivers/iommu/dmar.c:qi_flush_iotlb",
        "drivers/iommu/dmar.c:qi_flush_context",
        "drivers/iommu/dmar.c:qi_global_iec",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586145736,
      "name": "qi_submit_sync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071586142016,
      "name": "qi_submit_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 988
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int count</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int options</code>
</li>
<li>
<b>Param reordered. </b>
<code>desc, iommu</code> ➡️ <code>iommu, desc, count, options</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int qi_submit_sync(struct qi_desc * desc, struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int qi_submit_sync(struct qi_desc * desc, struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int qi_submit_sync(struct qi_desc * desc, struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int qi_submit_sync(struct qi_desc * desc, struct intel_iommu * iommu)
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
