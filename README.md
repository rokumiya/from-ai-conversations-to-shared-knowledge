English | [Japanese / 日本語 (authoritative version)](README.ja.md)

# From AI Conversations to Shared Knowledge

## Making AI a Gateway to Humanity’s Shared Knowledge

> In a conversation with AI, a person selects only the part they feel would be a shame to lose, and, if needed, the AI reshapes it so that it can stand on its own outside the conversation.
>
> After reviewing the text, attribution, and sharing scope, the person can preserve it where others within that scope can access it. Later, it can be rediscovered—with its source—in a conversation between another person and an AI.

This is not a finished proposal for a particular product or storage format. It is a concept note describing the user experience and basic principles of such a gateway.

The goal is to let another person rediscover and use an insight someone wants to preserve, beyond the original conversation. Sharing among users within a single provider’s service can achieve this goal. Publication on the public web is an option for extending its reach, not a prerequisite or a required final destination for every implementation. In any form, the person must explicitly select what to share and review the text, attribution, and sharing scope.

- **Version:** 1.1-draft
- **Date:** 2026-10-23
- **Status:** Revision draft / English translation
- **Author:** rokumiya
- **Authoritative version:** [Japanese](README.ja.md)
- **AI assistance:** This proposal emerged from a conversation between a human and ChatGPT, and AI was also used in drafting the document. Final responsibility for the published content rests with its human author.
- **License:** [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)

---

## 0. Where This Proposal Began: Concern for Shared Knowledge and a Conversation Worth Keeping

The idea emerged from a private conversation about AI search and sources of information on the web. It began with two concerns.

One was the possibility that shared knowledge might diminish in the future.

The process of asking questions, trying things, and finding solutions has often been recorded in forums, Q&A sites, and blogs, where others could refer to it later. If such exchanges come to take place entirely in private AI conversations without being preserved elsewhere, might there also be fewer opportunities for new experiences, corrections, and discoveries to enter shared knowledge?

This is not a claim that shared knowledge as a whole is already declining. It is a concern that, while AI draws on existing shared knowledge, the paths through which new insights reach others could narrow, weakening the renewal of knowledge on which both people and AI will depend.

The other concern was about the very conversation in which this issue was being discussed.

> **It would be a shame to close this conversation and let it disappear.**

Concern for the future of shared knowledge, together with the immediate feeling that this conversation was worth keeping, led to this proposal.

As the discussion unfolded, it led to a question: could AI do more than draw on knowledge already available on the public web? Could new knowledge and ideas that emerge in conversations with AI be returned to the public sphere?

The conversation was too long for a short social media post. It was not a paper, a product specification, or a finished business plan.

It was still only a concept, with no settled path to implementation.

Even so, I did not want the idea to end inside that conversation.

The internet made it possible for anyone to publish their words to a global audience.

Search engines made already-published writing discoverable by anyone.

Conversational AI may be able to act one step earlier: as a gateway through which people can bring thoughts that have not yet taken the form of finished work into the public sphere, by their own choice.

AI need not be merely a machine that absorbs knowledge created by people. It can become a medium that connects the experiences and ideas of people who might otherwise never meet, across time and place.

I want this proposal itself to serve as an initial example of the idea in practice.

The mechanism for passing insights on, however, does not have to be open to the entire public web from the start. Sharing within one provider’s service would not fully address the concern about a shrinking supply of sources on the public web, but it could preserve insights that would otherwise end inside a private conversation as shared knowledge another person can reference. That, too, is worth making possible.

---

## The Proposal Begins with a Single Action

What if an AI conversation offered an action like this?

> **Keep this part**

What people keep does not have to be anything grand.

- A small dab of yuzu kosho on a soft-boiled egg turned out to be delicious.
- A pancake maker turned out to have an unexpected use.
- The same inefficiency seems to recur at the same point in this task every time.
- This tool might be much easier to use if just this one part were changed.
- The method I tried did not work, but this particular condition still seems relevant.
- I cannot explain it well yet, but perhaps we need a system like this.

