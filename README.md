# 📘 GitHub SOP – Task, Time & Testing Flow

This SOP defines how tasks move through GitHub to ensure accurate time tracking, clear ownership, and consistent delivery across multiple projects and teams.

---

## 1️⃣ New Task Creation

- All new tasks must have a **full brief** before work starts.
- Tasks are created in **Backlog** or **Ready**.
- The brief must be sufficient for a developer to complete the task without further clarification.

**Ownership:** Project Manager / Project Coordinator

---

## 2️⃣ Development

- Developer moves the task to **In Progress**.
- Developer works strictly according to the brief.
- Tasks are intentionally small and typically completed within a short time frame.
- Developers are responsible only for development, not testing or task coordination.

**Ownership:** Developer

---

## 3️⃣ Review Readiness & Time Logging (Mandatory Gate)

- **Hours must be logged before the task may be moved to Review.**
- A task may **not** enter Review unless:
  - Development is complete
  - Time has been captured
- Once hours are logged, the developer moves the task to **Review** and assigns a reviewer.

**Ownership:** Developer

---

## 4️⃣ Code Review

- Reviewer evaluates the task against the brief and acceptance criteria.

### 4.1 Review Passed

- Task remains in **Review**
- Reviewer assigns **Mpho** to create a **testing subtask**
- Testing subtasks are created only after review approval to avoid backlog clutter

### 4.2 Review Failed

- Task is moved back to **Ready** or **In Progress**
- Developer addresses review feedback
- Task is resubmitted for Review once changes are complete

**Ownership:** Reviewer / Developer

---

## 5️⃣ Testing – Staging

- Testing subtask is marked for the **Staging environment**
- Tester(s) are assigned by Mpho
- Testing is performed against the original brief and acceptance criteria

If testing fails:
- Feedback is provided
- The original task returns to **Ready** or **In Progress** as required

**Ownership:** Tester(s) / Mpho

---

## 6️⃣ Testing – Production

- Once staging testing passes:
  - Task is labelled **Production**
  - Production testers are assigned
- Testing is performed on the live/production environment

**Ownership:** Tester(s)

---

## 7️⃣ Completion

- When production testing passes:
  - Task is officially marked **Completed**
- Developers may not mark tasks as Completed before production testing has passed.

**Ownership:** Project Coordination / Testing

---

## 🔒 Key Enforcement Rules

- Developers **cannot** move tasks directly to **Completed**
- No task may skip **Review**
- No task may skip **Testing**
- **Time logging is mandatory before Review**
- Testing tasks are created only after review approval
- Devs develop, testers test, project staff coordinate

---

## 🎯 Purpose of This SOP

- Keep developers focused on development
- Keep project staff focused on coordination and reporting
- Ensure accurate time tracking
- Provide clear visibility across multiple projects
- Reduce ambiguity and unnecessary task movement
