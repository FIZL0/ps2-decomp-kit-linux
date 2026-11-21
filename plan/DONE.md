# DONE — the archive

Finished tasks, newest at the top. `./kit plan tick <ID>` moves a line here from `plan/TODO.md`, with its
text intact, so a question like "when did the FPU model land, and what did it not cover?" is one `git log`
away. Nothing is ever edited by hand here either; `./kit plan <ID>` finds a task whichever file it is in.

### Next (in this order)
- [x] **B2** (follow-up, critical) ./kit hands every command it does not own to agent-runner (since, control, status, needs, pause, slots, attach, upgrade…) after runner.use(), the way run and stop already go, instead of 'unknown command' exit 2. openmx's runner feed and control sessions on rycs kept trying './kit since' and './kit control' and failing (agent-runner B71 worked around it by calling the runner itself). ./kit --help names them under keep going; the Windows edition too if it shares cli.py. | files: ps2kit/cli.py, ps2kit/runner.py | test: tests/test_cli.py
