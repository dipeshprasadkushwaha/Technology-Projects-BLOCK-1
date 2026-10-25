# 🧪 Task 2 — Memory Allocation Test

### 1️⃣ Run this Python script:
```python
import time, numpy as np
start = time.perf_counter()
a = np.random.rand(10_000_000)
end = time.perf_counter()
print('Memory allocation time:', end - start)
```

### 2️⃣ Check memory usage:
```bash
free -h
```

📁 Save results in `results/memory.txt`
<img width="3072" height="4096" alt="1548" src="https://github.com/user-attachments/assets/a44f1f56-e3e2-49f9-a16f-6cc6b9234d22" />
<img width="3072" height="1904" alt="1681" src="https://github.com/user-attachments/assets/290de12c-326e-428b-be3a-bd7ef52dba4c" />