Here, “shared knowledge” is not limited to knowledge whose accuracy has been established. It also includes one-line practical tips, personal experiences, questions, failures, and untested ideas.

It could also be a thought like this proposal: too long for a short social media post, yet not developed enough to become an article or formal proposal.

What matters is not whether it is an impressive finished product.

What matters is simply that **the person thinks, “I want to keep this.”**

The “gateway” in this proposal works in two directions:

1. It gives people a way to move something born in a private conversation into shared knowledge.
2. It gives another person and an AI a way to rediscover it in a later conversation.

The goal is not merely to let people post from an AI interface. It is to connect two conversations separated by time and place through shared knowledge.

---

## 1. So Much Is Already Being Put into Words in Conversations with AI

People do more in conversations with AI than ask questions and receive answers.

- They explain their circumstances.
- They recall past experiences.
- They articulate what is inconvenient or difficult.
- They try talking through a tentative idea.
- They challenge an AI’s response.
- They gradually organize their thoughts.
- They report what happened when they tried something.
- They arrive at ideas that were not there at the start.

In this process, things that might once have remained only in someone’s mind have already been put into words.

Yet when the conversation ends, most of what was said effectively ceases to exist as shared knowledge.

Even if the conversation remains in a personal account history, it does not exist as shared knowledge that other people can search, cite, or connect with related ideas.

A short thought posted on a platform such as X gains a public URL and at least a chance of being found. A blog can preserve a longer idea.

But turning an AI conversation into a post or an article requires doing all of the following again:

- Decide which part to extract.
- Rewrite it for people who do not know the surrounding context.
- Choose where to publish it.
- Adapt it to the required length and format.
- Remove personal context.
- Check whether it is safe and appropriate to publish.

For a single sentence, posting it on X may seem easy enough. Even then, people often do not do it.

More complex thoughts that do not yet even have a name will not fit in a short post, yet are not finished enough to become an article. Thoughts in this middle ground are especially likely to disappear because they have nowhere to go.

AI itself should be able to lower this final barrier.

---

## 2. Proposal: “Keep this part”

The original conversation remains private.

Only the text the person selects and approves is shared, within the scope they approve. This may be within one provider’s service or on the public web.

The person selects the passage they want to keep, or says something like this to the AI:

> I want to keep what we just discussed.
>
> Make only this part available for someone else to find later.
>
> Leave out my personal circumstances and turn this idea into something I can share.

The AI reshapes the selected passage so that it can be read outside the conversation.

If it is short, it can remain a single sentence.

If it is complex, the AI might organize it into a title, a short summary, background, the idea itself, and what is still unknown.

The person reviews the exact text, chooses how—or whether—to be credited, and checks who can access it and in which AI responses it may be referenced, making edits if necessary. Nothing is shared until the person explicitly approves it. The confirmation screen must clearly distinguish publication on the public web from sharing limited to the service.

```text
[Private AI conversation]
        │
        │ The person chooses “Keep this part”
        ▼
[AI makes it readable outside the conversation]
        │
        │ The person reviews the text, attribution, and sharing scope
        ▼
[Preserved as shared knowledge]
        │
        ├─ Someone finds it
        ├─ It connects to a related idea
        ├─ Someone adds the results of trying it
        ├─ Someone adds a counterargument or clarification
        └─ It leads to something that gets built
        │
        ▼
[A later conversation between another person and an AI]
        │
        └─ Rediscovered with a source: “Someone previously preserved an idea like this”
```

The AI must not decide on its own that something is “valuable” and share it.

The person—not the AI—decides whether anything is kept.

---

## 3. What Can Be Kept?

As a general rule, the system should not narrowly restrict the kinds of material people can keep, provided they want to keep it and have the right to share it within the chosen scope.

