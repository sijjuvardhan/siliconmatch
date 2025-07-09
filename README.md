# 🧬 SiliconMatch: Software-Only CPU Fingerprinting

**SiliconMatch** is a coding-only project that uniquely identifies a CPU’s behavioral profile — without needing any external hardware or admin access.

This is ideal for system profiling, CPU comparisons, or edge-device authentication.

---

## 🚀 What It Does

It performs 4 lightweight benchmarks:

| Benchmark Type | Description |
|----------------|-------------|
| 🧮 Integer Addition | Measures pure arithmetic speed |
| ✖️ Float Multiplication | Measures floating-point unit performance |
| 💾 Memory Access | Simulates array access and cache behavior |
| 🔁 Branching Logic | Tests if-else condition prediction |

Each benchmark runs 20 times → averages are calculated → and the fingerprint is saved in `.json`.

---

## 🧪 Example Output (JSON)

```json
{
  "int_add_avg": 0.712843,
  "float_mul_avg": 0.305294,
  "memory_access_avg": 1.178123,
  "branching_avg": 0.398229
}
