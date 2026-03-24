# 🔔 운영체제 공부

## 🎯 Study Goal

- 운영체제를 **암기 과목이 아닌, 시스템 이해 도구로 학습**
- 백엔드 개발 관점에서 **동시성, 메모리, 성능 문제 해결 능력 확보**
- 기술 면접에서 **깊이 있는 답변 가능 수준까지 이해**

---

## 🧠 Overall Structure

운영체제는 아래 4가지 관점으로 이해한다:

- **Process** → 실행 (CPU 관점)
- **Memory** → 공간 (RAM 관점)
- **File & I/O** → 데이터 (디스크 / 네트워크)
- **System** → 운영체제 내부 구조

<br>

## 🚀 Study Roadmap (중요도 순)

<br>

### 1️⃣ Process & Thread (⭐⭐⭐⭐⭐)

> 동시성의 시작, 백엔드 핵심

- Process vs Thread
- PCB (Process Control Block)
- Context Switching
- CPU Scheduling (FCFS, SJF, RR)
- Multi-threading
- Concurrency vs Parallelism

---

### 2️⃣ Synchronization (⭐⭐⭐⭐⭐)

> 동시성 문제 해결 능력

- Race Condition
- Critical Section
- Mutex / Semaphore
- Deadlock (개념 포함)
- Producer-Consumer Problem

---

### 3️⃣ Memory Management (⭐⭐⭐⭐⭐)

> 성능과 안정성의 핵심

- Virtual Memory
- Paging / Segmentation
- Page Fault
- Page Replacement (LRU, FIFO)

---

### 4️⃣ System Call & Kernel (⭐⭐⭐⭐⭐)

> OS와 프로그램의 연결

- System Call
- User Mode vs Kernel Mode
- Interrupt / Trap
- API vs System Call

---

### 5️⃣ File System & I/O (⭐⭐⭐⭐)

> 데이터 저장과 입출력

- File System Structure
- Disk Scheduling
- Buffer / Cache

---

### 6️⃣ OS Structure (⭐⭐⭐⭐)

> 운영체제 설계 방식

- Monolithic
- Microkernel
- Layered
- Modular
- Hybrid

---

### 7️⃣ Booting & Linking (⭐⭐⭐⭐)

> 프로그램 실행 흐름 이해

- Booting Process (BIOS / UEFI)
- Linker & Loader
- Static vs Dynamic Linking

---

### 8️⃣ Deadlock (⭐⭐⭐⭐⭐)

> 면접 단골 + 동시성 핵심

- Deadlock 조건 (4가지)
- Prevention / Avoidance / Detection / Recovery

---

### 9️⃣ Performance & Monitoring (⭐⭐⭐)

> 실무 성능 분석

- CPU / Memory Monitoring
- Profiling
- Tracing (strace, perf)
