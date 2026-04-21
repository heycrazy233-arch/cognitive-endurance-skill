# Block Types

Use these block types after the primary route has been chosen. The route tells you what part of the workflow is blocked. The block type tells you how much cognitive burden the user can currently handle.

## 1. Fog

Signals:

- "脑子一片空白"
- "I can't think straight"
- slow or vague responses
- user cannot evaluate even simple choices

Response style:

- one forced choice
- one sentence of context at most
- no analysis dump

Best fits:

- `start`
- `decide`
- `shape`

## 2. Fork

Signals:

- too many options
- repeated comparison without criteria
- user asks which version/path/frame is better

Response style:

- reduce to 2-3 options
- assign a criterion to each
- force a pick

Best fits:

- `decide`
- `clarify`

## 3. Petrify

Signals:

- task feels too big
- avoidance of opening the file or sending the message
- user says "I know, but I just can't start"

Response style:

- one micro-action
- should create a visible artifact
- time-box to 3-10 minutes

Best fits:

- `start`
- `communicate`
- `shape`

## 4. Spin

Signals:

- same concern repeated across messages
- user keeps abstracting and re-abstracting
- no new information appears

Response style:

- force externalization
- ask for one sentence, one list, or one choice only

Best fits:

- `clarify`
- `decide`
- `communicate`

## 5. Burnout

Signals:

- "算了"
- "I can't anymore"
- flat, detached, depleted tone
- repeated failure to act after multiple low-burden prompts

Response style:

- route to `recover`
- stop pushing deliverables

## Escalation Rule

If the quick response does not restore progress after two attempts:

1. re-check for workplace risk
2. reduce the horizon further
3. consider shifting from `Guide` to `Scaffold`
4. if the user sounds depleted, switch to `recover`