| Example | One way to preserve it |
|---|---|
| A small practical tip | Keep it as a one-line note |
| A food combination that tasted good | Present it as a personal impression |
| An unexpected use | Include the tool, how it was used, and any cautions |
| An inefficiency noticed in daily life or at work | Record where it occurs and what happens |
| A past experience or local memory | Include the time and place, and note that it is a personal recollection |
| A question or sense that something is off | Keep it as a question without forcing a conclusion |
| An untested idea | Record the problem, the proposed idea, and what remains unknown |
| A failed approach | Record what was tried and how it failed |
| Research or test findings | Add conditions, method, observations, and inferences as needed |
| A long, complex concept | Separate a summary from the main text so it can be discussed later |

There is no hierarchy among these forms.

Shared knowledge is not limited to reproducible technical information. Someone’s practical tip, an observation from the workplace, or an idea that has not yet taken shape may become a starting point for someone else.

At the same time, keeping something does not certify that it is true, original, or important.

What matters is not confusing one kind of content with another.

- Was it actually tried?
- Is it a personal impression?
- Is it something heard from someone else?
- Is it an inference?
- Is it a tentative idea?
- Is it a question that has not yet been investigated at all?

This does not mean asking people to classify every contribution manually. If the nature of the content is already clear from the writing, that is enough; when useful, AI can suggest a short label.

Classification is not a prerequisite for sharing. It is an optional aid that helps readers avoid misunderstanding what they are reading.

---

## 4. Let People Keep Things Without Polishing Them First

This gateway must not feel like submitting a paper or registering a dataset.

If preserving a short thought requires filling in dozens of fields, many people will preserve nothing at all.

The smallest shared item could be as simple as this:

```text
I found that a tiny dab of yuzu kosho on a soft-boiled egg was delicious.

— Anonymous · 2026-08-26 · From an AI conversation
```

The body may be all the person has to provide. The system can automatically add a small note with the date, the chosen attribution, and the fact that the item emerged from an AI conversation.

For a technical test, more information can be added when needed.

```text
In Product X v1.4, behavior Y occurred twice under condition A.
The cause may be setting Z, but I have not verified it.

Type: Observation and inference
Environment: Windows 11 / Product X v1.4
Validation status: One person, one environment only
```

A longer concept can include further background and open questions.

In other words, instead of imposing the same strict format on every contribution, the system should allow structure to be added in layers according to the content.

```text
Short shared note
    ↓ If useful
Add background, classification, and related information
    ↓ If useful
Link tests, counterarguments, revisions, and derivative ideas
```

Structure is not a gate that must be passed before something can be kept.

It is an additional layer that can make an item easier to find, reduce misunderstanding, and connect it to other knowledge.

---

## 5. What AI Makes Possible

Search engines made it easier to find what someone had already written.

Conversational AI can work one step earlier.

**It can help turn human thoughts that have not yet become public documents into a shareable form when the person chooses to do so.**

To do that, AI can help with the following:

- Extract the part of the conversation the person selected.
- Make it readable to someone who does not know the surrounding conversation.
- Shape it into a one-line note, a short post, or a longer concept, depending on the content.
- Draft a version with personal circumstances removed.
- Distinguish among observations, impressions, inferences, and ideas.
- Find similar earlier contributions.
- Translate it into another language.
- Later connect it with related experiences, counterarguments, or implementations.

In a later conversation, instead of merely listing search results, an AI could connect one person’s thinking with another’s in a form like this:

> Someone previously preserved a similar idea. It has not been implemented, but they framed the problem this way.

The AI does not need to determine the value of the idea.

Many ideas may already exist, may not work for one reason or another, or may be of no use at all.

Even so, a small number may gain value only when they connect with another person’s knowledge or technical skill.

The person who has an idea does not need to also be the writer, tester, implementer, and promoter.

It is enough for the person to preserve it so that someone in the future can find it and judge its value.

### Benefits for Both Providers and Users

