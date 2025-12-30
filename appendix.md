# Appendix A: Common Objections

This appendix addresses common objections to the Halt Invariant.

---

### Objection: “This is just an implementation detail.”

An invariant is a specification-level property, not an implementation choice. If the system is reasoned about as though halting prevents externally observable action, then the invariant is part of the specification, whether stated or not.

---

### Objection: “Our system already supports stopping.”

If so, the invariant can be stated and demonstrated explicitly. The absence of a clear specification makes it difficult to determine whether stopping is guaranteed under partial failure and retries.

---

### Objection: “Perfect halting is impossible.”

This paper does not claim that the invariant is achievable, only that it is widely assumed. Identifying an assumed-but-absent property is independent of its feasibility.

---

### Objection: “This only applies to AI systems.”

The Halt Invariant applies to any system capable of externally observable action, including financial, industrial, and distributed software systems.

---

### Objection: “This is a theoretical concern.”

Violations of the invariant occur whenever actions continue after a declared stop condition. The paper makes no claim about frequency, only possibility.
