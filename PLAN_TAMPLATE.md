# {TITLE} — {Plan Type: Fix / Feature / Refactor / Investigation}

> **Status**: {Draft | Analysis Complete | In Progress | Done}  
> **Created**: {YYYY-MM-DD}  
> **Severity**: {Critical | High | Medium | Low} *(for fixes)*  
> **Priority**: {P0 | P1 | P2 | P3} *(for features)*

---

## 1. Problem / Objective

<!-- What's broken, or what do we want to achieve? Be specific. -->
<!-- For bugs: describe the observed vs expected behavior -->
<!-- For features: describe the desired outcome -->

**Observed**:  
{What's happening now}

**Expected**:  
{What should happen instead}

**Evidence**:  
{Logs, screenshots, data samples, reproduction steps}

---

## 2. Root Cause Analysis

<!-- Only for bug fixes. Remove this section for feature plans. -->

### Finding 1: {Short description}

**File**: `{path/to/file.py}` (lines X-Y)

```python
# relevant code snippet showing the problem
```

**Why it fails**: {Explanation of the logic error}

### Finding 2: {Short description}

<!-- Repeat as needed -->

---

## 3. Solution Design

<!-- High-level approach before diving into phases -->

**Approach**: {Brief 1-2 sentence summary of the solution strategy}

**Alternatives Considered**:
| Approach | Pros | Cons | Decision |
|----------|------|------|----------|
| {Option A} | ... | ... | ✅ Chosen |
| {Option B} | ... | ... | ❌ Rejected |

---

## 4. Implementation Phases

### Phase 1: {Title}

**Goal**: {What this phase achieves}  
**File(s)**: `{path/to/file}`

**Changes**:

```diff
-old code
+new code
```

<!-- Or describe the changes in detail if diff isn't practical -->

### Phase 2: {Title}

<!-- Repeat as needed -->

### Phase N: Testing & Validation

1. **Unit test**: {What to test}
2. **Integration test**: {What to verify end-to-end}
3. **Manual verification**: {Steps to confirm the fix/feature works}

```python
# Example test case
def test_the_fix():
    """Description of what this validates."""
    # setup
    # action
    # assertion
```

---

## 5. Impact Assessment

| Area | Impact |
|------|--------|
| **{Area 1}** | {Description} |
| **{Area 2}** | {Description} |
| **Breaking Changes** | {None / describe what breaks} |
| **Re-indexing** | {Required / Not required} |
| **Dependencies** | {New packages / None} |

---

## 6. Files to Modify

| File | Change Summary |
|------|----------------|
| `{path/to/file1}` | {What changes} |
| `{path/to/file2}` | {What changes} |
| `{path/to/test}` | {New tests to add} |

---

## 7. Open Questions

<!-- Remove this section if none -->

- [ ] {Question that needs answering before implementation}
- [ ] {Decision that needs stakeholder input}

---

## 8. Checklist

- [ ] Root cause confirmed
- [ ] Solution reviewed
- [ ] Implementation complete
- [ ] Tests passing
- [ ] Re-index / migration done (if needed)
- [ ] Documentation updated