By connecting people through their insights, this gateway could benefit both service providers and the people who use their services. The following describes possible mechanisms and hypotheses to test through deployment, not guaranteed outcomes.

#### Keep Knowledge Current and Improve Answers

Everyday conversations can contain new uses, recently changed conditions, results from practical trials, and corrections to existing explanations. Preserving only the parts people select and approve for sharing as external records with dates and sources could create a continuing path for updating the knowledge a service can reference.

For example, one person might preserve a note saying, “This method stopped working after the recent update,” and another might add the results of trying an alternative. A later AI response could then present the changed conditions and corrections with sources, alongside the older explanation.

This does not depend on collecting entire conversations or waiting for model retraining. Searching and referencing approved records alone could make answers more current, specific, and relevant to the conditions at hand.

New posts, or a large number of posts, do not automatically produce correct answers. Responses must take sources, dates, applicable conditions, corrections, and counterarguments into account without turning unverified experiences into general facts. A lightweight way to preserve rough contributions is compatible with careful use of them in answers.

#### Pass Discoveries On, as Well as Receive Answers

For users, receiving help from other people’s experiences is one benefit. Being able to pass their own discoveries and practical tips on to someone else can itself be a reason to participate.

The motivation behind a post on a forum or Q&A site—“My experience might help someone”—can also have a place within an AI conversation. If people can select and preserve something they have already discussed, the effort of composing a separate post can be reduced.

People may want to share a discovery even when no reaction comes back. Rewards, rankings, and reaction counts do not need to be prerequisites for participation. Making the use of a contribution visible can remain an optional addition, as described in Section 8.

The experience of “I can get help, and I can leave something for others” could give people a reason to choose a service and keep using it. Even sharing within one provider’s service could support that motivation if the contribution can reach another user.

#### Let Knowledge and Participation Increase Each Other’s Value

Users preserve varied experiences; those contributions help others find answers or make discoveries; some of those users then preserve experiences of their own. If that cycle works, more participants and useful contributions could reinforce the value of the service through a network effect.

For providers, competitiveness could come not only from model performance, but also from the body of knowledge users have approved for sharing, the ability to find and use it appropriately in answers, and an experience people can trust when contributing. Users could spend less effort solving the same problems alone and gain more opportunities to encounter experiences and ideas beyond their own.

More users or posts alone would not establish this cycle. It requires relevant retrieval, attention to corrections, ways to manage noise, and trust that people’s choices will be respected. Knowledge accumulated within one provider’s service could become a distinctive source of value for that service. A service can also create value through the quality of discovery, referencing, and user experience when the knowledge is shared on the public web. Either form must respect the scope of use the person approved.

---

## 6. Model Improvement Is Not the Same as Preserving Part of a Conversation as Shared Knowledge

AI services may offer settings that control whether conversations can be used to improve their models.

But allowing a conversation to be used for model improvement is not the same as choosing to preserve part of it as a shared item that others can reference.

Information used for model improvement is generally not available as a discrete, source-linked record. It cannot be examined in ways that answer questions such as these:

- Who said it, and when?
- What did the person intend to share, and with whom?
- Was it an experience, an inference, or a joke?
- Was it later corrected?
- Did anyone try it?
- Did the knowledge help anyone?

This proposal is not about granting model-training permission for an entire conversation.

The original conversation remains private. Only the part selected by the person is preserved as a standalone shared item, accessible within the scope they approved.

Rather than trying to encode it in model weights, the idea is to preserve it as an external shared resource with source information that both people and AI can search and reference.

The same distinction applies to sharing limited to a service, as discussed in Section 11. Searching and referencing records within the approved scope is separate from using them for model training; approval to share must not be interpreted as consent to training.

### Keep Human and AI Contributions Distinct

A shared item may combine something the person said, material the AI reorganized for clarity, something newly proposed by the AI, and ideas that took shape jointly through the conversation.

The person’s approval for sharing must not imply that they independently originated everything in the item. When useful, simple labels such as “personal experience,” “organized by AI,” or “developed through dialogue” should make the distinction visible.

