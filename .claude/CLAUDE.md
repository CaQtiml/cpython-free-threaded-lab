../AGENTS.md

Before working on free-threading (`Py_GIL_DISABLED`) code in this checkout, read
`ft-notes/AGENT_BRIEF.md` first. It is short and lists the generated files you must never
hand-edit, why a missing lock is usually not a bug here, and the version facts that override
recalled knowledge about free threading.