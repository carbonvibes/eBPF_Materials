# **Introduction to eBPF**

Welcome to the **Introduction to eBPF** repository! This repository is a curated collection of resources, examples, and tools to help you dive into the powerful world of **eBPF (extended Berkeley Packet Filter)**. Whether you’re a beginner or an advanced user, this repository provides theory, practical knowledge, and interactive labs to enhance your understanding of eBPF.

---

## **What is eBPF?**
eBPF is a revolutionary technology that allows you to run custom programs in the Linux kernel safely and efficiently without modifying kernel source code. It’s used for:
- Observability and performance monitoring.
- Networking and security.
- Debugging and tracing applications.

eBPF programs are JIT-compiled and run in a sandboxed environment, offering **minimal overhead** with **maximum flexibility**.

---

## **Resources**

### **Books**
1. **[Learning eBPF by Liz Rice](https://isovalent.com/books/learning-ebpf/#form)**  
   *(Theory Knowledge)* – A great introduction to the concepts and architecture of eBPF.
2. **[BPF Performance Tools by Brendan Gregg](https://github.com/carbonvibes/eBPF_Materials/blob/main/BPF%20Performance%20Tools%20Dec%202019.pdf)**  
   *(Practical Knowledge)* – A comprehensive guide to leveraging eBPF for performance analysis.

---

### **Interactive Labs**
1. **[Interactive eBPF Lab 1](https://isovalent.com/labs/ebpf-tutorial/?utm_source=website-ebpf&utm_medium=referral&utm_campaign=ebpf-lab)**  
   *A beginner-friendly interactive lab to understand eBPF fundamentals.*
2. **[Interactive eBPF Lab 2](https://isovalent.com/labs/ebpf-getting-started/?utm_source=website-ebpf&utm_medium=referral&utm_campaign=ebpf-lab)**  
   *Dive deeper into writing eBPF programs with this hands-on tutorial.*

---

### **YouTube Tutorials**
1. **[Tutorial: Getting Started with eBPF - Liz Rice, Isovalent](https://www.youtube.com/watch?v=TJgxjVTZtfw)**  
   *A beginner's introduction to eBPF, covering key concepts and workflows.*
2. **[A Beginner's Guide to eBPF Programming with Go • Liz Rice • GOTO 2021](https://www.youtube.com/watch?v=uBqRv8bDroc)**  
   *For those who want to learn eBPF using the native Go library.*

---

### **Official Website**
- **[eBPF.io](https://ebpf.io/)**  
   *Stay updated with the latest eBPF developments, projects, and documentation.*

---

## **Ways to Write eBPF Programs**
1. **Libbpf**:  
   - Difficulty: **Very Hard**  
   - Write eBPF programs using **BPF CO-RE (Compile Once, Run Everywhere)** in pure C.  
   - *Highly customizable with full control over your programs.*

2. **BCC Tools (Python Wrappers)**:  
   - Difficulty: **Mid-Hard**  
   - Simplify eBPF programming using higher-level APIs with Python wrappers.  
   - **Note**: BCC Tools does **not** support Go.  
   - **GitHub Repository**: [BCC Tools](https://github.com/iovisor/bcc)

3. **Native Go Library**:  
   - Difficulty: **Mid-Hard**  
   - Write eBPF programs directly in Go using its **native support for eBPF**.  
   - **Useful Repository**: [Cilium eBPF Library for Go](https://github.com/cilium/ebpf)  
   - *Ideal for Go developers, offering flexibility and direct kernel interaction.*

4. **BPFtrace**:  
   - Difficulty: **Easy-Mid**  
   - Write eBPF scripts using a high-level scripting language.  
   - **GitHub Repository**: [BPFtrace](https://github.com/bpftrace/bpftrace)  
   - *Perfect for quick prototyping and observability tasks.*

---

## **Example Tracing Programs**

Explore example programs written with popular eBPF tools to trace system events and gain insights into kernel behavior.

1. **Using BPFtrace**:  
   - GitHub Repository: [BPFtrace Tools Examples](https://github.com/bpftrace/bpftrace/tree/master/tools)  
   - *Examples include simple tracing programs for file operations, system calls, and performance monitoring.*

2. **Using BCC Tools (Python Wrapper)**:  
   - GitHub Repository: [BCC Tools Examples](https://github.com/iovisor/bcc/tree/master/tools)  
   - *Examples include Python-based tools for tracing TCP connections, disk I/O, and process-level events.*

---

## **My Previous Work**
- **LeARN: Leveraging eBPF & AI for Ransomware Nose Out**  
   - *[COMSNETS'25 CSP Proceedings](https://github.com/carbonvibes/eBPF_Materials/blob/main/LeARN.pdf)*  

---