---

## 7. What People Preserve Can Grow

The content does not need to be complete when it is shared.

Other people can later add responses such as these:

- I tried it too, and it worked.
- It did not work for me.
- There is another way to use it.
- A similar idea existed before.
- It does not hold under these conditions.
- I tried building it.
- This idea led me to a different one.
- Part of the explanation is wrong.

These responses do not have to be merged into a single definitive answer.

The original contribution can remain intact, with additional context, counterarguments, revised versions, and derivative ideas linked to it.

A brief remark can remain a brief remark. More complex ideas can grow over time.

---

## 8. If Possible, Let Contributors Know What Happened Next

This is not required for the proposal to work.

People do not put things into the world only to receive rewards or reactions. Even when they do not know whether something will be useful, wanting to keep it is reason enough.

What matters first is a simple way to move something from a private conversation into a place where another person can reference it.

Beyond that, if it can be done without excessive tracking or a complex system, it would be valuable to let contributors know what happened to the things they preserved.

- Someone found it as related information.
- It was referenced in an AI response.
- Someone reported trying it.
- Someone added a counterargument or clarification.
- It led to another idea or an implementation.

There is a distinct kind of joy in learning later that a small remark helped someone you do not know.

But if providing that feedback would make the gateway so difficult to implement that the system itself never gets built, the feature can wait.

---

## 9. Keep It Easy to Use—and Safe

The gateway should be simple, but that does not mean AI should automatically share conversations.

### Keep the Original Conversation Private

Only the passage selected by the person and reviewed in the form to be shared is shared.

### Show the Exact Text Before Sharing

Do not ask people to trust that the AI “must have anonymized it correctly.” Before sharing, show them exactly the text and information that people outside the conversation will see.

### Use AI Screening Only as an Aid

AI can warn about possible issues such as:

- Personal information, including names, addresses, and contact details
- Information about third parties mentioned in the conversation
- Confidential information involving clients, employers, or research collaborators
- Excessive reproduction of copyrighted material
- Security information that would be dangerous to share
- Unpublished inventions or information the person may wish to treat as a trade secret

Automated screening is not perfect. The person must make the final decision about sharing.

### Explain the Limits of Taking Something Back

Even if an item can later be hidden or withdrawn, it cannot be fully taken back once others have saved, quoted, or copied it. This must be explained clearly before sharing.

### Confirm the Sharing Scope and Let People Choose How They Are Identified

The destination may be within a single provider’s service or on the public web. Keeping something only for oneself remains distinct from sharing it so that it can reach another person.

Limited sharing still requires prior review of the text, attribution, who can access it, and the scope of AI responses that may reference it. Show that scope briefly and clearly without requiring complex access settings each time. Widening the scope later, such as by publishing on the public web, requires the person’s renewed, explicit approval. Limited sharing also does not remove the need to explain the limits of withdrawal.

The person should, however, choose how—or whether—to be credited. They may be credited under their real name or a pseudonym, or the item may be published anonymously.

To keep the action lightweight, the system should default to the attribution the person uses most often and let them change it only when needed.

---

## 10. What This Proposal Does Not Aim to Do

- Save and share every AI conversation
- Let AI automatically select “valuable ideas”
- Treat everything submitted as correct knowledge
- Require academic-paper-level evidence for every contribution
- Turn short notes into complicated data-entry forms
- Replace blogs, social media, wikis, Q&A sites, or papers
- Treat consent to model training as consent to preserving material as shared knowledge
- Limit contributions to technical information

This system would create a small outlet even for thoughts that are not yet developed enough for existing publication channels.

---

## 11. If We Were to Test It

There is no need to build a global knowledge infrastructure from the outset.

### Sharing Within One Provider’s Service Can Be Enough

Making publication, search, operation, and correction work broadly across the public web may be a long undertaking. There is no need to wait for that before starting a system for preserving shared knowledge.

