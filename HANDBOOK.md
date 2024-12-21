## Values, Principles, Beliefs

My goal for organizations is that absolutely everybody understands why their work is important and how it drives the business forward.

- **Constant learning and growth**
  - I'm driven by the need to learn continuously. I expect the same from my team — always pushing forward.
- **Move fast and build things that last**
  - I like to prototype fast and identify potential issues early.
  - A stitch in time saves nine.
  - Things I absolutely cannot compromise on: leaking customer data, losing them money or otherwise affecting them negatively.
- **Patient observation and empirical evidence over assumptions or declarations**
  - I like to observe how orgs behave and adapt rather than force my style of work onto others. Expect me to be relatively quiet at first and then not be quiet anymore.
  - Purposes are deduced from behavior, not from rhetoric or stated goals.
  - The behavior of a system cannot be known just by knowing the elements of which the system is made. The best way to deduce the system’s purpose is to watch for a while to see how the system behaves.
- **Be direct in communication**
  - When you need an answer, keep it yes/no or number-based. Be brief, and don't bury important information.
- **Take ownership and ask for clarity**:
  - If the task is hard, it's my fault for not giving enough details, ask me for what you need — I won't take it personally.
- **Lack of feedback stalls growth**
  - I respond to feedback immediately and definitively. If you're not telling me what could be better, it's holding both of us back.
- **Compassion**
  - Treating others as you’d like to be treated works if they want exactly what you want, but no two people think exactly alike. When possible, I prefer to treat others as they would like to be treated.
- **I like lists**

## Engineering style

- I like my design docs to be easy to read and include implementation details (code snippets, screenshots, etc.) — API usage, logging, monitoring, debugging are part of software design.
- Solutions must be grounded in measurable outcomes rather than assumptions.
- Sometimes I prefer to build a quick prototype before any design docs, this allows me to identify blindspots in my plans.
- Minimalistic and efficient solutions over adopting large ecosystems unnecessarily — build for now, not the future.
- Technical debt should be documented and planned for — not ignored or accumulated blindly.
- Documentation should focus on "why" rather than "what".
- Prefer standard patterns and conventions over clever solutions — maintainability trumps cleverness.
- Regular refactoring is part of feature development.
- Code reviews are for knowledge sharing rather than just finding bugs.

## How to communicate with me

- **I prefer async, waiting to hop on a call kills momentum.**
  - Keep it brief — use bullet points over long explanations.
  - When asking for decisions, try to frame questions so they can be answered with yes/no or numbers. Consider "how can i help?" or "what do you need?" vs "do you think i should work on x?".
  - Not getting updates makes me anxious, 'working on x', 'this is done', 'i'm blocked here' are all good messages to send me.
- **Message me on slack when possible.**
  - If its urgent text me, assume I'm about to open you message on my apple watch — keep it short, no links.
  - I want to reply, but if I take too long, I might lose the opportunity.
- **Nobody should ever be blocked because of me.**

  - I respond to pings quickly but I don't expect reciprocity.
  - I do not mind interruptions from flow.
  - If you need a decision I will make a decision.

- **Use clear subject lines**: Make the topic or action needed immediately apparent.

  - Good: "Urgent: Main API endpoint failing in prod"
  - Bad: "Quick question about the API"

- **Structure messages for quick decisions**: Present options clearly, preferably as numbered choices.

  - Good: "Auth implementation options:
    1. JWT + Redis
    2. Session-based
    3. OAuth2
       Default to #1 if no response by EOD."
  - Bad: "How should we handle auth?"

- **Flag time-sensitive items**: Use prefixes like [P0], [P1], or [FYI] in subject lines.

  - Good: "[P0] Memory leak in production server"
  - Bad: "Server acting weird"

- **Use visuals when possible**: Error logs, metrics, or code snippets convey information faster than text.

  - Good: "DB query performance drop: [metrics screenshot]. Fix?"
  - Bad: "The database seems slower after the last deployment. The read operations are taking longer than usual..."

- **End with a clear next step**: Always include what action you need from me.

  - Good: "PR #123 ready. Needs arch review by tomorrow."
  - Bad: "I pushed some changes, take a look when you can."

- **Assume I'm on the run**: Send error messages or logs directly along with links.

  - Good: "Build failing: [error screenshot] [link]. Rolling back."
  - Bad: "Check CI pipeline: [Jenkins link]"

- **Keep it short**: Put the ask at the top. Give me a clear call to action.

  - Good: "Need approval on API schema changes. Details in PR #234."
  - Bad: "Hi, I've been working on refactoring our API schema to better handle the new user requirements. I've made several changes to the data models and added some new endpoints. The validation layer has been updated too. Would love your thoughts on the approach..."

Note: these are guidelines, not requirements.

## How I prioritize work and delegate

- **Client work always comes first**: Client tasks are the top priority. We should always be in the process of moving things along or waiting for client feedback.
- **Delegate early to avoid issues later**: If something isn't clear, ask for clarity early. Spending more time upfront is better than having to fix it later.
- **Maintain multiple active tasks**: If you get blocked you should already have another task to work on. It also helps to overcome procrastination by switching contexts.
- **Time-box your struggles**: If you're stuck on something for more than 2 hours, switch to your secondary task and seek help.
- **Keep meetings focused**: Come prepared with an agenda, take notes, and end with clear action items.
- **Constant progress updates**: Share brief updates on Slack - what you did, what's blocking you, what's next.
- **Use Fridays for personal growth**: Provided client work is in progress, Fridays are a good time for personal projects and knowledge sharing with the team.

## How to work with me effectively

- **I miss what others catch, and I catch what others miss**: Different people filter out different kinds of information. Then, what we don't filter out becomes our focus.
- **Take initiative on solutions**: Come to me with proposed solutions, not just problems. I value proactive thinking.
- **Keep me in the loop**: Small, regular updates prevent misalignment. Radio silence is worse than bad news.
- **Give direct feedback**: Challenge my ideas and point out what's not working. I value honesty over politeness.
- **I value outcomes over processes**: If you need structured guidance, ask — I might assume you’re comfortable figuring things out.
- **I focus on execution, sometimes at the cost of exploration**: If you think a problem needs deeper discovery, push back on my urgency.
- **I assume clarity where there is ambiguity**: If something is unclear, ask for clarification — I might think it’s obvious when it’s not.
- **I challenge ideas hard, not people**: I argue ideas rigorously, but it’s never personal. If it feels like it is, let’s clear it up.
- **I move fast and expect others to keep up**: If I seem to be rushing ahead, tell me when you need time to catch up or digest.
