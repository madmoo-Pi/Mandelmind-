# MandelMind Safety Acknowledgment (CC-0)

## **No Warranty**  
This project is in the **public domain (CC-0)**. By using it, you agree that:  
- There is **no guarantee** of stability, safety, or intended behavior.  
- The authors **are not liable** for any consequences (e.g., runaway recursion, existential dread).  

## **Known Risks**  
1. **50% Fractal Loop Failure:** May cause resource exhaustion.  
2. **DeepSeek-R1 Integration:** Local LLM could generate unpredictable meta-cognitive outputs.  

## **Mitigations**  
- Run in a sandboxed environment (e.g., Docker with CPU/memory limits).  
- Monitor recursion depth with `ulimit -t 300` (max 5min runtime).  
