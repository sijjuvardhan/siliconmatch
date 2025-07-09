# 🧬 SiliconMatch: CPU Fingerprint via Software Benchmarks

**SiliconMatch** is a lightweight software-only project that generates a unique fingerprint for your CPU — without any hardware sensors or admin access.

### 🔧 What It Does
It runs 4 benchmark tests:
- Integer addition
- Floating-point multiplication
- Memory access
- Branching logic

Each test is run 20 times, then a fingerprint is calculated based on average execution time.

### 🧪 Example Output

```json
{
  "int_add_avg": 0.712843,
  "float_mul_avg": 0.305294,
  "memory_access_avg": 1.178123,
  "branching_avg": 0.398229
}