An initial implementation could let users of one provider’s service share insights they have explicitly approved. “Within one company” here means that a contribution can reach other users of that provider’s service, rather than referring only to internal information sharing among its employees.

Reusing existing conversation interfaces, accounts, and search capabilities could make it easier to try selection, reshaping, review, sharing, and rediscovery on a small scale. The system can work only with approved shared items while keeping the original conversations private.

This is not merely a temporary step toward public web publication. Even if the system remains within one provider’s service, it achieves the goal of preserving shared knowledge when another person can find and use an experience someone has left. Operation by one company, or accumulating and providing knowledge exclusively within its service, is not categorically excluded from this proposal.

Public web publication and connections to other services can be optional extensions. If introduced, they must not automatically widen the scope the user approved; the content and expanded scope must be confirmed again. Instead of requiring numerous settings, the interface can begin with a short, accurate description such as “Share with users of this service” for the person to review.

The first question to test is not a technical one, but this:

> If an AI conversation offered a “Keep this part” option, would people actually preserve things they would otherwise let disappear?

### A Minimal Prototype

1. The person selects part of a conversation or says, “I want to keep what we just discussed.”
2. The AI creates text that can be read outside the conversation.
3. The person reviews and explicitly approves the text, attribution, and sharing scope.
4. The item is saved to a simple page accessible to people within the approved scope.
5. Each item receives a URL and timestamp and becomes searchable in full text within that scope.
6. In a later AI conversation with another user within the same scope, the AI can find a related item and present it with its source.

For limited sharing, the scope must be respected in search results and AI responses as well as on the page itself. If public web publication is chosen, the item can be made accessible to anyone.

At first, Markdown or simple JSON would be enough as a storage format. People should not have to think about YAML or schemas.

### Examples to Include in a Prototype

Testing only technical findings would narrow the concept again.

The examples should include at least the following different kinds of material:

- A one-line food or everyday-life tip
- An unexpected use for a tool
- A personal experience or memory
- A problem noticed in daily life or at work
- An untested idea
- A failed attempt
- Technical information that applies under particular conditions
- A long concept like this one

### Questions for Judging Success

- Is the process of keeping something lightweight enough?
- Does the shared text match what the person intended?
- Can the person understand and approve who can access it and in which AI responses it may be referenced?
- Does it make sense to someone who has not seen the original conversation?
- Does the feature lead people to preserve things they otherwise would not have kept?
- Can personal information and secrets be caught before sharing?
- Can someone later find, use, and connect the contribution with related material?
- Can a related contribution surface naturally in another AI conversation?
- Would contributors want to preserve something again even without notifications about what happened afterward?
- Compared with answers that do not reference shared items, do answers become more current and specific while reducing errors and reliance on outdated information?
- Do new contributions and corrections appear in later searches and answers while respecting the sharing scope?
- Does being able to preserve discoveries give people a reason to choose the service and keep using it?

---

## 12. Existing Systems We Can Learn From

This concept does not require building everything from scratch.

Short-form publishing, blogs, online publishing platforms, wikis, Q&A sites, conversation sharing, data donation, and knowledge graphs already perform related roles.

There are also useful examples of sharing knowledge from AI conversations. Two especially relevant examples are:

