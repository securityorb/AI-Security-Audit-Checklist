# AI Security Audit Checklist

## 1. Data Risk (MAP)

- [ ] Does the system process PII?
- [ ] Does the system process PHI?
- [ ] Is data encrypted in transit and at rest?
- [ ] Is data minimized?

Risk Level: ______

---

## 2. Exposure Risk (MAP)

- [ ] Is the system publicly accessible?
- [ ] Are APIs authenticated?
- [ ] Are rate limits enforced?

Risk Level: ______

---

## 3. Model Risk (MEASURE)

- [ ] Is the model externally hosted?
- [ ] Is model behavior tested for:
  - [ ] Prompt Injection
  - [ ] Data Leakage
  - [ ] Hallucinations
- [ ] Are adversarial tests performed?

Risk Level: ______

---

## 4. Autonomy Risk (MEASURE)

- [ ] Does the system make automated decisions?
- [ ] Is human oversight implemented?
- [ ] Are critical decisions reviewed?

Risk Level: ______

---

## 5. Governance Controls (GOVERN / MANAGE)

- [ ] AI policy exists
- [ ] Risk assessments are documented
- [ ] Monitoring is implemented
- [ ] Incident response plan exists

Risk Level: ______

---

## FINAL RISK DECISION

- Low / Medium / High

Decision:
- Approve / Review / Reject
