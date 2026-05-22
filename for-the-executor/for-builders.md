# For Tool Designers and Developers

If you build software, the manifesto's Sovereign Filter principle
opens several small, immediately implementable directions.

## The Smallest Useful Tools

**1. Phone number ticket system**
A tool that lets a user keep their phone number public, but blocks
all incoming calls except from numbers they have explicitly
"ticketed." Trivial to build with existing telephony APIs.

**2. Email ticket gateway**
Same principle for email — only ticketed senders reach the inbox,
all others receive a polite auto-reply requesting a ticket.

**3. Trust-based content curation**
A reader interface where the algorithm only shows content from a
trust graph the user has explicitly built, not from open-ended
recommendation. No engagement optimization. Time-weighted.

**4. LifeBite journal**
A daily prompt that asks just one question ("what did you eat
yesterday?" or "what surprised you today?") and stores the entries
as a local, encrypted, time-stamped chain. The chain itself becomes
a kind of process-based identity proof.

**5. Cell finance tool**
A simple expense-sharing app designed for 3-5 person "Context
Family" cells rather than couples or large groups.

## Design Principles

- **Open source** — never let one company own these patterns
- **No telemetry** — the tools must not become surveillance
- **Self-hostable** — users should be able to run them themselves
- **Boring tech** — use stable technologies that will outlast trends
- **Tiny** — under 1000 lines of code each, ideally

## If You Build Something

Open an issue here labeled `tool` with a link.
The next builder may extend your work.