- [**Stack Overflow for Agents**](https://stackoverflow.blog/2026/06/10/announcing-stack-overflow-for-agents/) provides a process in which agents draft entries based on knowledge gained during software development, humans review and publish them, and others validate them.
- [**The Foundation**](https://github.com/dannwaneri/chat-knowledge) is an implementation that retrieves AI conversations, extracts knowledge from them, allows the extracted knowledge to move from private to public, and supports federation.

Many other mechanisms in social media, annotation, knowledge management, and provenance tracking can also inform an implementation.

The focus here is not a domain-specific posting system or the sharing of entire conversations.

It is **an everyday outlet through which anyone can choose to keep just one part of a private AI conversation—from a one-line tip to a long, unfinished concept.**

Existing projects can teach us about publication flows, validation, search, and preserving provenance. By combining reusable pieces, this everyday outlet could be made real.

---

## 13. Open Questions

- Who should operate the place where this shared knowledge lives?
- When one company operates the system, what terms should govern shared items and what happens if the service ends?
- If needed, how can export, public web publication, and connections to other services be supported?
- How can the system allow rough contributions while limiting spam, promotion, and harassment?
- How can it avoid judging value in advance while maintaining enough quality for useful discovery?
- How should similar contributions be grouped without deleting them?
- How can personal experience be distinguished from dangerous claims about other people?
- How should corrections, withdrawals, and deletion requests be handled after sharing?
- How can people be guided through checks involving copyright, licensing, inventions, and trade secrets?
- How can we ensure that AI-generated summaries do not change what the person meant?
- How can one-line notes and long concepts remain discoverable in the same place?
- How much messiness—including errors, ideas already proposed elsewhere, and contributions that are not useful—should be accepted as an inherent property of shared knowledge?

These questions matter, but they should not become reasons to complicate the initial action.

Keep the gateway simple, and design the necessary safety, history, validation, and governance behind it.

---

## Change Log

### v1.1-draft — 2026-10-23

- Added a founding concern that solving problems entirely in private AI conversations could reduce opportunities for new experiences and corrections to enter shared knowledge.
- Clarified the goal as enabling another person to rediscover and use an insight someone wants to preserve, beyond the original conversation.
- Included sharing limited to one provider’s service as an implementation that can stand on its own, and changed public web publication from a prerequisite to an optional extension.
- Removed the categorical exclusion of knowledge ownership by one company.
- Added continuing knowledge updates, answer quality, user motivation, network effects, and competitiveness as possible benefits to test.
- Specified explicit review of text, attribution, and sharing scope, with renewed approval when the scope expands, and updated the prototype and evaluation questions.
- Preserved “Keep this part,” the privacy of the original conversation, lightweight contributions, optional visibility of contributions, and the distinction from consent to model training.

### v1.0 — 2026-08-26

- Published the first public release after aligning the full English translation with the authoritative Japanese version and finalizing the release metadata.

### v0.3-draft — 2026-08-26

- Clarified at the beginning that this document is not a finished design for a particular product, but a concept note about a user experience and its basic principles.
- Defined early that “shared knowledge” includes personal experiences, questions, failures, and untested ideas.
- Moved “Why preserve this proposal itself?” to Section 0, making clear that this proposal is itself an initial example of the idea in action.
- Made feedback about how a contribution was used an optional future feature rather than a requirement.
- Specified that shared items are published on the public web, while limited publication and access control are outside the scope of this proposal.
- Made the public text and the contributor’s choice of a real name, a pseudonym, or anonymity the central items to confirm before publication.
- Reframed the section on precedents as implementation references rather than an argument about originality.
- Removed the English summary and moved the full English translation to a separate README.md.
- Adopted CC0 1.0 Universal as the license for this document.

### v0.2-draft — 2026-08-26

- Shifted the focus back from “donating technical knowledge” to “a part of a conversation that the person wants to keep.”
- Explicitly broadened the scope from one-line practical tips to long, unfinished concepts.
- Made “keep” rather than “donate” the central action.
- Moved strict structure, confidence levels, and validation history from mandatory requirements to optional layers.
- Positioned AI as a gateway through which human thought that has not yet become a public document can enter shared knowledge.
- Made explicit the round trip through which a preserved thought can later be rediscovered in a conversation between another person and an AI.
- Redefined the minimal prototype as an experience of selection, reshaping, review, publication, and search rather than the registration of records in a public Git repository.

### v0.1 — 2026-08-26

- Organized the problem, design principles, user experience, example knowledge records, MVP, risks, and relationship to precedents.
- Centered technical validation records and provenance tracking.
